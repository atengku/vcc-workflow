# SUBSCRIPTION AGREEMENT
## {{fundName}}

> BASE TEMPLATE — VCC Document Engine. Bespoke document, structure anchored on the ILPA Model Subscription Agreement adapted for a Singapore VCC. Not legal advice.

**THIS SUBSCRIPTION AGREEMENT** is made between:

(1) **{{fundName}}**, a variable capital company incorporated in Singapore (the "**Fund**"), acting through {{managerName}} as its fund manager (the "**Manager**"); and

(2) the person who completes and signs the Application Form in Annex A (the "**Investor**").

## RECITALS

A. The Fund is offering participating shares on the terms of its Constitution and {{#IF isRetail}}its registered prospectus and Product Highlights Sheet{{#ELSE}}its Information Memorandum{{/IF}} (together, the "**Offer Documents**").

B. The Investor wishes to subscribe for shares and the Fund is willing to accept the subscription on these terms.

## 1. SUBSCRIPTION

1.1 The Investor irrevocably applies to subscribe for participating shares{{#IF isUmbrella}} of the sub-fund identified in the Application Form{{/IF}} for the subscription amount stated in the Application Form, at the issue price determined under the Constitution.

1.2 The application is irrevocable by the Investor but is not binding on the Fund until accepted in writing by or on behalf of the Manager. Subscription monies must be paid in cleared funds by the date stated in the Application Form.

1.3 The Fund may accept or reject any application in whole or in part in its discretion, and need give no reason. Applications not accepted by the long-stop date stated in the Application Form lapse, and subscription monies are returned without interest.

## 2. CONDITIONS TO SUBSCRIPTION

The Fund's acceptance is conditional on: (a) receipt of cleared subscription monies; (b) the Investor satisfying all eligibility, anti-money-laundering and know-your-customer requirements; and (c) the representations in clause 4 being true at acceptance.

## 3. ELIGIBILITY

{{#IF isRetail}}
3.1 The Investor confirms it has received the prospectus and Product Highlights Sheet and that an investment is suitable having regard to its circumstances. [Insert any retail suitability assessment requirements.]
{{#ELSE}}
3.1 The Investor represents that it is an accredited investor or an institutional investor within the meaning of the Securities and Futures Act 2001, or otherwise qualifies under the exemption in section 304 or 305 relied upon by the Fund, and completes the declaration in Annex B.

3.2 The Investor acknowledges that the Fund is offered in reliance on those exemptions, that the Offer Documents are not registered with MAS, and that the protections of a registered offer do not apply.
{{/IF}}

## 4. REPRESENTATIONS AND WARRANTIES OF THE INVESTOR

The Investor represents and warrants, as factual matters within its knowledge, that:

4.1 it has the power and authority to enter into and perform this Agreement, and the person signing is authorised to do so;

4.2 its subscription monies are not derived from unlawful activity and it is not subject to sanctions, nor acting for any sanctioned person;

4.3 it is acquiring the shares for its own account for investment and not with a view to distribution in breach of applicable law;

4.4 it has received, read and understood the Offer Documents, including the risk factors, and has taken its own legal, tax and financial advice or has decided not to;

4.5 it can bear the economic risk of the investment, including total loss; and

4.6 the information it provides in the Annexes is true, complete and not misleading, and it will notify the Fund promptly of any change.

## 5. ANTI-MONEY-LAUNDERING UNDERTAKINGS

The Investor will provide, on request, the documents and information the Fund or the Administrator ({{admin}}) requires to meet obligations under MAS Notice VCC-N01 and applicable AML/CFT law, and consents to screening and monitoring. The Fund may delay, refuse or compulsorily redeem where it considers necessary to comply.

## 6. ACKNOWLEDGEMENTS

The Investor acknowledges that: the Manager ({{managerName}}, {{manager}}) manages the Fund on a discretionary basis; fees of {{mgmtFee}} and {{perfFee}} (hurdle {{hurdle}}) apply; liquidity terms are {{lockup}}; and {{#IF isOpen}}shares are redeemable at NAV subject to the Constitution{{#ELSE}}the Fund is closed-ended and capital is returned on realisation or at term end{{/IF}}.

## 7. POWER OF ATTORNEY

The Investor appoints the Manager as its attorney to execute and do all documents and acts contemplated by the Constitution and this Agreement, including in connection with the maintenance of the register and regulatory filings.

## 8. INDEMNITY

The Investor indemnifies the Fund, the Manager and their delegates against loss arising from any breach of the Investor's representations, warranties or undertakings, or from any inaccuracy in the information it provides.

## 9. DATA PROTECTION

The Investor consents to the collection, use and disclosure of its personal data by the Fund, the Manager and the Administrator for administration, compliance and reporting, in accordance with the Personal Data Protection Act 2012.

## 10. TRANSFER, NOTICES AND GOVERNING LAW

10.1 Shares may be transferred only with Manager consent and subject to the Constitution and applicable law.

10.2 Notices are given in writing to the addresses in the Application Form.

10.3 This Agreement is governed by the laws of Singapore, and the parties submit to the [non-exclusive] jurisdiction of the Singapore courts {{#IF isAI}}[or to arbitration in Singapore, if elected]{{/IF}}.

10.4 This Agreement may be executed in counterparts, including electronically.

---

## ANNEX A — APPLICATION FORM
- Investor legal name; type (individual / corporate / trust / fund); jurisdiction
- {{#IF isUmbrella}}Sub-fund and share class subscribed for{{#ELSE}}Share class subscribed for{{/IF}}
- Subscription amount; settlement date; long-stop acceptance date
- Bank account details for redemptions and distributions
- Authorised signatory; contact and notice details

## ANNEX B — {{#IF isRetail}}SUITABILITY ASSESSMENT{{#ELSE}}ACCREDITED / INSTITUTIONAL INVESTOR DECLARATION{{/IF}}
{{#IF isRetail}}
- Knowledge and experience; financial situation; investment objectives
- Acknowledgement of risk; signature
{{#ELSE}}
- Declaration of accredited investor status against the SFA financial thresholds [net personal assets / income / financial assets], or institutional investor status
- Where applicable, opt-in / opt-out of accredited investor treatment
- Supporting evidence; signature and date
{{/IF}}

## ANNEX C — KNOW-YOUR-CUSTOMER PACK
- Identity and verification documents; beneficial ownership; source of funds and wealth
- Tax residency / self-certification (CRS / FATCA, as applicable)
- Sanctions and PEP self-declaration
