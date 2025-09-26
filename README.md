# Task 3: Vulnerability Scanning with Nessus & Nmap

This repository contains my report for Task 3 of the Elevate Labs Cybersecurity Internship. The objective was to perform a vulnerability scan on a local computer using a multi-tool approach to get a comprehensive security overview.

---

## 🛠️ Tools Used

I used a combination of two powerful tools for this assessment:
* **Tenable Nessus Essentials:** For a deep and detailed analysis of potential vulnerabilities and security misconfigurations.
* **Nmap Scripting Engine (NSE):** For a fast and efficient scan to check for common, known software exploits.

---

## 🔬 Key Finding: Patched vs. Vulnerable

This two-pronged assessment provided a crucial insight: a system can be fully patched but still be vulnerable due to insecure settings.

* **My Nmap Scan** came back "clean," confirming the machine was not vulnerable to the specific software exploits it checked for.
* **My Nessus Scan**, however, discovered a **Medium severity misconfiguration: "SMB Signing not required" (CVSS 5.3)**.

This primary finding highlights a weakness that could expose my machine to **Man-in-the-Middle (MitM) attacks** on the local network. Using both tools gave a more complete and realistic view of my system's security posture.

---

## 📄 How to View the Full Report

The complete, detailed vulnerability assessment report, including evidence from both scans and my remediation plan, can be found in the repository:
* **`Task-3_Vulnerability_Scan_Report.pdf`**
