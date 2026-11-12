<!--
TEMPLATE: Data theft response checklist for a tax professional

PURPOSE
A step list to work through, and keep as a record, after client data is
stolen, lost or exposed at a tax practice.

WHEN TO USE THIS VARIANT
- Use this file when a data theft or loss has happened or is suspected.
- To write the firm's security plan before anything happens: use
  wisp-template.md, or wisp-template-sole-practitioner.md for a one-person
  practice.
- To check basic technical protections: use security-six-checklist.md.

SOURCES (retrieved 2026-11-11)
[IRS]  IRS, "Data theft information for tax professionals", page last
       reviewed or updated 26-Mar-2026
       https://www.irs.gov/individuals/data-theft-information-for-tax-professionals
[4557] IRS Publication 4557 (Rev. 6-2024), Safeguarding Taxpayer Data,
       pages 8, 11, 12 and 17
       https://www.irs.gov/pub/irs-pdf/p4557.pdf
[5708] IRS Publication 5708 (Rev. 8-2024), sample Reportable Event Policy,
       page 10
       https://www.irs.gov/pub/irs-pdf/p5708.pdf
[FTC]  FTC, "Data Breach Response: A Guide for Business", dated August 2023
       https://www.ftc.gov/business-guidance/resources/data-breach-response-guide-business
[RULE] 16 CFR 314.4(j) (as amended at 88 FR 77508, Nov. 13, 2023) and the
       "notification event" definition in 16 CFR 314.2(m)
       https://www.law.cornell.edu/cfr/text/16/314.4
       https://www.law.cornell.edu/cfr/text/16/314.2

REQUIRED ELEMENTS AND WHERE EACH COMES FROM
Every step carries its source tag. In summary:
- Report to the IRS Stakeholder Liaison, law enforcement, state tax agencies
  and state attorneys general; contact a security expert and the insurer;
  contact the FTC, credit bureaus and clients: [IRS]
- Secure operations, fix vulnerabilities, notify appropriate parties, and the
  contents of the notice to individuals: [FTC]
- Recovery steps before resuming tax preparation: [4557] page 12
- Post-incident review recorded as an addendum to the WISP: [5708]
- FTC notification for 500 or more consumers within 30 days, and the six
  items the notice must include: [RULE] 314.4(j)(1)(i) to (vi)

LIMITS
- [RULE] is the only legally binding item here. [IRS], [4557] and [FTC] are
  agency guidance; [IRS] calls its steps "preliminary" and says to consult a
  security professional for a comprehensive list.
- 16 CFR 314.6 does not exempt small firms from 314.4(j).
- State breach notification laws have their own triggers, contents and
  deadlines and are not covered. [FTC] says all states, the District of
  Columbia, Puerto Rico and the Virgin Islands have them.
- The sources differ on the FBI: [IRS] lists the local FBI office without
  condition; [4557] says "(if directed by IRS)". The step below follows [IRS]
  and notes the difference.
- The incident record table and the Done/Date columns are layout.
-->

# Data theft response checklist

**Firm:** [FIRM NAME]
**Person coordinating the response:** [NAME]

## Incident record

| Item | Entry |
|---|---|
| Date and time discovered | [DATE AND TIME] |
| How it was discovered | [DESCRIPTION] |
| Date or date range of the incident, if it can be determined | [DATE OR RANGE] |
| Types of information involved | [TYPES] |
| Number of clients affected or potentially affected | [NUMBER] |
| Was the information encrypted, and was the encryption key accessed? | [YES / NO / UNKNOWN] |
| Latest date to notify the FTC if 500 or more consumers are involved (discovery date + 30 days) | [DATE] |

## 1. Secure operations

- [ ] Secure physical areas potentially related to the breach; lock them and change access codes if needed [FTC]
- [ ] Take all affected equipment offline immediately, but do not turn machines off until forensic experts arrive [FTC]
- [ ] If a computer connected to the Internet is compromised, disconnect it from the Internet [4557]
- [ ] Update credentials and passwords of authorized users [FTC]
- [ ] Remove any improperly posted personal information from the firm's website, and ask other sites that hold a copy to remove it [FTC]
- [ ] Interview the people who discovered the breach and document the investigation [FTC]
- [ ] Do not destroy any forensic evidence; preserve and review files or programs that may show how the breach occurred [FTC] [4557]

## 2. Report to the IRS and law enforcement

- [ ] Report the client data theft to the local IRS Stakeholder Liaison. Speed is critical: if reported quickly, the IRS can take steps to block fraudulent returns [IRS]
  - Contact: [LIAISON NAME AND CONTACT]. Date reported: [DATE]
- [ ] Federal Bureau of Investigation, local office [IRS]. Publication 4557 says "if directed by IRS"
- [ ] Secret Service, local office, if directed [IRS]
- [ ] Local police, to file a police report on the data breach [IRS]
- [ ] Ransomware attack: also contact the FBI and the Cybersecurity and Infrastructure Security Agency (CISA) [4557]

## 3. Notify the Federal Trade Commission, if 500 or more consumers

- [ ] Decide whether this is a notification event: acquisition of unencrypted customer information without the authorization of the individual it pertains to. Information counts as unencrypted if the encryption key was accessed by an unauthorized person [RULE 314.2(m)]
- [ ] If the event involves the information of at least 500 consumers, notify the FTC as soon as possible and no later than 30 days after discovery, electronically on the form on the FTC's website [RULE 314.4(j)(1)]
- [ ] Discovery is the first day the event is known to the firm, including to any employee, officer or agent other than the person who committed the breach [RULE 314.4(j)(2)]

The notice must include [RULE 314.4(j)(1)(i) to (vi)]:

- [ ] The name and contact information of the reporting financial institution
- [ ] A description of the types of information involved
- [ ] The date or date range of the event, if it can be determined
- [ ] The number of consumers affected or potentially affected
- [ ] A general description of the event
- [ ] Whether a law enforcement official has given a written determination that notifying the public would impede a criminal investigation or damage national security, and how the FTC can contact that official

Date FTC notified: [DATE, OR "NOT REQUIRED: FEWER THAN 500 CONSUMERS"]

## 4. Contact the states

- [ ] State tax agencies for each state in which the firm prepares returns; the Federation of Tax Administrators "Report a Data Breach" page lists the contacts [IRS]
- [ ] Determine whether the state attorney general must be notified, for each state in which the firm prepares returns [IRS]
- [ ] Check whether breach notification is required under applicable state law [4557] [FTC]

| State | Tax agency contacted (date) | Attorney general contacted (date) |
|---|---|---|
| [STATE] | [DATE] | [DATE] |

## 5. Contact experts

- [ ] Security expert, to determine the cause and scope of the breach, stop it and prevent further breaches [IRS]
- [ ] Insurance company, to report the breach and check whether the policy covers data breach mitigation expenses [IRS]
- [ ] Legal counsel, for advice on the federal and state laws that may apply [FTC]

## 6. Fix vulnerabilities

- [ ] If service providers were involved, examine what personal information they can access, decide whether to change their access, and verify any fix they report [FTC]
- [ ] Check whether network segmentation contained the breach [FTC]
- [ ] With the forensics experts: find out whether encryption was enabled, review logs to see who had access, restrict access that is not needed, and verify the types of information compromised and the number of people affected [FTC]
- [ ] Determine how the intrusion or theft occurred and make any required fixes before resuming tax preparation activities and being issued a new EFIN [4557]

## 7. Notify clients and other businesses

- [ ] Consult the law enforcement contact about the timing of the notification so it does not impede the investigation [FTC] [IRS]
- [ ] Send an individual letter to all victims to inform them of the breach [IRS]
- [ ] Credit bureaus (Equifax, Experian, TransUnion), to notify them of the compromise [IRS]; if Social Security numbers were stolen, contact them for additional information or advice [FTC]
- [ ] Credit monitoring or identity theft protection: certain states require offering it [IRS]; the FTC suggests considering at least a year free, particularly if financial information or Social Security numbers were exposed [FTC]
- [ ] If account access information was stolen for accounts the firm does not maintain, notify the institution that does [FTC]
- [ ] Tell clients to complete IRS Form 14039, Identity Theft Affidavit, only if they receive a notice or letter from the IRS or their e-filed return is rejected for a duplicate Social Security number [IRS]
- [ ] Designate one point person for releasing information [FTC]

The client notice should cover, unless state law says otherwise [FTC]:

- [ ] How it happened
- [ ] What information was taken
- [ ] How the thieves have used the information, if known
- [ ] What the firm has done to remedy the situation
- [ ] What the firm is doing to protect individuals, such as free credit monitoring
- [ ] How to reach the relevant contact at the firm
- [ ] Steps people can take, such as fraud alerts or credit freezes, with a reference to IdentityTheft.gov
- [ ] How the firm will contact clients in the future

The FTC guide includes a model letter with the headings: What Happened, What Information Was Involved, What We Are Doing, What You Can Do, Other Important Information, For More Information.

## 8. Recover

- [ ] Update the IRS Stakeholder Liaison with developments [4557]
- [ ] Check the EFIN status in e-Services and the returns filed per PTIN; contact the IRS e-help Desk if totals exceed the returns the firm filed [4557]
- [ ] Develop a continuity plan [4557]
- [ ] Make full, encrypted backups of all business data and files on a routine schedule [4557]
- [ ] Consult the professional insurance provider about data theft protection [4557]
- [ ] Hold a post-incident review of the events and actions taken, decide whether operations must change, and keep the record as an addendum to the firm's Written Information Security Plan [5708]

---

This is a draft checklist for the practitioner, and for legal counsel and a security professional, to review. It is not legal advice.
