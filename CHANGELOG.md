# Changelog

## 0.6.0 (2026-11-26)

- 26 new request-list templates, every item citing an official source read on 2026-11-26:
  - Tax: estate tax (706), 1099 filing season (with the $2,000 threshold for 2026 payments), research credit (6765), FBAR and Form 8938, and FIRPTA (8288-B).
  - IRS collection and relief: Forms 433-A, 433-B and 433-F, offer in compromise, and innocent spouse relief.
  - Nonprofit and retirement plans: 501(c)(3) application (1023) and VCP submission (8950).
  - Mortgage: FHA 203(k), condo project documents, and buyer closing.
  - Immigration: I-751, I-864 and I-765.
  - Employment: EEOC charge.
  - Benefits and aid: HealthCare.gov data matching, FAFSA verification, VA disability, VA pension, and VA survivors.
  - Disaster: FEMA Individual Assistance and NFIP flood claim.
- `docs/template-backlog.md`: 170 proposed templates graded by source strength, with the demand signal from Content Snare, TaxDome, Karbon, Financial Cents, AICPA, Harvey, Clio and others.
- `building-document-request-lists`: index, sources and description updated.
- Two new eval cases.

## 0.5.0 (2026-11-12)

- 31 new request-list templates, each a variant for a different client condition, with every item citing an official source: individual tax (basic, self-employed, rental), ITIN, IRS credit proof (three), business records (two), payroll (employee, contractor, employer), mortgage (conventional salaried, self-employed, rental income, other income, FHA, VA, hardship), SBA (7(a), two disaster loans, bank account), immigration (four), bankruptcy (chapter 7 and 13) and Social Security disability (adult and child).
- `building-document-request-lists`: picks among variants using a new `references/template-index.md`.
- `drafting-gift-letters`: new templates for Freddie Mac, FHA, VA and a Fannie Mae gift of equity, with a program comparison.
- `drafting-wisp`: sole-practitioner WISP template, data-theft response checklist and basic-safeguards checklist.
- New skill `drafting-incompleteness-notices`: the Regulation B notice of incomplete application.
- Four new eval cases.

## 0.4.1 (2026-11-11)

- Repository moved to `TryApraxo/doc-chaser`; links and install commands updated.

## 0.4.0 (2026-11-11)

- The plugin no longer ships any scripts. The directory will accept scripts only from Verified organizations, so the five skills that used one now carry the formula, counting procedure or rules in their instructions and reference files, with check cases.
- `calculating-trid-deadlines`: the reference file gains the counting procedure, a holiday table for 2026 to 2028 and six check cases.
- Removed the script unit tests; the eval suite remains.

## 0.3.2 (2026-11-11)

- Repository moved to `ApraxoTeam/doc-chaser`; links and install commands updated.

## 0.3.1 (2026-11-11)

- Removed two manifest fields (`supportUrl`, `documentationUrl`) that the directory does not recognize. The support and documentation links remain in the README.

## 0.3.0 (2026-11-11)

- Renamed the plugin from its working name to `doc-chaser` before first listing. No skill changed.

## 0.2.0 (2026-11-11)

- New skill `reviewing-received-documents`: checks what a client sent against the request list and tracks each item's status in the CSV.
- New skill `drafting-gift-letters`: mortgage gift letter with the elements in Fannie Mae Selling Guide B3-4.3-04, eligibility checks and the transfer evidence to collect.
- New skill `assessing-safeguards-readiness`: FTC Safeguards Rule self-assessment with a gap report and the 16 CFR 314.6 small-firm exemption.
- `drafting-wisp`: the Safeguards Rule reference now lists the four requirements that do not apply to firms with fewer than 5,000 consumers.

## 0.1.0 (2026-11-11)

First release.

- `building-document-request-lists`: six checklist templates (individual tax return, bookkeeping onboarding, mortgage purchase, mortgage refinance, legal intake, agency onboarding) with Markdown, CSV and JSON output.
- `drafting-client-reminders`: request and reminder sequences for email and text.
- `estimating-chasing-cost`: yearly cost of chasing clients, from the firm's own inputs.
- `drafting-wisp`: Written Information Security Plan draft in the IRS Publication 5708 structure.
- `calculating-trid-deadlines`: Loan Estimate and Closing Disclosure dates under Regulation Z.
