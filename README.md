# Phishing Email Detection & Awareness System 
**Cybersecurity Task 2 | Future Interns (2026)**

##  Project Overview
This project demonstrates the analytical workflow of a Security Analyst in identifying and mitigating phishing threats. By analyzing real-world samples, I have documented the technical indicators used by attackers to bypass modern email security filters.

## Objectives
* **Header Investigation:** Analyzing SPF, DKIM, and DMARC records to verify sender legitimacy.
* **Attack Archetyping:** Identifying different phishing methods (Look-alike domains, Authorized Spoofing, and Account Takeovers).
* **Risk Mitigation:** Developing a corporate-ready awareness report to reduce the human-element risk.

## Analysis Summary: The Three Archetypes
I analyzed three distinct phishing samples to showcase a broad range of threats:
1. **The "Fake" (Microsoft):** Total authentication failure using a typosquatted domain.
2. **The "Sneaky" (Ripple/CoinDesk):** A "Pass" on SPF/DKIM by leveraging a compromised 3rd-party mail server.
3. **The "Hacked" (Suksapan):** A Business Email Compromise (BEC) scenario where a legitimate account was hijacked to send spam.

## Tools Used
* **Google Admin Toolbox / MXToolbox:** For deep-dive header analysis.
* **VirusTotal:** For domain and IP reputation checks.
* **Markdown/PDF:** For professional reporting.

## Repository Contents
* `Phishing_Detection_Report.pdf`: The full analysis and employee guidelines.
* `/Evidence`: Raw header data and technical logs for the three samples.

---
**Author:** Denise Mutayi  
**Role:** Cybersecurity Intern  
