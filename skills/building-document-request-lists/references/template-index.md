# Template index

Every file in `assets/checklists/`, grouped by purpose. Templates in one group are variants: same job, different client condition. Pick by the "use when" line. "Sourced" means every item cites an official source named in the file; "Mixed" means some items are common practice and are labelled so.

## Contents

- Individual tax returns
- ITIN applications
- Proof for credits and filing status (IRS audit-letter lists)
- Business records and bookkeeping
- Payroll onboarding
- Mortgage needs lists
- Mortgage hardship
- SBA loans and business banking
- Immigration
- Bankruptcy
- Social Security disability
- General intake

## Individual tax returns

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `tax-1040-free-prep-basic.json` | Pick this for a simple wage-earner return with no business or rental income, where the short IRS free tax preparation (VITA) list is enough. | 22 | Sourced |
| `tax-1040-rental-property.json` | Pick this when the client owns residential rental real estate reported on Schedule E; add the basic individual list for personal items. | 18 | Sourced |
| `tax-1040-self-employed.json` | Pick this when the client is a sole proprietor, freelancer or gig worker who reports business income on Schedule C; add the basic individual list for personal items. | 25 | Sourced |
| `tax-individual-1040.json` | General individual return covering most situations through tags; the default when no narrower variant fits. | 33 | Mixed |

## ITIN applications

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `tax-itin-w7.json` | Pick this when someone on the return needs a new ITIN or must renew an expired one with Form W-7. | 23 | Sourced |

## Proof for credits and filing status (IRS audit-letter lists)

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `tax-credit-proof-dependents-hoh.json` | Pick this when the client must back up a claimed dependent or head of household filing status. | 20 | Sourced |
| `tax-credit-proof-education.json` | Pick this when the client is claiming or must back up an education credit for a student. | 12 | Sourced |
| `tax-credit-proof-eitc-child.json` | Pick this when the client must show that a child claimed for the Earned Income Credit lived with them, is related to them and meets the age test. | 14 | Sourced |

## Business records and bookkeeping

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `bookkeeping-onboarding.json` | New bookkeeping client: access, accounts and prior books. Common-practice items. | 18 | Mixed |
| `bookkeeping-records-small-business.json` | Use for collecting the federal tax records of a small business, whether or not it has employees; the employee, inventory, asset, travel and corporation items are switched on by tags. | 41 | Sourced |
| `tax-business-new-client-records.json` | Pick this short list when taking on a small business and you want its books and supporting records by category; use bookkeeping-records-small-business for the itemized version with the full employment tax record list. | 13 | Sourced |

## Payroll onboarding

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `payroll-employer-setup.json` | Use when a payroll provider or reporting agent is taking on a new employer client; use the new-hire and contractor lists for individual workers. | 18 | Sourced |
| `payroll-new-contractor.json` | Use when a business starts paying a worker it has already determined is an independent contractor; use the new-hire list for employees. | 8 | Sourced |
| `payroll-new-hire-employee.json` | Use when a business is adding a new employee (paid on Form W-2) to payroll; use the contractor list for independent contractors and the employer setup list for a new employer client. | 32 | Sourced |

## Mortgage needs lists

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `mortgage-conventional-rental-income.json` | Pick this, alongside the borrower's main income variant, for a conventional loan to be sold to Fannie Mae when rental income from the subject property or another property is used to qualify. | 17 | Sourced |
| `mortgage-conventional-salaried.json` | Pick this for a conventional loan to be sold to Fannie Mae when the borrower qualifies on W-2 employment income, instead of the self-employed, rental-income or other-income variants. | 26 | Sourced |
| `mortgage-conventional-self-employed.json` | Pick this for a conventional loan to be sold to Fannie Mae when the borrower owns 25% or more of a business and qualifies on that income, or receives Schedule K-1 income from a smaller ownership share. | 12 | Sourced |
| `mortgage-fha.json` | Pick this for an FHA-insured forward mortgage instead of the conventional variants. | 34 | Sourced |
| `mortgage-other-income-sources.json` | Pick this, alongside the borrower's main income variant, for a conventional loan to be sold to Fannie Mae when income such as support payments, Social Security, retirement, disability, trust or investment income is used to qualify. | 31 | Sourced |
| `mortgage-purchase.json` | Home purchase when the loan program is not yet known; the consumer-level core from the CFPB. | 16 | Mixed |
| `mortgage-refinance.json` | Refinance when the loan program is not yet known. | 15 | Mixed |
| `mortgage-va-purchase.json` | Pick this for a VA-backed purchase loan to collect what the borrower needs for the Certificate of Eligibility, alongside a general purchase list for income and assets. | 14 | Sourced |

## Mortgage hardship

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `mortgage-hardship-assistance.json` | Pick this when a borrower with payment difficulties is applying to the servicer for mortgage assistance (loss mitigation) on a loan owned by Fannie Mae or Freddie Mac. | 17 | Sourced |

## SBA loans and business banking

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `business-bank-account-opening.json` | Use when a client is opening a business bank account and needs to gather the documents banks commonly ask for. | 4 | Sourced |
| `sba-7a-loan-application.json` | Use when a business is applying for an SBA 7(a) loan through a participating lender; use the disaster loan lists for SBA disaster loans. | 16 | Sourced |
| `sba-disaster-loan-business.json` | Use when a business or private nonprofit is applying for an SBA disaster loan (physical damage, economic injury or Military Reservist EIDL) on SBA Form 5; use the home list for homeowners and renters. | 17 | Sourced |
| `sba-disaster-loan-home.json` | Use when a homeowner or renter is applying for an SBA disaster loan for a home or personal property on SBA Form 5C; use the business list for businesses and nonprofits. | 13 | Sourced |

## Immigration

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `legal-immigration-i130-parent-child.json` | The client is petitioning on Form I-130 for a child, parent, brother or sister rather than a spouse. | 23 | Sourced |
| `legal-immigration-i130-spouse.json` | The client is a U.S. citizen or lawful permanent resident petitioning for a husband or wife on Form I-130. | 16 | Sourced |
| `legal-immigration-i485-family.json` | The client is in the United States applying to adjust status on Form I-485 as an immediate relative or family preference immigrant. | 20 | Sourced |
| `legal-immigration-n400-naturalization.json` | The client is a lawful permanent resident applying for U.S. citizenship on Form N-400. | 23 | Sourced |

## Bankruptcy

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `legal-bankruptcy-chapter13.json` | The client is an individual with regular income filing a chapter 13 (repayment plan) case. | 19 | Sourced |
| `legal-bankruptcy-chapter7.json` | The client is an individual filing a chapter 7 (liquidation) case. | 17 | Sourced |

## Social Security disability

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `legal-ssa-disability-adult.json` | The client is an adult applying for Social Security disability benefits. | 22 | Sourced |
| `legal-ssa-disability-child.json` | The client is a parent or guardian applying for Supplemental Security Income (SSI) disability payments for a child under age 18. | 14 | Sourced |

## General intake

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `agency-onboarding.json` | New marketing, design or web client. Common-practice items. | 14 | Mixed |
| `legal-intake-general.json` | Opening any new legal matter: identity, conflict check and engagement. Common-practice items. | 14 | Mixed |

## Combining variants

- A client can need two variants at once (self-employed and a landlord; a salaried borrower with rental income). Build from both and merge items that ask for the same document.
- The `mortgage-other-income-sources` file is an add-on to a salaried or self-employed mortgage list, not a list on its own.
- The credit-proof files are for backing up a claim (often after an IRS letter); they add to an individual return list and do not replace it.
