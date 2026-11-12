<!--
TEMPLATE: Written Information Security Plan (WISP) for a one-person tax practice

PURPOSE
A shorter WISP for a sole practitioner who prepares tax returns, with no
employees or only outside contractors (IT provider, cleaning service).

WHEN TO USE THIS VARIANT
- Use this file for a one-person practice. IRS Publication 5708 says "a sole
  practitioner can use a more abbreviated and simplified plan than a
  10-partner accounting firm".
- Firm with employees or more than one practitioner: use wisp-template.md.
- After a data theft: use data-breach-response-checklist.md.
- Quick check of basic technical protections: security-six-checklist.md.

SOURCES (retrieved 2026-11-11)
- IRS Publication 5708 (Rev. 8-2024), Creating a Written Information
  Security Plan for your Tax & Accounting Practice
  https://www.irs.gov/pub/irs-pdf/p5708.pdf
- IRS Publication 4557 (Rev. 6-2024), Safeguarding Taxpayer Data
  https://www.irs.gov/pub/irs-pdf/p4557.pdf
- 16 CFR 314.6, Exceptions (86 FR 70308, Dec. 9, 2021)
  https://www.law.cornell.edu/cfr/text/16/314.6
- 16 CFR 314.4, Elements (as amended at 88 FR 77508, Nov. 13, 2023)
  https://www.law.cornell.edu/cfr/text/16/314.4

REQUIRED ELEMENTS AND WHERE EACH COMES FROM
Structure: Pub 5708 "WISP - Outline", page 4, items I to VII.
- I Objective, II Purpose, III Scope: Pub 5708 outline item I; sample pages 6
- IV Qualified individual (Data Security Coordinator) and Public Information
  Officer: outline item II; sample page 7; "Requirements", page 2
- V Risk assessment: outline item III; "Assess Risks", page 13
- VI Hardware inventory: outline item IV; page 14; Attachment E
- VII Safety measures (data collection and retention, data disclosure,
  network protection, user access, electronic data exchange, Wi-Fi access,
  remote access, connected devices, reportable incidents): outline item V;
  sample pages 8 to 12; Pub 4557 pages 4 to 8
- VIII Implementation clause, signed and dated: outline item VI; page 16
- Attachments A to F: outline item VII; samples pages 19 to 25
- Multi-factor authentication: Pub 5708 page 2; Pub 4557 page 13 ("required
  for all companies regardless of size"); 16 CFR 314.4(c)(5)
- FTC report for 500 or more people within 30 days: Pub 5708 pages 2 and 22;
  16 CFR 314.4(j)

SECTIONS MARKED OPTIONAL
16 CFR 314.6: "Section 314.4(b)(1), (d)(2), (h), and (i) do not apply to
financial institutions that maintain customer information concerning fewer
than five thousand consumers."
- 314.4(b)(1), the written risk assessment: section V is marked optional
- 314.4(d)(2), continuous monitoring, or annual penetration testing and
  six-monthly vulnerability assessments: marked optional in section V
- 314.4(h), the written incident response plan: section VII "Reportable
  incidents" and Attachment C are marked optional
- 314.4(i), the annual written report to a board or senior officer: not in
  Pub 5708; one optional line in section IV
The optional sections are still in the Pub 5708 outline, which says to
"incorporate all the required elements in your plan, but scale the
comprehensiveness to your firm's size". Keep them unless the practitioner
decides otherwise. Everything else in 314.4 still applies below 5,000
consumers, including 314.4(a), (b) apart from (b)(1), (c), (d)(1), (e), (f),
(g) and (j).

LIMITS
- Pub 5708 describes itself as sample information, not a substitute for a
  plan based on the firm's own needs.
- Pub 5708 says the DSC and PIO should be different people "in most firms of
  two or more practitioners". Naming the owner to both roles here is this
  template's reading for a one-person firm.
- Employee rules in Pub 5708 (background checks, discipline, termination) are
  left out because there are no employees; contractor access is kept.
- State data security and breach notification laws are not covered.
- This template does not make a firm compliant. Never state a control the
  practitioner has not confirmed.
-->

# Written Information Security Plan (WISP)

**[FIRM NAME]**

This document is available to clients by request and with the consent of the Data Security Coordinator.

Last modified or reviewed: [LAST REVIEW DATE]. Review and update at least annually.

## I. Objective

The objective of this Written Information Security Plan is to create effective administrative, technical and physical safeguards for the protection of the Personally Identifiable Information (PII) retained by [FIRM NAME] (the Firm), and to comply with the Firm's obligations under the Gramm-Leach-Bliley Act and the Federal Trade Commission Financial Privacy and Safeguards Rules.

For this plan, PII means the first name and last name, or first initial and last name, of a taxpayer, spouse, dependent or legal guardianship person, in combination with any of the following retained by the Firm:

- Social Security number, date of birth or employment data
- Driver's license number or state-issued identification card number
- Income data, tax filing data, retirement plan data, asset ownership data or investment data
- Financial account number, credit or debit card number, with or without a security code, access code, personal identification number or password that permits access to a client's financial accounts
- E-mail addresses, non-listed phone numbers, and residential or mobile contact information

PII does not include information obtained from publicly available sources or from government records lawfully made available to the general public.

## II. Purpose

This plan is to:

- Ensure the security and confidentiality of all PII retained by the Firm
- Protect PII against anticipated threats or hazards to its security or integrity
- Protect against unauthorized access to or use of PII in a manner that creates a substantial risk of identity theft or fraudulent or harmful use

## III. Scope

Under this plan the Firm will:

- Identify reasonably foreseeable internal and external risks to the security, confidentiality and integrity of electronic, paper or other records containing PII
- Assess the potential damage of these threats, considering the sensitivity of the PII
- Evaluate the sufficiency of existing policies, procedures, systems and other safeguards to control those risks
- Design and implement safeguards to minimize those risks
- Regularly monitor and assess the effectiveness of those safeguards

## IV. Responsible individual

**Data Security Coordinator (DSC):** [OWNER NAME], [OWNER TITLE]. The DSC is the Firm's qualified individual and will:

- Implement this plan, including all daily operating procedures
- Identify every place the Firm stores PII and restrict access to it
- Evaluate the ability of third-party service providers to maintain appropriate security for the PII they can access, and require them to do so
- Review this plan at least annually, or whenever a material change in the practice affects the security of records containing PII

**Public Information Officer (PIO):** [OWNER NAME]. All statements to clients, law enforcement, news media and business associates about a security incident come from this person.

**Authorized users:** listed in Attachment F.

[OPTIONAL under 16 CFR 314.6 if the Firm holds information on fewer than 5,000 consumers] Annual written report on the security program under 16 CFR 314.4(i): [NOT APPLICABLE, OR DESCRIBE]

## V. Risk assessment

[OPTIONAL IN WRITTEN FORM under 16 CFR 314.6 if the Firm holds information on fewer than 5,000 consumers. IRS Publication 5708 includes it in its outline.]

**Types of information the Firm handles:** [LIST, FOR EXAMPLE TAXPAYER PII ON PAPER AND IN ELECTRONIC FORM, PRIVATE BUSINESS FINANCIAL INFORMATION]

**Potential areas for data loss:**

| Risk | Internal or external | Current safeguard | Gap or action |
|---|---|---|---|
| [FOR EXAMPLE: PHYSICAL THEFT OF PAPER OR ELECTRONIC FILES] | [INTERNAL OR EXTERNAL] | [SAFEGUARD IN PLACE] | [GAP OR ACTION] |
| [FOR EXAMPLE: REMOTE ACCESS TAKEOVER OF THE COMPUTER NETWORK] | [INTERNAL OR EXTERNAL] | [SAFEGUARD IN PLACE] | [GAP OR ACTION] |
| [FOR EXAMPLE: LOSS DUE TO FIRE OR OTHER NATURAL CAUSE] | [INTERNAL OR EXTERNAL] | [SAFEGUARD IN PLACE] | [GAP OR ACTION] |

**Procedures to monitor and test for risks:** [DESCRIBE HOW AND HOW OFTEN THE DSC CHECKS THE SAFEGUARDS]

[OPTIONAL under 16 CFR 314.6] Continuous monitoring, or annual penetration testing with vulnerability assessments every six months (16 CFR 314.4(d)(2)): [NOT USED, OR DESCRIBE]

## VI. Hardware inventory

Every device that comes in contact with taxpayer data is listed in Attachment E with its description, physical location and the types of information it stores or processes.

## VII. Safety measures

### Data collection and retention

- The Firm collects only the PII necessary for legitimate business needs.
- PII is stored only in these places and formats: [LIST: TAX SOFTWARE, CLIENT PORTAL, CLOUD STORAGE, COMPUTER, EXTERNAL DRIVES, FILING CABINET]
- Records containing PII are destroyed or deleted at the earliest opportunity consistent with business needs and legal retention requirements, as set out in Attachment A.

### Data disclosure

- No PII is disclosed without authenticating the receiving party and without written authorization from the individual whose PII it is.
- Paper and electronic records containing PII are kept securely on the premises. If records must leave, only the minimum necessary is taken, it is returned as soon as possible, and it is never left unattended in a car, home or other insecure location.
- In the ordinary course of business the Firm may share client PII with: [LIST: STATE AND FEDERAL TAX AUTHORITIES, TAX SOFTWARE VENDOR, AND ANY BOOKKEEPING, PAYROLL, IT SUPPORT OR OTHER PROVIDER]. Access by these third parties is the minimum required, and each service provider must meet the standards of this plan.

### Network protection

- Firewall protection, operating system security patches and all software are kept up to date on every computer that accesses, stores or processes PII.
- Anti-virus and anti-malware security software is installed, kept up to date and set to update automatically on every device.
- Strong passwords of eight or more characters, with upper- and lower-case letters, numbers and special characters, are used. Passwords are changed every 365 days or when there is evidence of a compromise.
- Firm passwords are not used on other sites, and personal passwords are not used for Firm business.
- Event logging stays enabled on all systems containing PII. The DSC reviews the logs at intervals of no more than 90 days.
- Drive encryption is used on: [LIST DEVICES]
- Client data is backed up in encrypted form to: [EXTERNAL DRIVE OR CLOUD SERVICE], on this schedule: [BACKUP SCHEDULE]

### User access

- Multi-factor authentication is used by anyone accessing client information on the Firm's systems: [LIST SYSTEMS WITH MFA ENABLED]
- [LIST ANY SYSTEM WITHOUT MFA AND THE DATE IT WILL BE ENABLED, OR THE DSC'S WRITTEN APPROVAL OF AN EQUIVALENT CONTROL]
- There are no shared passwords or accounts.
- Password manager, if used: [NAME, OR NONE]. It stores credentials on a secure encrypted site and requires multi-factor authentication for new devices.

### Electronic data exchange

- PII is not sent in an unprotected format such as plain e-mail unless encryption or password protection is present. The password is sent to the recipient by a different method from the data, such as by phone call or text message.
- Documents containing PII are exchanged through: [PASSWORD-PROTECTED PORTAL OR OTHER METHOD]
- Files containing PII on USB or other interface drives are encrypted.

### Wi-Fi access

- Firm Wi-Fi uses strong encryption and requires a password. Any guest Wi-Fi for clients is on a separate network.
- Default factory passwords on the router, printers and every other wireless-capable device have been changed.

### Remote access

- Remote access: [NOT USED, OR NAME THE TOOL]
- Remote access is allowed only with multi-factor authentication in addition to username and password, using tools that encrypt both the traffic and the sign-in.

### Connected devices

- New devices get a security review before they join the network, including security patches and login and password settings.
- "AutoRun" features for USB ports and optical drives are disabled.
- Hard drives and memory devices are erased at the end of their service life, or physically destroyed if they cannot be erased.

### Reportable incidents

[A WRITTEN INCIDENT RESPONSE PLAN IS OPTIONAL under 16 CFR 314.6 if the Firm holds information on fewer than 5,000 consumers. IRS Publication 5708 includes this policy in its outline. The FTC notification in the last bullet is NOT optional.]

- After a data security incident that requires notification, the DSC reviews the events and the actions taken, decides whether operations must change, and keeps a record as an addendum to this plan.
- Steps to re-secure devices, data, passwords and networks, and who carries them out: [DESCRIBE, AND NAME ANY IT PROVIDER]
- Data theft or cyber insurance carrier: [CARRIER AND POLICY CONTACT, OR NONE]. Legal counsel: [NAME, OR NONE]
- The DSC notifies the IRS Stakeholder Liaison and the other parties listed in Attachment C.
- A security event affecting 500 or more people is reported to the Federal Trade Commission as soon as possible and no later than 30 days from discovery.

## VIII. Implementation

Effective [DATE OF IMPLEMENTATION], [FIRM NAME] has created this Written Information Security Plan in compliance with the requirements for a written data security plan found in the Gramm-Leach-Bliley Act and the Federal Trade Commission Financial Privacy and Safeguards Rules.

[ADD ANY STATE REGULATORY REQUIREMENTS THAT APPLY]

Signed: ______________________ Date: __________

[OWNER NAME], [OWNER TITLE], Owner and Data Security Coordinator

---

## Attachment A: Record retention policy

- In no case are paper or electronic records containing PII kept longer than [NUMBER] years.
- Paper records are securely destroyed by cross-cut shredding or incineration at the end of their service life.
- Electronic records are securely destroyed by deleting and overwriting the file directory, by reformatting the drive, or by destroying the drive.

## Attachment B: Rules of behavior and conduct safeguarding client PII

- Do not click a link or open an attachment that was not expected; call the sender to verify.
- Use separate personal and business computers, mobile devices and e-mail accounts.
- Do not connect personal or untrusted storage devices or hardware to business computers or networks.
- Do not download software from an unknown web page.
- Never respond to unsolicited calls asking for sensitive personal or business information, and never give out usernames or passwords.
- Do not respond to pop-up windows; use a pop-up blocker.
- Use strong passwords, do not reuse them, and change default passwords on devices immediately.
- Conduct online business only over a secure browser connection.

## Attachment C: Security breach procedures and notifications

[OPTIONAL as part of a written incident response plan under 16 CFR 314.6; see section VII.]

If the DSC determines that PII has been stolen or lost, the Firm will notify:

| Who | Contact |
|---|---|
| IRS Stakeholder Liaison | [CONTACT] |
| State Attorney General's office | [CONTACT FOR EACH STATE] |
| State tax agencies | [CONTACT FOR EACH STATE WHERE RETURNS ARE PREPARED] |
| FBI Internet Crime Complaint Center, if a cyber-crime involving electronic data theft | [CONTACT] |
| Federal Trade Commission, for a security event affecting 500 or more people, within 30 days of discovery, through its online Safeguards Rule Security Event Reporting Form | [DATE REPORTED, IF APPLICABLE] |
| Local law enforcement | [CONTACT] |
| Tax software vendor | [CONTACT] |
| Liability insurance carrier | [CONTACT] |
| Legal counsel | [CONTACT] |
| The victims of the theft, to the extent required by law and good business practice | [METHOD] |

Checks to make: review the EFIN activity report in IRS e-Services for more returns filed than the Firm transmitted, and for returns submitted outside normal hours.

For the full step list, use `data-breach-response-checklist.md`.

## Attachment D: Contractor acknowledgement of understanding

For each outside party with access to the premises or systems, such as an IT professional, cleaning service or copier servicing company.

I, [CONTRACTOR NAME], acknowledge that I have been informed of the Written Information Security Plan used by [FIRM NAME]. I understand the importance of protecting the Personally Identifiable Information of the Firm's clients and will comply with the purpose and intent of this plan.

Signed: ______________________ Date: __________

Title: [CONTRACTOR TITLE OR COMPANY]

## Attachment E: Hardware inventory containing PII

| Hardware item | Location | Principal user | Information stored or processed | In-service date | Last inventoried |
|---|---|---|---|---|---|
| [ITEM] | [LOCATION] | [USER] | [TYPES OF INFORMATION] | [DATE] | [DATE] |

Include filing cabinets and archive boxes, computers, laptops, business cell phones, routers, printers, removable drives and cloud storage.

## Attachment F: People authorized to access PII

| Name | Role | Job duties | Access level | Date access granted | Date access terminated |
|---|---|---|---|---|---|
| [OWNER NAME] | DSC | [DUTIES] | Full access to all PII | [DATE] | |
| [CONTRACTOR NAME] | [ROLE] | [DUTIES] | [ACCESS LEVEL] | [DATE] | [DATE] |

---

This is a draft for the practitioner, and a security or legal professional where needed, to review. It is not legal advice and does not make the Firm compliant.
