# VCC Document Engine — Base Template Library

These are the **base templates** the engine parameterizes for the four bespoke documents:

| File | Document | Standardization |
|---|---|---|
| `01_information_memorandum.md` | Information Memorandum (private placement) | Bespoke |
| `02_subscription_agreement.md` | Subscription Agreement (+ AI declaration annex) | Bespoke / ILPA-anchored |
| `03_fund_management_agreement.md` | Fund Management Agreement | Bespoke |
| `04_side_letter.md` | Side Letter | Bespoke |

The **constitution** is not here: it is the SAL model (open-ended / closed-end), adapted, not drafted. The **regulator forms** (ACRA incorporation, MAS Form 1A, OPERA Form 1) are retrieved, not templated.

---

## Merge syntax

Two constructs only, so a small JS parser can resolve them.

**Field substitution:** `{{fieldName}}` is replaced by the engine state value of that key.

**Conditional block:**
```
{{#IF flag}} ...text... {{/IF}}
{{#IF flag}} ...text... {{#ELSE}} ...text... {{/IF}}
```

Blocks may nest. A flag resolves true/false from the derived flags below.

---

## Field keys (map 1:1 to engine `state`)

| Key | Example value |
|---|---|
| `fundName` | Alpha Capital VCC |
| `office` | Singapore |
| `fye` | 31 December |
| `shape` | Standalone \| Umbrella |
| `subfunds` | Sub-Fund I, Sub-Fund II |
| `liquidity` | Open-ended \| Closed-ended |
| `investor` | Accredited / Institutional \| Retail |
| `manager` | Own CMS licence \| VCFM \| Hosted |
| `managerName` | Alpha Asset Management Pte Ltd |
| `origin` | Fresh incorporation \| Re-domiciliation |
| `strategy` | Private Equity \| Venture Capital \| Private Credit \| Real Estate \| Hedge \| Fund-of-Funds \| Single Asset |
| `geography` | Singapore \| Regional \| Global |
| `resDir` | resident director name |
| `mgrDir` | manager-linked director name |
| `indDir` | independent director name |
| `mgmtFee` | 2.0% per annum of NAV |
| `perfFee` | 20% of net profits |
| `hurdle` | 8% per annum |
| `lockup` | Quarterly redemption, 90 days notice, 12-month soft lock |
| `admin` | administrator name |
| `custodian` | custodian name |
| `auditor` | auditor name |
| `tax` | None \| 13O \| 13U |

## Derived flags (compute before render)

```js
const flags = {
  isUmbrella: state.shape === "Umbrella",
  isRetail:   state.investor === "Retail",
  isAI:       state.investor !== "Retail",
  isOpen:     state.liquidity === "Open-ended",
  isClosed:   state.liquidity === "Closed-ended",
  isHedge:    state.strategy === "Hedge",
  isReDom:    state.origin === "Re-domiciliation",
  ownLicence: state.manager === "Own CMS licence" || state.manager === "VCFM",
  isHosted:   state.manager === "Hosted",
  hasTax:     state.tax !== "None"
};
```

`{{subfundsList}}` is a helper: split `subfunds` on commas, trim, render as a lettered list.

---

## Sourcing

Original drafting for a Singapore VCC. Structure and best-practice content informed by:
- ILPA Model Subscription Agreement & Model LPA (Delaware-law PE reference): https://ilpa.org/industry-guidance/templates-standards-model-documents/
- Singapore Academy of Law model VCC constitutions (constitution only)
- MAS Securities and Futures Act, Code on Collective Investment Schemes, Notice VCC-N01

**Not legal advice.** Base templates to brief counsel and scaffold a data room. Every output must be reviewed by qualified Singapore counsel before use.
