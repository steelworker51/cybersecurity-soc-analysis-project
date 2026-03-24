
# Cybersecurity SOC Analysis Project

## Overview

This project simulates a full cybersecurity assessment combining both offensive (Red Team) and defensive (Blue Team) techniques.

The objective was to identify, analyze, and mitigate security risks using real-world methodologies.

---

## Key Features

* Network reconnaissance using Nmap
* Vulnerability discovery and exploitation (TryHackMe Vulnversity)
* Privilege escalation techniques
* SIEM-based log analysis and detection
* Threat intelligence correlation
* MITRE ATT&CK technique mapping
* Risk scoring and remediation planning
* Detection rule automation
* Attack path visualization

---

## Tools & Technologies

* Python (Google Colab / Jupyter Notebook)
* Nmap
* TryHackMe Labs
* SIEM Log Analysis
* Pandas
* NetworkX (graph visualization)

---

## Key Findings

* Critical file upload vulnerability leading to remote code execution
* Privilege escalation via misconfigured SUID binary
* Brute-force authentication activity detected
* Suspicious outbound connections identified via SIEM
* Multiple attack paths to full system compromise

---

## Project Structure

* `notebook.ipynb` → Full analysis
* `report.pdf` → Executive report
* `*.csv` → Data exports
* `security_assessment.json` → Structured findings

---

## MITRE ATT&CK Coverage

The project maps detected behaviors to MITRE ATT&CK techniques including:

* T1595 – Active Scanning
* T1190 – Exploit Public-Facing Application
* T1059 – Command Execution
* T1068 – Privilege Escalation
* T1566 – Phishing

---

## Outcome

This project demonstrates a full security operations workflow:

Recon → Exploitation → Detection → Analysis → Remediation

It reflects real-world SOC and penetration testing practices.

---

## Author

Dale Murphy
