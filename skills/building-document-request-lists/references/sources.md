# Where the checklist items come from

Each item in `assets/checklists/*.json` has a `basis` field. This file says what each basis means and how far to trust it. Read it when a user asks where an item comes from or whether a list is complete.

| Basis | Source | Used in | What it covers |
|---|---|---|---|
| `irs` | IRS, "Gather your documents" (https://www.irs.gov/filing/gather-your-documents) | `tax-individual-1040` | Identity details, information returns (W-2, 1099 series, SSA-1099, 1095-A), deduction and credit records, self-employment records |
| `cfpb` | CFPB, "Create a loan application packet" (https://www.consumerfinance.gov/owning-a-home/prepare/create-a-loan-application-packet/) | `mortgage-purchase`, `mortgage-refinance` | Pay stubs (30 days), W-2s and signed federal returns (two years), two most recent bank statements, down payment source with two months' history, ID, Social Security number, name change documents, VA certificate of eligibility, counseling certificate |
| `fnma` | Fannie Mae Selling Guide B3-4.3-04, Personal Gifts (https://selling-guide.fanniemae.com/sel/b3-4.3-04/personal-gifts) | `mortgage-purchase` | Gift letter contents and acceptable evidence that the gift funds were transferred |
| `practice` | Common practice among small firms | All templates | Items with no single official source, such as engagement letters, software access and conflict-check details |

## Sources by template (added in 0.5.0)

Every item in these templates cites one of the sources listed in its own file, each with the date it was read. The table gives the publisher; open the file for the exact documents and URLs.

| Template | Publisher and documents |
|---|---|
| `bookkeeping-records-small-business` | IRS Publication 583, Starting a Business and Keeping Records (Rev. December 2024); IRS, Employment tax recordkeeping (page last reviewed or updated 12-Jun-2026); IRS, What kind of records should I keep (page last reviewed or updated 03-Aug-2026) |
| `business-bank-account-opening` | SBA, Launch your business: Open a business bank account (web page; no review date shown) |
| `legal-bankruptcy-chapter13` | 11 U.S.C. 1308, Filing of prepetition tax returns (Cornell Legal Information Institute); 11 U.S.C. 521, Debtor's duties (Cornell Legal Information Institute); Federal Rules of Bankruptcy Procedure, Rule 4002, Debtor's Duties, as amended effective Dec. 1, 2024 (Cornell Legal Information Institute); U.S. Department of Justice, U.S. Trustee Program, Section 341 Meeting of Creditors; U.S. Trustee Program, Acceptable Photo Identification and Social Security Number Documents, 08/25/2023; United States Courts, Bankruptcy Basics: Chapter 13 |
| `legal-bankruptcy-chapter7` | 11 U.S.C. 521, Debtor's duties (Cornell Legal Information Institute); Federal Rules of Bankruptcy Procedure, Rule 4002, Debtor's Duties, as amended effective Dec. 1, 2024 (Cornell Legal Information Institute); U.S. Department of Justice, U.S. Trustee Program, Section 341 Meeting of Creditors; U.S. Trustee Program, Acceptable Photo Identification and Social Security Number Documents, 08/25/2023; United States Courts, Bankruptcy Basics: Chapter 7 |
| `legal-immigration-i130-parent-child` | USCIS, Instructions for Form I-130, Petition for Alien Relative, and Form I-130A, edition 04/01/24 |
| `legal-immigration-i130-spouse` | USCIS, Instructions for Form I-130, Petition for Alien Relative, and Form I-130A, edition 04/01/24 |
| `legal-immigration-i485-family` | USCIS, Checklist of Required Initial Evidence for Form I-485 (for informational purposes only), immediate relatives and family-based preference section, last reviewed/updated 07/08/2025; USCIS, Instructions for Form I-485, Application to Register Permanent Residence or Adjust Status, edition 09/18/26 |
| `legal-immigration-n400-naturalization` | USCIS, Form M-477, Document Checklist (for Form N-400), Rev. 11/21/2016 |
| `legal-ssa-disability-adult` | Social Security Administration, Adult Disability Starter Kit, Publication No. 64-110, June 2024; Social Security Administration, Checklist for Online Adult Disability Application, Publication No. 05-10519, July 2026 |
| `legal-ssa-disability-child` | Social Security Administration, Child Disability Starter Kit, Publication No. 64-112 (formerly SSA-1171), August 2024 |
| `mortgage-conventional-rental-income` | Fannie Mae Selling Guide B3-3.8-01, General Rental Income Information (09/02/2026); Fannie Mae Selling Guide B3-3.8-02, Rental Income from the Subject Property (09/02/2026); Fannie Mae Selling Guide B3-3.8-03, Rental Income from the Subject Property: Short-Term Rental (09/02/2026); Fannie Mae Selling Guide B3-3.8-04, Rental Income from Non-Subject Property (09/02/2026); Fannie Mae Selling Guide B3-3.8-05, Rental Income from Non-Subject Property: Departing Residence (09/02/2026) |
| `mortgage-conventional-salaried` | Fannie Mae Selling Guide B1-1-03, Allowable Age of Credit Documents and Federal Income Tax Returns (04/02/2025); Fannie Mae Selling Guide B3-3.1-02, Tax Return and Transcript Documentation Requirements (06/03/2026); Fannie Mae Selling Guide B3-3.2-01, Standards for Employment and Income Documentation (03/04/2026); Fannie Mae Selling Guide B3-3.2-02, Standards for Employment-Related Income (03/04/2026); Fannie Mae Selling Guide B3-3.3-01, Base Income (03/04/2026); Fannie Mae Selling Guide B3-3.3-02, Bonus, Commission, Overtime, and Tip Income (03/04/2026); Fannie Mae Selling Guide B3-3.3-03, Employment Offers or Contracts (10/07/2026); Fannie Mae Selling Guide B3-3.3-05, Military Income (03/04/2026); Fannie Mae Selling Guide B3-3.3-08, Seasonal Income (03/04/2026); Fannie Mae Selling Guide B3-3.3-09, Temporary Leave Income (03/04/2026); Fannie Mae Selling Guide B3-3.4-17, Unemployment Benefits Income (03/04/2026); Fannie Mae Selling Guide B3-4.2-01, Verification of Deposits and Assets (05/04/2022); Fannie Mae Selling Guide B3-4.2-02, Depository Accounts (12/14/2022); Fannie Mae Selling Guide B3-4.3-09, Earnest Money Deposit (05/04/2022) |
| `mortgage-conventional-self-employed` | Fannie Mae Selling Guide B1-1-03, Allowable Age of Credit Documents and Federal Income Tax Returns (04/02/2025); Fannie Mae Selling Guide B3-3.1-02, Tax Return and Transcript Documentation Requirements (06/03/2026); Fannie Mae Selling Guide B3-3.4-19, Schedule K-1 Income <25% Ownership (10/07/2026); Fannie Mae Selling Guide B3-3.5-01, Underwriting Factors and Documentation for a Self-Employed Borrower (12/13/2023); Fannie Mae Selling Guide B3-3.7-04, Analyzing Profit and Loss Statements (04/01/2009); Fannie Mae Selling Guide B3-4.2-02, Depository Accounts (12/14/2022) |
| `mortgage-fha` | HUD, FHA Single Family Housing Policy Handbook 4000.1, issued August 12, 2026 (sections II.A.1 Origination/Processing and II.A.4 Underwriting the Borrower Using the TOTAL Mortgage Scorecard) |
| `mortgage-hardship-assistance` | Fannie Mae Servicing Guide D2-2-05, Receiving a Borrower Response Package (06/09/2021); Fannie Mae/Freddie Mac Form 710, Mortgage Assistance Application (effective 12.11.24), copy published with the Freddie Mac Single-Family Seller/Servicer Guide |
| `mortgage-other-income-sources` | Fannie Mae Selling Guide B3-3.1-01, General Income Information (10/07/2026); Fannie Mae Selling Guide B3-3.4-02, Alimony, Child Support, Equalization Payments, or Separate Maintenance (10/07/2026); Fannie Mae Selling Guide B3-3.4-03, Annuity, Pension, or Retirement Income (10/07/2026); Fannie Mae Selling Guide B3-3.4-04, Boarder Income (03/04/2026); Fannie Mae Selling Guide B3-3.4-05, Capital Gains Income (03/04/2026); Fannie Mae Selling Guide B3-3.4-07, Foster-Care Income (03/04/2026); Fannie Mae Selling Guide B3-3.4-08, Interest and Dividend Income (03/04/2026); Fannie Mae Selling Guide B3-3.4-09, Long-term Disability Income (03/04/2026); Fannie Mae Selling Guide B3-3.4-11, Notes Receivable Income (10/07/2026); Fannie Mae Selling Guide B3-3.4-12, Public Assistance Income (10/07/2026); Fannie Mae Selling Guide B3-3.4-13, Royalty Payment Income (10/07/2026); Fannie Mae Selling Guide B3-3.4-15, Social Security Income (10/07/2026); Fannie Mae Selling Guide B3-3.4-16, Trust Income (10/07/2026); Fannie Mae Selling Guide B3-3.4-17, Unemployment Benefits Income (03/04/2026); Fannie Mae Selling Guide B3-3.4-18, VA Benefits Income (10/07/2026) |
| `mortgage-va-purchase` | U.S. Department of Veterans Affairs, Home loans for surviving spouses (last updated September 22, 2026); U.S. Department of Veterans Affairs, How to request a VA home loan Certificate of Eligibility (COE) (last updated September 22, 2026) |
| `payroll-employer-setup` | IRS Form 8655, Reporting Agent Authorization (Rev. January 2024); IRS, Depositing and reporting employment taxes (page last reviewed or updated 29-Jun-2026); IRS, EFTPS: The Electronic Federal Tax Payment System (page last reviewed or updated 10-Nov-2026); IRS, Employment tax recordkeeping (page last reviewed or updated 12-Jun-2026); IRS, Get an employer identification number (page last reviewed or updated 16-Oct-2026) |
| `payroll-new-contractor` | IRS Form W-9, Request for Taxpayer Identification Number and Certification (Rev. March 2024); IRS Instructions for the Requester of Form W-9 (Rev. March 2024); IRS, Forms and associated taxes for independent contractors (page last reviewed or updated 11-Sep-2026); IRS, Reporting payments to independent contractors (page last reviewed or updated 22-May-2026) |
| `payroll-new-hire-employee` | IRS, Hiring employees (page last reviewed or updated 18-Feb-2026); USCIS Form I-9, Employment Eligibility Verification, including Lists of Acceptable Documents (Edition 01/20/25, expires 05/31/2027); USCIS, Form I-9 Acceptable Documents (I-9 Central web page; no review date captured) |
| `sba-7a-loan-application` | 13 CFR 120.191, The contents of a business loan application (Cornell LII; same text confirmed on ecfr.gov); SBA Form 1919, SBA 7(a) Borrower Information Form (02/2025; OMB expiration date 6/30/2027); SBA Form 413, Personal Financial Statement (05-24; OMB expiration date 08/31/2027) |
| `sba-disaster-loan-business` | SBA Form 5, Disaster Business Loan Application (05/23; OMB expiration date shown 07/31/26) |
| `sba-disaster-loan-home` | SBA Form 5C, Disaster Home Loan Application (05/23; OMB expiration date shown 07/31/26) |
| `tax-1040-free-prep-basic` | IRS, Checklist for free tax return preparation (web page, last reviewed or updated 24-Oct-2026); IRS, Form 13614-C, Intake/Interview and Quality Review Sheet (Rev. 10-2026) |
| `tax-1040-rental-property` | IRS, Publication 463 (2025), Travel, Gift, and Car Expenses, chapter 5 and Table 5-1; IRS, Publication 527 (2025), Residential Rental Property; IRS, Tips on rental real estate income, deductions and recordkeeping (web page, last reviewed or updated 04-Apr-2026); IRS, Topic no. 414, Rental income and expenses (web page, last reviewed or updated 09-Nov-2026) |
| `tax-1040-self-employed` | IRS, Manage taxes for your gig work (web page, last reviewed or updated 28-Jun-2026); IRS, Publication 463 (2025), Travel, Gift, and Car Expenses, chapter 5 and Table 5-1; IRS, Publication 583, Starting a Business and Keeping Records (Revised December 2024); IRS, Publication 587 (2025), Business Use of Your Home; IRS, What kind of records should I keep (web page, last reviewed or updated 03-Aug-2026) |
| `tax-business-new-client-records` | IRS, Publication 583, Starting a Business and Keeping Records (Revised December 2024) |
| `tax-credit-proof-dependents-hoh` | IRS, Form 886-H-DEP, Supporting Documents for Dependents (Rev. 10-2022); IRS, Form 886-H-HOH, Supporting Documents to Prove Head of Household Filing Status (Rev. 10-2019) |
| `tax-credit-proof-education` | IRS, Education credits: AOTC and LLC (web page, last reviewed or updated 12-Aug-2026); IRS, Form 886-H-AOC, Supporting Documents to Prove American Opportunity Credit (Rev. 5-2017) |
| `tax-credit-proof-eitc-child` | IRS, Form 886-H-EIC, Documents You Need to Send to Claim the Earned Income Credit on the Basis of a Qualifying Child or Children (Rev. 10-2022) |
| `tax-itin-w7` | IRS, ITIN supporting documents (web page, last reviewed or updated 28-Oct-2026); IRS, Instructions for Form W-7 (Revised 12/2024) |

## Limits

- **Official sources are written for consumers.** They list what a typical filer or borrower gathers. A professional's engagement often needs more.
- **`practice` items are a starting point.** No regulator publishes them. The firm should edit them to match its own process.
- **Sources change.** The IRS and CFPB pages are updated without notice, and Fannie Mae revises the Selling Guide several times a year. Before relying on a specific requirement, open the source link and check it.
- **Fannie Mae rules apply to loans sold to Fannie Mae.** FHA, VA, USDA, Freddie Mac and portfolio loans have their own gift and documentation rules.
- **Agency forms go out of date.** Several templates follow a named edition of a form or guide (for example USCIS M-477 Rev. 11/21/2016, the IRS Form 886-H series, SBA Forms 5 and 5C). The edition is in each file's `note`. Check the agency's current edition before filing.
- **Program lists cover what the source lists.** The VA template covers Certificate of Eligibility evidence only; the FHA template covers the TOTAL Scorecard sections read, not manual underwriting; the SBA 7(a) template is the regulation's minimum, and lenders ask for more.
- **No state or provincial items.** State tax returns, state bar rules and Canadian requirements are not covered.

## Template file format

Add a template by placing a JSON file in `assets/checklists/`:

```json
{
  "id": "file-name-without-extension",
  "title": "Heading shown on the list",
  "industry": "tax | mortgage | legal | agency | bookkeeping | payroll | lending",
  "variant_of": "group id shared by sibling variants",
  "use_when": "When to pick this variant instead of its siblings",
  "jurisdiction": "US federal",
  "note": "One or two sentences printed under the list.",
  "sources": {"key": {"name": "Agency, document, edition", "url": "https://...", "retrieved": "YYYY-MM-DD"}},
  "situations": {"tag": "Plain-language question the tag answers"},
  "sections": [
    {"name": "Section heading", "items": [
      {"id": "unique-id", "label": "What to ask for", "detail": "Optional clarification",
       "when": ["tag"], "basis": "practice"}
    ]}
  ]
}
```

After adding a file, add its row to `references/template-index.md`.

An item with an empty `when` list is always included. An item with several tags is included when any one of them applies.
