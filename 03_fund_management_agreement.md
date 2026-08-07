# FUND MANAGEMENT AGREEMENT
## {{fundName}}  ×  {{managerName}}

> BASE TEMPLATE — VCC Document Engine. Bespoke document. Original drafting for a Singapore VCC. Not legal advice.

**THIS FUND MANAGEMENT AGREEMENT** is made between:

(1) **{{fundName}}**, a variable capital company incorporated in Singapore (the "**Fund**"); and

(2) **{{managerName}}** (the "**Manager**").

## RECITALS

A. The Fund is a VCC and, under the Variable Capital Companies Act 2018, must appoint a permissible fund manager regulated by MAS.

B. The Manager {{#IF ownLicence}}holds, or has applied for, a Capital Markets Services licence for fund management{{#IF isHedge}}{{/IF}}{{#ELSE}}is hosted by, and acts under the Capital Markets Services licence of, a MAS-licensed fund manager{{/IF}}, and the Fund wishes to appoint it on these terms.

## 1. DEFINITIONS

Capitalised terms not defined here have the meanings in the Fund's Constitution. "Investment Guidelines" means the guidelines and restrictions in Schedule 1.

## 2. APPOINTMENT AND SCOPE

2.1 The Fund appoints the Manager to manage the assets of the Fund{{#IF isUmbrella}}, and of each sub-fund,{{/IF}} on a discretionary basis, and the Manager accepts the appointment.

2.2 The Manager has authority to acquire, hold, dispose of and otherwise deal with investments within the Investment Guidelines, to exercise rights attaching to investments, and to appoint and instruct brokers and counterparties.

2.3 The Manager pursues the Fund's {{strategy}} strategy across {{geography}} markets, consistent with the Offer Documents.

## 3. INVESTMENT GUIDELINES AND RESTRICTIONS

3.1 The Manager complies with the Investment Guidelines in Schedule 1, including any concentration and diversification limits.

{{#IF isHedge}}
3.2 The Manager may use leverage, short positions, derivatives and a prime broker within the limits in Schedule 1, and manages the associated counterparty and rehypothecation exposure.
{{#ELSE}}
3.2 The Manager may use leverage only to the limited extent permitted by Schedule 1.
{{/IF}}

## 4. REGULATORY COMPLIANCE

4.1 The Manager will manage the Fund in compliance with the VCC Act, the Securities and Futures Act 2001, the conditions of {{#IF ownLicence}}its CMS licence{{#ELSE}}the host manager's CMS licence{{/IF}}, and applicable MAS notices and guidelines, including AML/CFT obligations under Notice VCC-N01.

4.2 {{#IF isRetail}}Where the Fund is an authorised scheme, the Manager will comply with the Code on Collective Investment Schemes.{{#ELSE}}The Manager will ensure the offer is conducted within the exemptions relied upon.{{/IF}}

## 5. DELEGATION

5.1 The Manager may delegate or appoint sub-advisers, but remains responsible for the acts of its delegates and for oversight of them, and may not delegate in a way that conflicts with its regulatory obligations.

## 6. FEES AND EXPENSES

6.1 **Management fee.** The Fund pays the Manager {{mgmtFee}}, accruing and payable as set out in Schedule 2.

6.2 **Performance fee / carried interest.** The Manager is entitled to {{perfFee}}, subject to a hurdle of {{hurdle}}{{#IF isHedge}} and a high-water mark{{/IF}}, computed as set out in Schedule 2.

6.3 **Expenses.** [Allocate Fund expenses versus Manager expenses, including establishment, administration, custody, audit, legal and regulatory costs.]

## 7. REPORTING AND RECORDS

7.1 The Manager reports to the board of the Fund [periodically] on performance, portfolio, compliance and risk, and keeps proper books and records that the Fund and its auditor may inspect.

## 8. STANDARD OF CARE, EXCULPATION AND INDEMNITY

8.1 The Manager will act with the care, skill and diligence of a professional fund manager and in the best interests of the Fund.

8.2 The Manager is not liable for loss except to the extent caused by its fraud, wilful default, gross negligence or breach of this Agreement or of applicable law. The Fund indemnifies the Manager against other liabilities properly incurred in performing its duties. [Insert any liability cap.]

8.3 **Key person.** [Identify the key person(s); state the consequences of a key-person event, including any suspension of investment or investor rights.]

## 9. CONFLICTS OF INTEREST

9.1 The Manager will manage conflicts under its conflicts policy, will allocate opportunities fairly between the Fund and other vehicles it manages, and will disclose material conflicts to the board.

## 10. TERM AND TERMINATION

10.1 This Agreement continues until terminated on [notice] by either party, or immediately on insolvency, loss of regulatory status, or uncured material breach.

10.2 On termination the Manager will hand over records and cooperate in an orderly transition to a successor manager, and remains entitled to fees accrued to the termination date.

## 11. CONFIDENTIALITY, NOTICES AND GOVERNING LAW

11.1 Each party keeps the other's confidential information confidential, subject to legal and regulatory disclosure.

11.2 Notices are in writing to the parties' registered addresses.

11.3 This Agreement is governed by the laws of Singapore, and the parties submit to the [non-exclusive] jurisdiction of the Singapore courts.

---

## SCHEDULE 1 — INVESTMENT GUIDELINES AND RESTRICTIONS
- Objective; eligible asset classes for the {{strategy}} strategy; geographic scope ({{geography}})
- Concentration, diversification and leverage limits
- Prohibited investments; valuation policy reference

## SCHEDULE 2 — FEE COMPUTATION
- Management fee: basis, accrual and payment frequency ({{mgmtFee}})
- Performance fee / carried interest: {{perfFee}}; hurdle {{hurdle}}{{#IF isHedge}}; high-water mark mechanics{{/IF}}
- Worked example
