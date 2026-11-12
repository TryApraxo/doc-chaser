<p align="center"><img src=".claude-plugin/icon.png" alt="Apraxo logo" width="120"></p>

# Doc Chaser by Apraxo

Skills for the paperwork side of a professional-services firm: asking clients for the right documents, chasing what is missing, and two compliance chores that small tax and mortgage shops put off.

> **Important:** This plugin helps with firm operations. It does not provide tax, legal, lending or compliance advice. Every output is a draft for a qualified professional to review, edit and send. Nothing is sent to a client and nothing is filed on anyone's behalf.

## What it does

| Skill | Use it when you say | What you get |
|---|---|---|
| `building-document-request-lists` | "What documents do I need from this client?" | A request list tailored to the client's situation, as Markdown or CSV |
| `reviewing-received-documents` | "Check what the client sent. What's still missing?" | Each item marked received, rejected or outstanding, with the exact resend instruction |
| `drafting-client-reminders` | "The client still hasn't sent their W-2. Write a reminder." | A first request, reminders and a final notice, for email or text |
| `estimating-chasing-cost` | "How much does chasing clients cost us?" | Hours and cost per year from your own numbers, with what-if scenarios |
| `drafting-wisp` | "I need a WISP for my tax practice." | A Written Information Security Plan draft in the IRS Publication 5708 structure (full or sole-practitioner version), plus a data-theft response checklist and a basic-safeguards checklist |
| `assessing-safeguards-readiness` | "Where do we stand on the FTC Safeguards Rule?" | A gap report: every requirement with its status and citation, and what to fix first |
| `calculating-trid-deadlines` | "When must the borrower have the CD for an April 2 closing?" | Loan Estimate and Closing Disclosure dates, each with its Regulation Z citation |
| `drafting-gift-letters` | "Her parents are gifting the down payment. Draft the gift letter." | A gift letter for the loan program (Fannie Mae, Freddie Mac, FHA, VA, or a Fannie Mae gift of equity), eligibility flags and the transfer evidence to collect |
| `drafting-incompleteness-notices` | "The borrower still hasn't sent the documents and the 30 days are running." | The Regulation B notice of incomplete application in the sample-form wording, with the 30-day timing check |

## Template library

37 request-list templates and 11 letter, plan and checklist templates. Templates with the same purpose come as variants for different conditions; each skill picks the variant that fits the client. Every template added since 0.5.0 cites the official source for each item, with the edition and the date it was read.

| Purpose | Variants |
|---|---|
| Individual tax return | General 1040; simple wage earner (IRS free-prep list); self-employed (Schedule C); rental property (Schedule E) |
| ITIN application | Form W-7 supporting documents, with tags for dependents and renewals |
| Proof for credits and filing status | EITC qualifying child; dependents and head of household; education credit (IRS Form 886-H series) |
| Business records | Short list by category; itemized list with employment tax records (IRS Publication 583); bookkeeping onboarding |
| Payroll onboarding | New employee (Form W-4 and Form I-9 Lists A, B, C); new contractor (Form W-9); new employer client (Form 8655, EIN, EFTPS) |
| Mortgage needs list | Program not yet known (purchase, refinance); conventional salaried; conventional self-employed; rental income; other income sources; FHA; VA eligibility evidence |
| Mortgage hardship | Mortgage assistance application (Form 710) by hardship and income type |
| SBA loans and banking | 7(a) application; disaster loan for a business; disaster loan for a home; business bank account |
| Immigration | I-130 for a spouse; I-130 for a parent, child or sibling; I-485 family-based; N-400 naturalization |
| Bankruptcy | Chapter 7; chapter 13 |
| Social Security disability | Adult; child |
| Gift letter | Fannie Mae; Freddie Mac; FHA; VA; Fannie Mae gift of equity |
| Security plan | Full WISP; sole-practitioner WISP; data-theft response checklist; basic-safeguards checklist |
| Notice of incomplete application | Written notice; written notice after an oral request (Regulation B Form C-6) |

The full index, with a "use when" line for each file, is in [template-index.md](skills/building-document-request-lists/references/template-index.md).

## Example prompts

- "New client has a W-2 job, a rental condo and sold some crypto. Build the document request list for their 1040 and give me a CSV."
- "Borrower is self-employed and getting a gift from her parents for the down payment. What goes on the needs list?"
- "Priya still owes us her brokerage 1099. Cut-off is April 3. Draft the next two reminders."
- "We have 320 clients and my admin spends about 50 minutes on each chasing documents, at $40 an hour. What does that cost a year?"
- "Draft our WISP. Three people, Drake on two desktops, clients email us documents, no MFA yet."
- "We mailed the LE on June 29. What's the earliest we can close?"
- "She uploaded a January pay stub and half a bank statement. What do I still need, and what do I tell her?"
- "Borrower's mother is wiring $20,000 for the down payment on a primary residence. Draft the gift letter."
- "New hire starts Monday. What do I collect for payroll and the I-9?"
- "Client is filing chapter 13. What documents do I need from them before the meeting of creditors?"
- "FHA loan, the borrower's aunt is giving $8,000. Draft the gift letter."
- "Application came in October 20 and we still have no bank statements. Draft the notice of incompleteness."
- "Two-person tax shop, 400 clients, MFA on the tax software but not on email. Where do we stand on the Safeguards Rule?"

## Install

In Claude Code:

```bash
claude plugin marketplace add TryApraxo/doc-chaser
```

```bash
claude plugin install doc-chaser@apraxo-plugins
```

To try it from a local copy without installing:

```bash
claude --plugin-dir .
```

## Requirements

None. The plugin is instructions, reference files and data only: no scripts, no programs and nothing to install.

## What the plugin runs, sends and stores

- **Runs:** nothing. The plugin contains no scripts, hooks or programs. Where a calculation is needed, the skill gives Claude the formula or counting method and check cases.
- **Sends:** nothing. The plugin has no MCP servers, no hooks and no network calls.
- **Stores:** nothing. If you ask for a file, such as a request list as CSV, Claude writes it where you ask.
- **Collects:** no personal data, no analytics, no credentials. The skills tell Claude not to ask for passwords, account numbers or Social Security numbers.

Your conversation with Claude is handled under the terms of the Claude product you use; this plugin adds no data handling of its own.

## Where the content comes from

| Content | Source |
|---|---|
| Individual tax return list | IRS, [Gather your documents](https://www.irs.gov/filing/gather-your-documents) |
| Mortgage lists | CFPB, [Create a loan application packet](https://www.consumerfinance.gov/owning-a-home/prepare/create-a-loan-application-packet/); Fannie Mae Selling Guide [B3-4.3-04, Personal Gifts](https://selling-guide.fanniemae.com/sel/b3-4.3-04/personal-gifts) |
| WISP template | IRS [Publication 5708](https://www.irs.gov/pub/irs-pdf/p5708.pdf) (Rev. 8-2024), a US government work, adapted |
| Safeguards Rule questions and summary | FTC, [Safeguards Rule: What Your Business Needs to Know](https://www.ftc.gov/business-guidance/resources/ftc-safeguards-rule-what-your-business-needs-know); [16 CFR 314.4](https://www.law.cornell.edu/cfr/text/16/314.4) and [314.6](https://www.law.cornell.edu/cfr/text/16/314.6) |
| Gift letter rules | Fannie Mae Selling Guide [B3-4.3-04, Personal Gifts](https://selling-guide.fanniemae.com/sel/b3-4.3-04/personal-gifts) (topic dated 02/04/2026) |
| Retention reference | IRS, [How long should I keep records?](https://www.irs.gov/businesses/small-businesses-self-employed/how-long-should-i-keep-records) |
| TRID timing | Regulation Z, [12 CFR 1026.19](https://www.consumerfinance.gov/rules-policy/regulations/1026/19/) and [1026.2](https://www.consumerfinance.gov/rules-policy/regulations/1026/2/) |
| Tax variants, ITIN, credit proof, business records | IRS: free tax preparation checklist, Form 13614-C, Publications 583, 527, 587 and 463, Form W-7 instructions, Forms 886-H-EIC, 886-H-DEP, 886-H-HOH and 886-H-AOC |
| Payroll | IRS hiring-employees and independent-contractor pages, Forms W-9 and 8655; USCIS Form I-9 (edition 01/20/25) and its Lists of Acceptable Documents |
| Mortgage variants | Fannie Mae Selling Guide income, asset and rental topics; HUD Handbook 4000.1 (issued August 12, 2026); VA.gov Certificate of Eligibility pages; Fannie Mae/Freddie Mac Form 710 |
| SBA | 13 CFR 120.191; SBA Forms 1919, 413, 5 and 5C; SBA.gov |
| Immigration | USCIS Form I-130 and I-485 instructions, the I-485 initial evidence checklist, and Form M-477 |
| Bankruptcy | 11 U.S.C. 521 and 1308; Bankruptcy Rule 4002; U.S. Courts Bankruptcy Basics; U.S. Trustee Program |
| Social Security disability | SSA Adult and Child Disability Starter Kits; SSA online application checklist |
| Gift letter variants | Freddie Mac Guide 5501.4; HUD Handbook 4000.1; VA Pamphlet 26-7 chapter 4; Fannie Mae B3-4.3-05 |
| Notice of incomplete application | Regulation B, [12 CFR 1002.9](https://www.consumerfinance.gov/rules-policy/regulations/1002/9/) and Appendix C, Form C-6 |
| Breach response and basic safeguards | IRS data-theft page and Publication 4557; FTC Data Breach Response guide; 16 CFR 314.4(j) |
| The six original general lists (parts), reminder cadence, document completeness checks | Common practice. No official source; labelled in each file; edit them to fit your firm |

Sources were read on 2026-11-11. Each template file names the exact document, edition and URL for its items. Rules and guides change: check the linked source before relying on a specific requirement. The adaptation of government material is not endorsed by any agency.

## Limits

- US federal sources only. No state tax, state bar, state breach-notification or Canadian rules.
- Mortgage lists are the common core. Lender, investor and loan-program rules add conditions.
- The TRID calculator does not model state waiting periods, rescission, timeshares or the restart of the Closing Disclosure waiting period.
- A WISP draft does not make a firm compliant. It must describe what the firm really does and be reviewed and signed by the firm.
- Gift letters cover Fannie Mae, Freddie Mac, FHA and VA. USDA and portfolio loans have no template.
- Templates built from an agency form follow the edition named in the file. Some editions are old (USCIS M-477 is from 2016; SBA Forms 5 and 5C show a passed expiry date). Check the agency's current edition before filing.
- The VA list covers Certificate of Eligibility evidence only. The FHA list covers the automated-underwriting sections of the Handbook, not manual underwriting. The SBA 7(a) list is the regulation's minimum; lenders ask for more. No USDA list.
- The notice of incomplete application covers Regulation B only, and the creditor chooses the response date.
- The Safeguards check is a self-assessment from your own answers. It is not an audit and never concludes that a firm complies.
- The document review checks completeness. It does not judge whether a document is genuine.
- The chasing-cost calculator uses your numbers only. It contains no industry benchmarks.

## Checks and evals

```bash
claude plugin validate --profile directory --strict .
```

```bash
claude plugin eval .
```

The `evals/` folder holds thirteen end-to-end cases, each run with and without the plugin. The TRID reference file includes check cases from the Regulation Z official commentary.

## Support

Open an issue at https://github.com/TryApraxo/doc-chaser/issues

## About Apraxo

Apraxo builds client-portal software for professional-services firms: document requests, reminders, e-signature and payments in one place. This plugin works on its own and needs no Apraxo account.

## License

MIT. See [LICENSE](LICENSE). The Apraxo name and logo are trademarks of Apraxo and are not covered by the MIT licence. Material adapted from US government publications is in the public domain in the United States.
