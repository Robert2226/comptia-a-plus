# Lab 2: Incident Reporting Workflow

## Objective
Simulate documenting and escalating a detected security event (e.g., phishing attempt) using an IT support/help desk workflow.

---

## Part 1: Gathering Evidence
### Steps Taken:
1. Collected all relevant screenshots:
   - Suspicious email content
   - Email headers
   - CLI inspection results (`nslookup`, `whois`, `curl`)

**Screenshots:**
- `Screenshots/Lab2_email.png`
- `Screenshots/Lab2_headers.png`
- `Screenshots/Lab2_cli.png`

---

## Part 2: Creating the Incident Ticket
### Mock Ticket Fields:
- **Incident Title:** Example — "Suspicious Email – Possible Phishing"
- **Description:**  
  _Include a brief but detailed summary of what was observed._
- **Steps Taken Before Reporting:**  
  _E.g., Isolated email, did not click links, inspected headers._
- **Attachments:**  
  _List all screenshots, header text file, CLI logs._

**Screenshot:** `Screenshots/Lab2_ticket_form.png`

---

## Part 3: Classification & Severity
| Severity Level | Description | Example |
|----------------|-------------|---------|
| Low            | Harmless spam | Unsolicited marketing email |
| Medium         | Possible phishing attempt | Email asking to verify account info |
| High           | Confirmed malicious activity | Credential theft or malware execution |

**Selected Severity:** _<choose one based on evidence>_

---

## Part 4: Escalation Path
- **Escalated To:** _(e.g., SOC team, IT Security)_
- **Method of Escalation:** _(ticket assignment, direct call, Slack/Teams message)_
- **Escalation Time:** _(timestamp)_

**Screenshot:** `Screenshots/Lab2_escalation.png`

---

## Part 5: Communication & Follow-Up
- **Users Notified:** _(list affected parties)_
- **Security Advisory Sent:** _(Y/N)_
- **Final Resolution:** _(domain blocked, system quarantined, ticket closed)_

**Screenshot:** `Screenshots/Lab2_resolution.png`

---

## Key Takeaways
- Always collect complete evidence before submitting an incident.
- Classify severity to help security teams prioritize.
- Follow escalation paths exactly as documented in policy.

---

## References
- [NIST SP 800-61 – Computer Security Incident Handling Guide](https://csrc.nist.gov/publications/detail/sp/800-61/rev-2/final)
- [CISA – Reporting Cyber Incidents](https://www.cisa.gov/report)

