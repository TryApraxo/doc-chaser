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
- Estate, gift and foreign reporting
- Information returns and business credits
- IRS collection and relief
- Nonprofit exemption and retirement plan correction
- Condo project review and closing
- Employment discrimination
- Health coverage, student aid and VA benefits
- Disaster and flood claims
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
| `mortgage-fha-203k.json` | Use when an FHA loan will also pay for repairs or renovation under Section 203(k); add this list to mortgage-fha, which still covers the borrower's identity, income and assets. | 29 | Sourced |
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
| `legal-immigration-i751-remove-conditions.json` | Use when a conditional permanent resident who got status through marriage is filing Form I-751, jointly or with a waiver of the joint filing requirement; use the I-485 family list for the original green card application. | 22 | Sourced |
| `legal-immigration-i765-work-permit.json` | Use when the client is applying for an initial, renewal or replacement Employment Authorization Document on Form I-765 under (c)(9), (c)(8), (a)(12)/(c)(19), (c)(33), (c)(3) or (c)(26); use the I-485 family list for the green card application itself. | 25 | Sourced |
| `legal-immigration-i864-affidavit-support.json` | Use when a petitioning, joint or substitute sponsor must complete Form I-864 for a family-based (or certain employment-based) immigrant; use the I-485 family or I-130 lists for the immigrant's own application. | 27 | Sourced |
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

## Estate, gift and foreign reporting

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `tax-706-estate.json` | Use when the firm is preparing Form 706 for a decedent who died after December 31, 2025, whether the return is required or filed only to elect portability. | 23 | Sourced |
| `tax-fbar-foreign-accounts.json` | Use when a U.S. client has foreign bank, securities or other financial accounts or assets to report on FinCEN Form 114 and/or Form 8938; use tax-firpta-8288b when a foreign person is selling U.S. real estate. | 18 | Sourced |
| `tax-firpta-8288b.json` | Use when a foreign person selling a U.S. real property interest applies on Form 8288-B to reduce or eliminate FIRPTA withholding, and the sale is reported on Forms 8288 and 8288-A; use tax-fbar-foreign-accounts for a U.S. person's foreign bank and financial accounts. | 23 | Sourced |

## Information returns and business credits

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `tax-1099-filing-season.json` | Use when the firm prepares a business client's Forms 1099-NEC and 1099-MISC for payments made in 2026; use payroll-new-contractor when collecting paperwork from one new contractor at the start of an engagement. | 17 | Sourced |
| `tax-rd-credit-6765.json` | Use when the firm is claiming the credit for increasing research activities on Form 6765, on an original return or on an amended return or AAR claiming a refund. | 22 | Sourced |

## IRS collection and relief

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `tax-irs-collection-433a.json` | Use when an individual wage earner or sole proprietor who owes the IRS must complete the full Form 433-A collection information statement; use the Form 433-F list when the IRS asked for the shorter 433-F, the Form 433-B list for a corporation, partnership or LLC, and the offer in compromise list for Form 433-A (OIC). | 40 | Sourced |
| `tax-irs-collection-433b.json` | Use when a corporation, partnership or LLC that owes the IRS must complete Form 433-B; use the Form 433-A list for an individual or sole proprietor, and the offer in compromise list for Form 433-B (OIC). | 29 | Sourced |
| `tax-irs-collection-433f.json` | Use when the IRS has asked an individual wage earner or self-employed person for the shorter Form 433-F, often with an installment agreement request; use the Form 433-A list when the full 433-A is required and the Form 433-B list for a corporation, partnership or LLC. | 25 | Sourced |
| `tax-irs-offer-in-compromise.json` | Use when a client wants to settle an IRS tax debt for less than the full amount through an offer in compromise (Form 656, or Form 656-L for doubt as to liability); use the Form 433-A, 433-B or 433-F lists when the IRS only wants a collection information statement. | 26 | Sourced |
| `tax-irs-innocent-spouse-8857.json` | Use when a client wants relief from tax on a joint return (or community income) that they believe only their spouse or former spouse should owe; injured spouse refund claims use Form 8379 instead. | 26 | Sourced |

## Nonprofit exemption and retirement plan correction

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `nonprofit-1023-exemption.json` | Use when an organization is applying for recognition of 501(c)(3) tax-exempt status on the full Form 1023. | 29 | Sourced |
| `retirement-plan-vcp-submission.json` | Use when a plan sponsor is filing a Voluntary Correction Program (VCP) submission with the IRS on Form 8950 to correct a retirement plan failure. | 23 | Sourced |

## Condo project review and closing

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `mortgage-condo-project.json` | Use when a conventional loan is secured by a unit in a condominium project and the project needs review: these items are collected from the HOA or its management company, alongside the borrower's own needs list (for example mortgage-conventional-salaried). | 28 | Sourced |
| `mortgage-closing-buyer.json` | Use when a homebuyer with an approved mortgage is getting ready for the closing table; use the program needs list (for example mortgage-fha or mortgage-conventional-salaried) for the documents the lender underwrites with. | 21 | Sourced |

## Employment discrimination

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `legal-eeoc-charge.json` | Use when a private-sector, state or local government, union or staffing-agency worker or applicant is preparing an EEOC inquiry, intake interview and charge of employment discrimination; federal employees and applicants follow a different complaint process. | 21 | Sourced |

## Health coverage, student aid and VA benefits

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `benefits-aca-marketplace-verification.json` | Use when a client's HealthCare.gov Marketplace notice asks for documents to resolve a data matching issue (inconsistency) on their application. | 19 | Sourced |
| `benefits-fafsa-verification.json` | Use when a student's 2026–27 FAFSA form has been selected for verification (group V1, V4 or V5) and the family needs to gather what the school's financial aid office asks for. | 16 | Sourced |
| `benefits-va-disability-compensation.json` | Use when a Veteran or service member is filing a VA disability compensation claim (new, increased, secondary, supplemental or presumptive); use benefits-va-pension for needs-based pension and benefits-va-survivors-dic for survivors. | 25 | Sourced |
| `benefits-va-pension.json` | Use when a wartime Veteran is applying for the needs-based VA Veterans Pension (with or without Aid and Attendance or Housebound); use benefits-va-disability-compensation for service-connected compensation and benefits-va-survivors-dic for survivors. | 18 | Sourced |
| `benefits-va-survivors-dic.json` | Use when a surviving spouse, child, or parent of a Veteran or service member is claiming Dependency and Indemnity Compensation, Survivors Pension, or accrued benefits; use benefits-va-pension or benefits-va-disability-compensation for a living Veteran's own claim. | 16 | Sourced |

## Disaster and flood claims

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `disaster-fema-individual-assistance.json` | Use when a household is applying to FEMA for Individual Assistance after a declared disaster, or must prove occupancy or ownership afterward; for SBA disaster home loans also use sba-disaster-loan-home, and for an NFIP flood claim use insurance-nfip-flood-claim. | 10 | Sourced |
| `insurance-nfip-flood-claim.json` | Use when a client with a National Flood Insurance Program (NFIP) policy is filing a flood claim; for FEMA disaster grants use disaster-fema-individual-assistance, and for SBA disaster home loans use sba-disaster-loan-home. | 17 | Sourced |

## General intake

| Template file | Use when | Items | Basis |
|---|---|---|---|
| `agency-onboarding.json` | New marketing, design or web client. Common-practice items. | 14 | Mixed |
| `legal-intake-general.json` | Opening any new legal matter: identity, conflict check and engagement. Common-practice items. | 14 | Mixed |

## Combining variants

- A client can need two variants at once (self-employed and a landlord; a salaried borrower with rental income). Build from both and merge items that ask for the same document.
- The `mortgage-other-income-sources` file is an add-on to a salaried or self-employed mortgage list, not a list on its own.
- Add-on lists: `mortgage-fha-203k` adds to `mortgage-fha`; `mortgage-condo-project` is collected from the HOA alongside the borrower's needs list; `mortgage-closing-buyer` follows the needs list; `tax-irs-offer-in-compromise` usually needs the Form 433-A or 433-B list too.
- The credit-proof files are for backing up a claim (often after an IRS letter); they add to an individual return list and do not replace it.
