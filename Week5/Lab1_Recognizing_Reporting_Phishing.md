# Lab 1: Recognizing & Reporting Phishing Attempts

## Objective
Learn to identify phishing emails and suspicious links, and understand how to report them following security best practices.

---

## Part 1: Identifying Phishing Indicators
### Steps Taken:
1. Opened sample phishing email in a safe, sandboxed environment.
2. Checked:
   - Sender address and domain.
   - Subject line urgency or threats.
   - Spelling/grammar inconsistencies.
   - Unexpected attachments or links.

**Screenshot:** `Screenshots/Lab1_email_indicators.png`

---

## Part 2: Inspecting Email Headers
### Steps Taken:
1. Viewed full email headers (method depends on client: Gmail, Outlook, Apple Mail).
2. Located:
   - `Received:` lines for source IP.
   - `Return-Path` vs `From` address mismatch.
   - SPF/DKIM/DMARC authentication results.

**Screenshot:** `Screenshots/Lab1_email_headers.png`

---

## Part 3: Checking URLs Safely
### Steps Taken:
1. Hovered over link (without clicking) to reveal destination.
2. Used safe preview tools (VirusTotal, URLVoid) to scan URL.
3. Noted domain mismatches or unusual TLDs.

**Screenshot:** `Screenshots/Lab1_url_check.png`

---

## Part 3.5: CLI Workflow for URL Inspection
**Purpose:** Check a suspicious URL from the terminal without opening it in a browser.

1. **Extract the domain** from the link  
   Example suspicious URL:  

