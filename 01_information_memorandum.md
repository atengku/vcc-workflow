# INFORMATION MEMORANDUM
## {{fundName}}
### Private Placement Memorandum

> BASE TEMPLATE — VCC Document Engine. Bespoke document. Original drafting for a Singapore VCC; not legal advice. Resolve merge fields and conditional blocks against engine state, then review with counsel.

---

## IMPORTANT NOTICES

This Information Memorandum (this "**Memorandum**") relates to an offer of participating shares in {{fundName}}, a variable capital company incorporated in Singapore under the Variable Capital Companies Act 2018 (the "**Fund**").

{{#IF isRetail}}
NOTICE — RETAIL OFFER. Where shares are offered to retail investors, this Memorandum does not stand alone: the offer must be made in or accompanied by a prospectus registered with the Monetary Authority of Singapore ("**MAS**") and a Product Highlights Sheet, and the Fund must be an authorised scheme under the Code on Collective Investment Schemes. This Memorandum is then used for internal drafting and as the source document for that prospectus.
{{#ELSE}}
This is a restricted offer. Shares are offered only to accredited investors and institutional investors, or otherwise in reliance on the exemptions in sections 304 and 305 of the Securities and Futures Act 2001. This Memorandum has not been registered as a prospectus with MAS.
{{/IF}}

This Memorandum is confidential, is provided solely to the named recipient for the purpose of evaluating an investment, and may not be reproduced or distributed. Distribution and the offer of shares are restricted in certain jurisdictions; recipients in {{geography}} markets must observe applicable selling restrictions. Statements about future performance are forward looking and not guarantees. An investment carries risk, including loss of capital. Recipients should take their own legal, tax and financial advice.

---

## DIRECTORY

| Role | Party |
|---|---|
| The Fund | {{fundName}} (Singapore VCC) |
| Fund Manager | {{managerName}} ({{manager}}) |
| Administrator | {{admin}} |
| Custodian | {{custodian}} |
| Auditor | {{auditor}} |
| Registered office | {{office}} |
| Financial year-end | {{fye}} |

---

## 1. DEFINITIONS

Capitalised terms have the meanings given in the Constitution of the Fund. In case of conflict between this Memorandum and the Constitution, the Constitution prevails.

## 2. SUMMARY OF TERMS

| Term | Detail |
|---|---|
| Vehicle | {{#IF isUmbrella}}Umbrella VCC comprising the sub-funds at section 3{{#ELSE}}Standalone VCC{{/IF}} |
| Liquidity profile | {{liquidity}} |
| Eligible investors | {{investor}} |
| Strategy | {{strategy}} |
| Management fee | {{mgmtFee}} |
| Performance fee / carried interest | {{perfFee}} |
| Hurdle / preferred return | {{hurdle}} |
| Liquidity terms | {{lockup}} |
| Tax posture | {{#IF hasTax}}Applying for the section {{tax}} fund tax incentive (subject to MAS/IRAS conditions){{#ELSE}}No fund tax incentive applied for{{/IF}} |

This summary is indicative and qualified in full by the body of this Memorandum and by the Constitution.

## 3. THE FUND

The Fund is a body corporate with separate legal personality, governed by its board of directors in accordance with its Constitution, and managed by the Fund Manager to whom day-to-day authority is delegated.

{{#IF isUmbrella}}
The Fund is an umbrella VCC comprising the following sub-funds:
{{subfundsList}}
The assets and liabilities of each sub-fund are segregated and ring-fenced from every other sub-fund. The assets of one sub-fund may not be applied to discharge the liabilities of another. A sub-fund has no separate legal personality but is treated as a separate person for the purposes of insolvency and enforcement.
{{#ELSE}}
The Fund is a standalone (non-umbrella) VCC.
{{/IF}}

{{#IF isReDom}}
The Fund was established by transfer of registration to Singapore of a comparable foreign corporate fund, and is continued as a VCC.
{{/IF}}

## 4. INVESTMENT OBJECTIVE AND STRATEGY

**Objective.** [State the target return objective and benchmark, if any.]

**Strategy.** The Fund pursues a {{strategy}} strategy. [Describe the investment approach, sourcing, target investments, geographic and sector focus across {{geography}} markets, expected holding periods and portfolio construction.]

**Investment restrictions.** [State concentration limits, leverage limits, prohibited investments and any diversification policy.]
{{#IF isHedge}}
**Leverage and derivatives.** The Fund may employ leverage, short positions and derivatives within the limits in the investment guidelines. Use of a prime broker and any rehypothecation of assets are described at section 9.
{{/IF}}

## 5. THE MANAGER AND KEY PERSONS

The Fund Manager is {{managerName}}, operating as {{manager}}. {{#IF ownLicence}}The Fund Manager holds (or is applying for) a Capital Markets Services licence for fund management from MAS{{#IF isHedge}}{{/IF}}.{{#ELSE}}The Fund is managed under the licence of a MAS-licensed manager hosting the Fund Manager.{{/IF}}

[Insert biographies of key persons, track record and the basis of the team's edge. Identify any key-person event and its consequences.]

## 6. FEES AND EXPENSES

**Management fee.** {{mgmtFee}}, accruing and payable as set out in the Constitution.

**Performance fee / carried interest.** {{perfFee}}, subject to a hurdle of {{hurdle}}{{#IF isHedge}} and a high-water mark{{/IF}}.

**Expenses.** [State which expenses are borne by the Fund versus the Manager, including establishment costs, administration, custody, audit, legal and regulatory costs.]

## 7. SUBSCRIPTIONS, REDEMPTIONS AND TRANSFERS

**Subscriptions.** Shares are subscribed under the Subscription Agreement. {{#IF isRetail}}Retail subscriptions follow the dealing arrangements in the prospectus.{{#ELSE}}Subscriptions are accepted only from eligible investors who complete the accredited or institutional investor declaration.{{/IF}}

**Liquidity.** {{lockup}}.

{{#IF isOpen}}
Shares are redeemable at net asset value per share on each dealing day, subject to any notice period, gate or suspension provided in the Constitution.
{{#ELSE}}
The Fund is closed-ended. Redemptions are restricted; capital and returns are distributed on realisation of investments or at the end of the Fund's term.
{{/IF}}

**Transfers.** Transfers are subject to Manager consent and to the transfer restrictions in the Constitution and applicable law.

## 8. RISK FACTORS

An investment is suitable only for investors who can bear the loss of their capital. Principal risks include, without limitation: market risk; liquidity risk; concentration risk; key-person risk; valuation risk; operational and counterparty risk; {{#IF isHedge}}leverage, short-selling and derivatives risk; prime-broker and rehypothecation risk; {{/IF}}tax and regulatory change; and risks specific to the {{strategy}} strategy and to {{geography}} markets. [Expand each risk.]

## 9. VALUATION, NAV AND SERVICE PROVIDERS

Net asset value is determined under the valuation policy in the Constitution. The Administrator ({{admin}}) calculates NAV and maintains the register. The Custodian ({{custodian}}) holds Fund assets. The Auditor ({{auditor}}) audits the Fund's financial statements{{#IF isUmbrella}} for each sub-fund{{/IF}}; the Fund has no audit exemption.

## 10. CONFLICTS OF INTEREST

[Describe allocation between the Fund and other vehicles managed by the Manager, related-party transactions, and the conflicts policy.]

## 11. TAXATION

{{#IF hasTax}}
The Fund intends to apply for the section {{tax}} fund tax incentive, administered by MAS with the Inland Revenue Authority of Singapore, subject to the applicable assets-under-management and local business-spending conditions. Eligibility is not guaranteed and conditions are subject to change.
{{#ELSE}}
The Fund has not applied for a fund tax incentive. [State the default Singapore tax treatment of the Fund and, in general terms, investor-level considerations.]
{{/IF}}
Investors must obtain their own tax advice. Nothing here is tax advice.

## 12. AML/CFT, DATA AND REPORTING

The Fund's anti-money-laundering and counter-terrorism-financing obligations under MAS Notice VCC-N01 are performed by an eligible financial institution, in practice the Manager or the Administrator, which conducts customer due diligence, screening and monitoring. Personal data is handled under the Personal Data Protection Act 2012. Investors receive [periodic] reporting comprising [NAV statements, capital account statements and audited financial statements].

## 13. GENERAL

This Memorandum is governed by the laws of Singapore. The Constitution, the Subscription Agreement and any Side Letter, together with this Memorandum, record the terms of the investment; in the event of conflict, the Constitution prevails, followed by any Side Letter, then the Subscription Agreement, then this Memorandum.
