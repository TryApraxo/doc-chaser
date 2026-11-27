# Template backlog (proposed, not built)

170 candidate templates that the current library (37 request lists, 11 letters and plans) does not cover. Each row names where the market already ships it (the demand signal) and the authority that would back its item list. Nothing here is built yet; this is the list to approve before writing JSON.

Research date: 2026-11-26. Method: public template libraries (Content Snare, TaxDome, Karbon, Financial Cents, Liscio, Canopy, AICPA, Harvey, Clio, MyCase, Docketwise, HoneyBook, Jotform, Moxo, Oregon State Bar PLF) and official government, GSE and standards pages.

## How to read this

**Tier.** This tells you how strongly an official source backs the template. It decides the order to build in and whether the file can be labelled "Sourced" under the repo's rule.

| Tier | Meaning | Count |
|---|---|---|
| **A** | An official source publishes an itemized document list or checklist. Can be built as **Sourced**. | 67 |
| **B** | Official rules or form instructions define what is needed, but there is no ready list; we derive one from the form. Build as **Sourced**, with more care. | 62 |
| **C** | Market-normal (several vendors ship it), but no official list exists. Build as **Mixed** or common practice, labelled as such. | 41 |

**Demand signal codes:**

| Code | Source |
|---|---|
| CS | Content Snare form-templates library (contentsnare.com/form-templates/…) |
| TD | TaxDome |
| KB | Karbon template library |
| FC | Financial Cents template library |
| AK | AICPA Annual Tax Compliance Kit and organizers |
| LIS | Liscio Smart Requests |
| CAN | Canopy |
| SV | SmartVault |
| JW | Jetpack Workflow |
| HV | Harvey workflows / Agent Builder |
| CL | Clio |
| MC | MyCase |
| LM | Lawmatics |
| SB | Smokeball |
| DW | Docketwise |
| OR | Oregon State Bar PLF practice forms |
| HB | HoneyBook |
| JF | Jotform |
| MX | Moxo |
| PF | Paperform |
| CU | ClickUp |
| — | No vendor template found; the official checklist is the reason to build it |

**Verification status.** The research agents loaded about a third of the authority URLs. The others come from search results, or follow standard form-page patterns (`irs.gov/forms-pubs/about-form-X`, `uscis.gov/<form>`). Every source must be loaded and its edition recorded when the template is built, as the repo already requires.

---

## 1. Tax: entity, fiduciary and specialty returns (13)

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 1 | `tax-1065-partnership.json` | Partnership or multi-member LLC return | AK, KB, TD, CS | Instructions for Form 1065 | B |
| 2 | `tax-1120s-s-corp.json` | S corporation return; shareholder basis and distributions | AK, KB, FC, CS | Instructions for Form 1120-S; Form 7203 | B |
| 3 | `tax-1120-c-corp.json` | C corporation return | AK, KB, JW, CS | Instructions for Form 1120 | B |
| 4 | `tax-990-nonprofit.json` | Exempt organization annual return | AK, KB, FC | Instructions for Form 990 and schedules | B |
| 5 | `tax-990-ez.json` | Smaller exempt organization | AK | Instructions for Form 990-EZ | B |
| 6 | `tax-990-pf-private-foundation.json` | Private foundation | AK | Instructions for Form 990-PF | B |
| 7 | `tax-990-t-ubti.json` | Unrelated business income | AK | Instructions for Form 990-T | B |
| 8 | `tax-1041-estate-trust.json` | Fiduciary income tax return | AK, KB, FC | Instructions for Form 1041 | B |
| 9 | `tax-706-estate.json` | Federal estate tax return | AK, KB | Instructions for Form 706 (schedule-by-schedule attachments); Form 8971 | A |
| 10 | `tax-709-gift.json` | Gift tax return | AK, KB | Instructions for Form 709 | B |
| 11 | `tax-1040nr-nonresident.json` | Foreign national / nonresident alien | AK | Instructions for Form 1040-NR; Pub 519 | B |
| 12 | `tax-5500-benefit-plan.json` | Employee benefit plan annual report | AK, KB | DOL EBSA Form 5500 instructions | B |
| 13 | `tax-new-entity-first-return.json` | First return of a new business; elections | AK | Instructions for SS-4, 2553, 8832; IRC §195 | B |

## 2. Tax: compliance cycles and special situations (12)

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 14 | `tax-1099-filing-season.json` | Year-end vendor 1099 preparation | KB, FC, LIS | General Instructions for Certain Information Returns; 1099-NEC/MISC instructions | A |
| 15 | `payroll-quarterly-941.json` | Quarterly federal and state payroll filings | KB, FC, LIS | Instructions for Form 941; Pub 15 | B |
| 16 | `payroll-year-end-w2-940.json` | W-2/W-3 and FUTA year-end | JW | Instructions for W-2/W-3 and Form 940 | B |
| 17 | `tax-sales-tax-filing.json` | Periodic sales tax return | KB, FC | State revenue rules; Streamlined Sales Tax | C |
| 18 | `tax-state-nexus-review.json` | Multistate exposure review | AK | *Wayfair* (2018); state revenue departments | C |
| 19 | `tax-1040x-amended.json` | Amending an individual return | KB, AK | Instructions for Form 1040-X | B |
| 20 | `tax-rd-credit-6765.json` | Research credit study | KB | Instructions for Form 6765 (Section G business-component data) | A |
| 21 | `tax-estimated-tax-projection.json` | Mid-year projection and 1040-ES | AK, FC | Form 1040-ES; Pub 505 | B |
| 22 | `tax-fbar-foreign-accounts.json` | FinCEN 114 and Form 8938 | AK | FinCEN BSA E-Filing FBAR instructions; Instructions for Form 8938 | A |
| 23 | `tax-intake-13614c.json` | Full intake interview mapped to documents | CS, JF | Form 13614-C; Pub 4012 | A |
| 24 | `tax-firpta-8288b.json` | Foreign seller withholding certificate | — | IRS FIRPTA withholding certificates page; Instructions for Form 8288-B | A |
| 25 | `tax-client-onboarding-authorizations.json` | New tax client: 2848/8821, §7216 consent, prior returns | FC, LIS, CS | Instructions for Forms 2848 and 8821; Treas. Reg. §301.7216-3 | B |

## 3. Tax: IRS notices, collection and controversy (9)

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 26 | `irs-notice-response.json` | Client received a CP/LTR notice | CAN | IRS "Understanding your notice"; Document Upload Tool | B |
| 27 | `irs-collection-433a.json` | Individual collection information statement | CAN, SV | Form 433-A; Pub 1854 | A |
| 28 | `irs-collection-433b.json` | Business collection information statement | CAN | Form 433-B | A |
| 29 | `irs-collection-433f.json` | Short-form statement for an installment agreement | — | Form 433-F | A |
| 30 | `irs-offer-in-compromise.json` | Offer in compromise package | — | Form 656-B booklet, application checklist | A |
| 31 | `irs-penalty-abatement.json` | Reasonable-cause or first-time abatement | SV | IRM 20.1.1; IRS penalty relief pages | B |
| 32 | `irs-exam-response.json` | Audit / Information Document Request response | AK | Pub 556; IRM 4.10 | B |
| 33 | `irs-innocent-spouse-8857.json` | Innocent spouse relief | — | Instructions for Form 8857; Pub 971 | A |
| 34 | `irs-identity-theft-14039.json` | Tax-related identity theft | — | Form 14039 | A |

## 4. Accounting, audit and advisory engagements (12)

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 35 | `bookkeeping-month-end-close.json` | Monthly close request | KB, FC, LIS | Common practice | C |
| 36 | `bookkeeping-reconciliation-request.json` | Missing bank and card support | LIS | Common practice | C |
| 37 | `bookkeeping-catch-up-cleanup.json` | Behind-on-books cleanup | FC, LIS | IRC §6001; Pub 583 | B |
| 38 | `bookkeeping-year-end-review.json` | Annual books review | KB, FC, JW | Common practice | C |
| 39 | `assurance-compilation.json` | Compilation engagement | FC | AICPA SSARS AR-C 80 | B |
| 40 | `assurance-review.json` | Review engagement | — (gap) | AICPA SSARS AR-C 90 | B |
| 41 | `assurance-audit-pbc.json` | Audit prepared-by-client list | CS, KB, JW, SV | AICPA AU-C 500, 501, 505, 580 | B |
| 42 | `payroll-run-inputs.json` | Each payroll processing run | FC | Pub 15 | C |
| 43 | `firm-client-offboarding.json` | Disengagement and records return | FC, AK | Circular 230 §10.28 | B |
| 44 | `firm-practice-acquisition-dd.json` | Buying an accounting practice | FC | Common practice | C |
| 45 | `advisory-business-valuation.json` | Valuation engagement data request | CS | AICPA SSVS (VS 100) | C |
| 46 | `advisory-forensic-accounting.json` | Forensic / dispute engagement | CS | Common practice | C |

## 5. Nonprofit, government contracting and retirement plans (10)

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 47 | `nonprofit-1023-exemption.json` | 501(c)(3) application | — | IRS "Required attachment to Form 1023"; Instructions for Form 1023 | A |
| 48 | `nonprofit-1023-ez.json` | Streamlined exemption | — | Instructions for Form 1023-EZ (eligibility worksheet) | A |
| 49 | `benefits-vcp-submission.json` | Retirement plan correction (VCP) | — | IRS "Fill in VCP submission documents"; Instructions for Form 8950 | A |
| 50 | `benefits-401k-annual-review.json` | Annual 401(k) compliance check | — | IRS 401(k) plan checklist | B |
| 51 | `govcon-sam-registration.json` | SAM.gov entity registration | — | SAM.gov registration guide; GSA FSD | A |
| 52 | `govcon-sba-8a-application.json` | 8(a) initial application | — | SBA certify 8(a) document list; 13 CFR 124 | A |
| 53 | `govcon-sba-8a-annual-review.json` | 8(a) annual review | — | SBA 8(a) annual review checklist | A |
| 54 | `govcon-wosb-certification.json` | WOSB / EDWOSB certification | — | SBA WOSB checklist; 13 CFR 127.303 | A |
| 55 | `grants-federal-application.json` | Federal grant via Grants.gov | CS | SF-424 family instructions; 2 CFR 200 | B |
| 56 | `business-boi-report.json` | FinCEN BOI (foreign reporting companies only since March 2025) | FC | FinCEN BOI FAQs; interim final rule of 3/26/2025 | B |

## 6. Mortgage, lending and account opening (13)

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 57 | `mortgage-usda-502-direct.json` | USDA direct home loan | — | RD 502 application package; HB-1-3550 | A |
| 58 | `mortgage-usda-504-repair.json` | USDA repair loan or grant | — | RD 504 application package | A |
| 59 | `mortgage-usda-guaranteed.json` | USDA guaranteed loan file | — | USDA RD GHR Attachment 15-A checklist (2025) | A |
| 60 | `mortgage-condo-project.json` | Condo / HOA documentation | — | Fannie Mae Form 1076 / Freddie Mac Form 476 | A |
| 61 | `mortgage-fha-203k.json` | FHA rehab loan | — | HUD 203(k) document list; HUD 4000.1 | A |
| 62 | `mortgage-hecm-reverse.json` | Reverse mortgage | — | HUD HECM pages; HECM Mortgagee Letter attachment | B |
| 63 | `mortgage-construction-to-perm.json` | Construction-to-permanent | CS | Fannie Mae Selling Guide B5-3.1 | B |
| 64 | `mortgage-closing-buyer.json` | Buyer closing package | CS, SB | CFPB closing checklist; CFPB Closing Disclosure guide | A |
| 65 | `realestate-seller-listing.json` | Seller listing and disclosures | CS | 40 CFR 745 / HUD lead-based paint disclosure | B |
| 66 | `lending-commercial-loan.json` | Non-SBA business loan | CS | Common practice | C |
| 67 | `lending-invoice-factoring.json` | Factoring / AR financing | CS | Common practice | C |
| 68 | `banking-kyc-individual.json` | Individual account opening / KYC | CS, MX | FinCEN CIP, 31 CFR 1020.220 | B |
| 69 | `banking-kyb-beneficial-owners.json` | Business KYB / CDD | MX | FinCEN CDD rule, 31 CFR 1010.230 | B |

## 7. Insurance and disaster recovery (5)

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 70 | `insurance-nfip-flood-claim.json` | Flood insurance claim | — | FEMA NFIP Claims Checklist for Policyholders | A |
| 71 | `disaster-fema-individual-assistance.json` | FEMA individual assistance | — | DisasterAssistance.gov application checklist | A |
| 72 | `insurance-life-beneficiary-claim.json` | Life insurance death claim | — | NAIC consumer guidance | C |
| 73 | `insurance-commercial-application.json` | Commercial P&C submission | CS | ACORD 125/126/140 | C |
| 74 | `insurance-personal-lines.json` | Home and auto quote | CS | ACORD personal lines forms | C |

## 8. Government benefits, retirement and financial planning (18)

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 75 | `ssa-retirement-benefits.json` | Social Security retirement / spouse | — | SSA "Documents you need"; SSA-1; Pub 05-10377 | A |
| 76 | `ssa-survivors-benefits.json` | Widow(er) benefits | — | SSA-10 page | A |
| 77 | `ssa-lump-sum-death.json` | Lump-sum death payment | — | SSA-8 page | A |
| 78 | `ssa-parent-benefits.json` | Mother's / father's benefits | — | SSA-5 page | A |
| 79 | `ssa-ssi-application.json` | Supplemental Security Income | — | SSA "Documents you may need… SSI" | A |
| 80 | `medicare-part-b-sep.json` | Late Part B enrollment | — | CMS-40B, CMS-L564; Medicare.gov | A |
| 81 | `aca-marketplace-verification.json` | Marketplace data-matching documents | — | HealthCare.gov documents and deadlines | A |
| 82 | `va-disability-claim.json` | VA disability compensation | — | VA.gov evidence needed | A |
| 83 | `va-pension.json` | VA pension | — | VA.gov pension how-to-apply | A |
| 84 | `va-survivors-dic.json` | Survivors pension, DIC, accrued benefits | — | VA.gov evidence for pension/DIC/accrued | A |
| 85 | `federal-fers-retirement.json` | Federal employee retirement packet | — | OPM BAL 24-103 Att. 2; OPM application tips | A |
| 86 | `estate-savings-bonds-deceased.json` | Redeeming a deceased owner's bonds | — | TreasuryDirect; FS Form 5336 | A |
| 87 | `education-fafsa-prep.json` | FAFSA preparation | — | studentaid.gov "Things you need" | A |
| 88 | `education-fafsa-verification.json` | Selected for FAFSA verification | — | FSA Handbook AVG ch. 4 (2026-27) | A |
| 89 | `housing-hcv-income-verification.json` | Section 8 / HUD-assisted income verification | — | HUD Handbook 4350.3, App. 3 | A |
| 90 | `planning-financial-fact-find.json` | Financial plan data gathering | CS | CFP Board Practice Standards (gathering information) | C |
| 91 | `planning-retirement-review.json` | Retirement planning review | CS | CFP Board; SSA my Social Security statement | C |
| 92 | `investor-accredited-verification.json` | Reg D 506(c) accredited investor verification | CS | 17 CFR 230.506(c)(2)(ii) safe-harbor methods | A |

## 9. HR, employment and healthcare compliance (5)

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 93 | `hr-flsa-records.json` | Wage-hour records audit / retention | — | DOL WHD Fact Sheet #21; 29 CFR 516 | A |
| 94 | `hr-perm-audit-file.json` | PERM labor certification audit file | — | 20 CFR 656.10; DOL OFLC PERM audit guidance | B |
| 95 | `hr-hiring-manager-intake.json` | Recruiting search intake | CS | Common practice | C |
| 96 | `healthcare-medicare-855i.json` | Medicare provider enrollment | — | CMS-855I Section 12 attachments | A |
| 97 | `healthcare-hipaa-audit-readiness.json` | HIPAA policy and evidence pack | — | HHS OCR audit protocol | B |

## 10. Immigration (16)

All of these are Tier A unless marked otherwise. USCIS publishes a "Checklist of Required Initial Evidence" on most form pages.

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 98 | `immigration-i751-remove-conditions.json` | Two-year green card through marriage | CS | uscis.gov/i-751; I-751 instructions | A |
| 99 | `immigration-i864-affidavit-support.json` | Sponsor financial evidence | — | uscis.gov/i-864; I-864 instructions (ed. 08/24/26) | A |
| 100 | `immigration-i765-work-permit.json` | Standalone EAD | DW | uscis.gov/i-765; I-765 instructions | A |
| 101 | `immigration-i129f-fiance.json` | K-1 fiancé(e) petition | — | uscis.gov/i-129f | A |
| 102 | `immigration-i131-travel-document.json` | Advance parole / reentry permit | — | uscis.gov/i-131 | A |
| 103 | `immigration-i589-asylum.json` | Affirmative asylum | — | uscis.gov/i-589 | A |
| 104 | `immigration-i918-u-visa.json` | U nonimmigrant status | — | uscis.gov/i-918 | A |
| 105 | `immigration-i360-vawa.json` | VAWA self-petition | — | uscis.gov/i-360 | A |
| 106 | `immigration-i360-sij.json` | Special Immigrant Juvenile | — | uscis.gov/i-360; SIJ evidence checklist | A |
| 107 | `immigration-daca-renewal.json` | DACA renewal (I-821D, I-765, I-765WS) | DW | uscis.gov/i-821d | A |
| 108 | `immigration-h1b-petition.json` | H-1B petition | DW | uscis.gov/i-129, optional H-1B checklist; DOL LCA | A |
| 109 | `immigration-i140-employment.json` | Employment-based immigrant petition | — | uscis.gov/i-140 | A |
| 110 | `immigration-i601a-waiver.json` | Provisional unlawful-presence waiver | — | uscis.gov/i-601a | A |
| 111 | `immigration-i90-card-replacement.json` | Replace or renew a green card | — | uscis.gov/i-90 | A |
| 112 | `immigration-n600-citizenship-cert.json` | Certificate of citizenship | — | uscis.gov/n-600 | A |
| 113 | `passport-ds11-first-time.json` | First passport, adult or minor | — | travel.state.gov apply-in-person and under-16 pages | A |

## 11. Legal: corporate, IP and transactions (12)

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 114 | `legal-ma-due-diligence.json` | Sell-side / buy-side diligence request list | HV ("Check a Diligence Request List"), CS | Common practice; ABA Model SPA | C |
| 115 | `legal-post-closing-deliverables.json` | Post-closing checklist | HV ("Generate a Post-Closing Timeline") | Deal agreement | C |
| 116 | `legal-8k-item-101-inputs.json` | Material definitive agreement disclosure | HV ("Draft an Item 1.01 Disclosure") | SEC Form 8-K General Instructions, Item 1.01 | B |
| 117 | `legal-contract-review-intake.json` | Contract review request | CS, HV | Common practice | C |
| 118 | `legal-dpa-vendor-privacy.json` | DPA / vendor privacy review packet | HV (DPA workflow) | GDPR Art. 28(3) required terms | B |
| 119 | `legal-llc-formation.json` | New LLC or corporation | CS, FC | IRS LLC page and Form 8832; state SOS | B |
| 120 | `legal-annual-minute-book.json` | Annual compliance / minute book | CS | State SOS annual report rules | C |
| 121 | `legal-trademark-application.json` | USPTO trademark filing | CS | USPTO TEAS requirements; 37 CFR Part 2; TMEP | B |
| 122 | `legal-patent-application.json` | Invention disclosure to application | CS | USPTO "Apply for a patent"; 37 CFR 1.51 | B |
| 123 | `legal-franchise-review.json` | Prospective franchisee FDD review | CS | FTC Franchise Rule, 16 CFR 436 (FDD items 1–23) | B |
| 124 | `legal-commercial-lease-application.json` | Commercial tenant application | CS | Common practice | C |
| 125 | `legal-residential-tenant-screening.json` | Residential tenant application | CS | FTC FCRA guidance for landlords | C |

## 12. Legal: litigation and disputes (16)

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 126 | `legal-litigation-hold-custodians.json` | Preservation notice and custodian questionnaire | HV ("Draft Internal Litigation Hold") | FRCP 26, 37(e) | B |
| 127 | `legal-initial-disclosures-26a1.json` | Rule 26(a)(1) initial disclosures | CS, HV | FRCP 26(a)(1)(A) | A |
| 128 | `legal-discovery-responses.json` | Client documents for RFPs / interrogatories | HV ("Summarize Discovery Responses") | FRCP 33, 34 | B |
| 129 | `legal-deposition-prep.json` | Deposition prep packet | HV | FRCP 30 | C |
| 130 | `legal-case-chronology.json` | Key-events chronology intake | HV ("Extract Timeline of Key Events") | Common practice | C |
| 131 | `legal-records-subpoena.json` | Records subpoena (AO 88B) | — | AO 88B; FRCP 45 | B |
| 132 | `legal-personal-injury-auto.json` | Auto accident injury claim | CL, LM, MC, CS | Common practice | C |
| 133 | `legal-medical-records-request.json` | Medical records and bills (HIPAA authorization) | MC | 45 CFR 164.508(c) core elements; HHS right of access | A |
| 134 | `legal-workers-comp-state.json` | State workers' comp claim | — | CA DWC-1 (model); state agency | B |
| 135 | `legal-workers-comp-feca.json` | Federal employee injury (CA-1/CA-2) | — | DOL OWCP FECA | B |
| 136 | `legal-eeoc-charge.json` | Employment discrimination charge | CS | EEOC "How to file a charge" | A |
| 137 | `legal-criminal-defense-intake.json` | Criminal defense intake | CL, CS | Common practice | C |
| 138 | `legal-record-expungement.json` | Record clearance | — | State court self-help (CA model) | B |
| 139 | `legal-small-claims.json` | Small claims preparation | — | State court self-help (CA model) | B |
| 140 | `legal-eviction-landlord.json` | Landlord eviction case | — | State court self-help (CA model) | B |
| 141 | `legal-eviction-tenant.json` | Tenant eviction defense | — | State court self-help (CA model) | B |

## 13. Legal: family, estates and personal matters (13)

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 142 | `legal-divorce-intake.json` | Divorce / dissolution intake | CL, CS, OR | OR Dissolution Checklist; state self-help | C |
| 143 | `legal-divorce-financial-disclosure.json` | Mandatory financial disclosure | CL, CS | CA FL-140/142/150 (model); state rules | A |
| 144 | `legal-custody-parenting.json` | Custody / parenting plan | CL, CS | State court forms | C |
| 145 | `legal-prenup-disclosure.json` | Premarital agreement disclosure | — | Uniform Premarital Agreement Act §6 | C |
| 146 | `legal-guardianship-minor.json` | Guardianship of a minor | OR | State self-help (CA model) | B |
| 147 | `legal-conservatorship-adult.json` | Adult guardianship / conservatorship | OR | State self-help (CA model) | B |
| 148 | `legal-name-change.json` | Adult or minor name change | — | State self-help (CA model) | B |
| 149 | `legal-estate-planning.json` | Wills, trusts, POA intake | CS, MC, SB, OR | OR Estate Planning Information Checklist | C |
| 150 | `legal-probate-opening.json` | Opening probate | OR | State self-help; UPC | B |
| 151 | `legal-probate-inventory.json` | Estate inventory and appraisal | OR | UPC §3-706; CA inventory page | A |
| 152 | `legal-small-estate-affidavit.json` | Collecting a small estate without probate | — | UPC §3-1201; state forms | B |
| 153 | `legal-foia-request.json` | FOIA request preparation | — | foia.gov "How to make a FOIA request" | A |
| 154 | `legal-pro-bono-eligibility.json` | Legal aid income eligibility | CS | LSC 45 CFR 1611 | B |

## 14. Agencies, creative and IT services (16)

The demand signal here is strongest (Content Snare, HoneyBook, ClickUp, Paperform), but there are almost no official lists. Where a platform documents an exact access step, that platform document backs the item.

| # | Proposed file | Use when | Demand | Authority | Tier |
|---|---|---|---|---|---|
| 155 | `agency-website-content.json` | Website copy and asset collection | CS (starter-website, landing-page) | Common practice | C |
| 156 | `agency-hosting-credentials-handover.json` | Domain, hosting and CMS access handover (no passwords in chat; delegated access only) | CS (web-hosting-credentials) | Registrar / CMS delegated-access docs | C |
| 157 | `agency-web-design-discovery.json` | Web design discovery | CS, HB | Common practice | C |
| 158 | `agency-brand-discovery.json` | Brand / logo discovery | CS, HB | Common practice | C |
| 159 | `agency-seo-onboarding.json` | SEO engagement access and history | CS | Google Search Console and GA4 user-permission docs | B |
| 160 | `agency-paid-ads-onboarding.json` | Google Ads / Meta ads access | CS | Google Ads manager-account linking; Meta Business partner access | B |
| 161 | `agency-social-media-onboarding.json` | Social media management | CS, HB | Platform partner-access docs | C |
| 162 | `agency-content-request.json` | Blog, newsletter and content inputs | CS | Common practice | C |
| 163 | `agency-video-photo-production.json` | Shoot inputs, locations, releases | CS | Common practice | C |
| 164 | `agency-pr-press-kit.json` | Press kit assets | CS | Common practice | C |
| 165 | `agency-event-speaker-sponsor.json` | Speaker and sponsor assets | CS | Common practice | C |
| 166 | `vendor-supplier-onboarding.json` | New vendor: W-9, COI, licenses | CS, JF | IRS Form W-9; ACORD 25 | B |
| 167 | `vendor-security-questionnaire.json` | Vendor security / risk evidence | CS | NIST CSF 2.0; AICPA SOC 2 | B |
| 168 | `it-msp-onboarding.json` | Managed IT onboarding | CS | CIS Controls v8 (asset and software inventory) | B |
| 169 | `it-data-migration.json` | System migration inputs | CS | Common practice | C |
| 170 | `esg-data-request.json` | ESG / sustainability data request | CS | GRI Standards; ISSB IFRS S1/S2 | B |

---

## Dropped from the research (and why)

- **Harvey drafting workflows**: Translate, Proofread, Draft from Template, Research Memo, Motion to Dismiss, Redline Summary. These review or draft documents the firm already holds; they don't collect anything from a client.
- **Non-US variants** (Content Snare AU/NZ/UK, Karbon T1/T2/GST/VAT/BAS): outside the README's US-federal scope.
- **SNAP and Medicaid long-term care**: no federal list; state-specific only.
- **Forms 8821/2848 alone, Form 4564 IDR**: no standing document list (8821/2848 are folded into #25; IDRs into #32).
- **CFPB/FDIC death-of-account-holder pages**: they list no documents.
- **Generic "client intake", "employee onboarding", "mortgage questionnaire", "bankruptcy", "immigration intake"**: already covered by existing templates.

## Suggested build order

1. **Wave 1, Tier A with a high-value audience (31): built 26 in 0.6.0, 5 blocked.**
   - Built: #9, 14, 20, 22, 24, 27–30, 33, 47, 49, 60, 61, 64, 70, 71, 81–84, 88, 98–100 and 136.
   - Swap: #23 (13614-C intake) was replaced by #88 (FAFSA verification), because `tax-1040-free-prep-basic` already follows Form 13614-C.
   - Blocked: #57–59 (USDA 502, 504 and guaranteed) because rd.usda.gov refuses automated access, and #75 and #79 (SSA retirement, SSI) because ssa.gov refuses automated access. These need a person to download the source documents into the repo session, or a permission change.
2. **Wave 2, the rest of Tier A (35, now that #88 is built):** immigration, SSA/VA/FAFSA, govcon, legal Tier A.
3. **Wave 3, Tier B (62):** entity returns first (1065, 1120-S, 1041, 990), then legal and agency access lists.
4. **Wave 4, Tier C (41):** labelled "Mixed / common practice", same as the original six general lists.

## Counting note

170 proposed templates: 67 Tier A, 62 Tier B, 41 Tier C. Overlaps with the existing 48 templates were removed before numbering.
