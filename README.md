# Future_CS_02
# Phishing Email Detection & Awareness System 
**Cybersecurity Task 2 | Future Interns (2026)**

## 📌 Project Overview
Phishing remains one of the most prevalent threats in the modern cyber landscape. This project focuses on the role of a **Security Analyst** in identifying, analyzing, and mitigating phishing attacks through technical investigation and employee awareness.

The goal of this project was to analyze real-world phishing samples, dissect their technical headers, and produce a professional awareness report to educate non-technical users on identifying malicious intent.

## 🎯 Objectives
* **Technical Analysis:** Investigate email headers (SPF, DKIM, DMARC) to verify sender authenticity.
* **Indicator Identification:** Identify common social engineering triggers (Urgency, Greed, Fear).
* **Risk Classification:** Categorize threats based on technical and contextual markers.
* **Awareness Education:** Create a "Client-Ready" report for corporate security training.

## 🛠️ Tools & Technologies Used
* **Google Admin Toolbox:** Used for deep-dive Message Header analysis.
* **MXToolbox:** Utilized for DNS lookup and SPF/DKIM/DMARC verification.
* **URLScan.io / VirusTotal:** (Research) For safe inspection of malicious URLs and domain reputation.
* **GitHub:** Version control and project documentation.

## 📂 Repository Structure
* `Phishing_Detection_Report.pdf`: The final professional awareness document.
* `/Evidence`: Contains the raw headers and analysis notes for the investigated samples.
* `README.md`: Project summary and methodology.

## 🧪 Analysis Summary
This project analyzed two distinct attack vectors:
1.  **Credential Harvesting (Microsoft Impersonation):** A high-risk attack failing all authentication protocols (SPF/DKIM/DMARC).
2.  **Authorized Spoofing (Crypto Allocation Scam):** A sophisticated attack that passed technical checks by using a compromised third-party mailing service.

## 💡 Key Takeaways
This task highlighted that **technical filters are not foolproof.** Even when an email passes SPF/DKIM checks, the content and intent must be scrutinized. Effective cybersecurity is a combination of robust systems and an informed, skeptical workforce.

---
**Author:** Denise Mutayi  
**Role:** Cybersecurity Intern  

