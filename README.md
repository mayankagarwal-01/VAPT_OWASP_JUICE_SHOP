Overview

This repository contains a complete Web Application Vulnerability Assessment & Penetration Test (VAPT) conducted against the intentionally vulnerable application OWASP Juice Shop as part of a personal cybersecurity learning and research project. The assessment was performed in a controlled lab environment through TryHackMe.

The project focuses on identifying, exploiting, documenting, and understanding common web application vulnerabilities aligned with the OWASP Top 10 (2021) framework.

Project Objectives
Gain hands-on experience in web application penetration testing
Understand real-world attack vectors and exploitation techniques
Practice vulnerability reporting and remediation documentation
Explore OWASP Top 10 vulnerabilities in a legal lab environment
Develop skills in reconnaissance, exploitation, and post-exploitation activities

Assessment Information
Category	Details
Target Application	OWASP Juice Shop
Assessment Type	Black-box VAPT
Platform	TryHackMe Hosted VM
Year	2026
Environment	Legal / Educational Lab
Classification	Portfolio / Educational Use Only

Tools & Technologies Used
Burp Suite Community
Nmap
ffuf
Gobuster
Browser DevTools
beautifier.io
Usage Highlights
Tool	Purpose
Burp Suite	HTTP interception, SQLi, XSS, API testing
Nmap	Service and port enumeration
ffuf	Directory and endpoint fuzzing
Gobuster	Hidden directory discovery
DevTools	API analysis and source inspection

Vulnerabilities Exploited
ID	Vulnerability	Severity
F-01	SQL Injection – Admin Login Bypass	Critical
F-02	SQL Injection – User Enumeration	High
F-03	Broken Authentication / Brute Force	High
F-04	Sensitive Data Exposure	High
F-05	Broken Access Control	High
F-06	DOM / Reflected XSS	Medium
F-07	Insecure API Exposure	Medium
F-08	Hidden Route Discovery	Low

Key Skills Demonstrated
Web Application Penetration Testing
SQL Injection Exploitation
Authentication Bypass
IDOR & Broken Access Control Testing
XSS Payload Crafting
REST API Security Testing
Directory Enumeration & Fuzzing
Burp Suite Intruder/Reaper Usage
Security Reporting & Documentation

Methodology

The assessment followed a structured black-box testing approach:

Reconnaissance
Scanning & Enumeration
Exploitation
Post-Exploitation
Reporting & Remediation

Evidence & Screenshots

All proof-of-concept screenshots and captured evidence can be found inside the /images directory.

Evidence Categories
SQL Injection
Password Cracking & Reset
Restricted Document Access
Unauthorized Account Access
Restricted File Downloads
Privilege Escalation
IDOR Exploitation
DOM XSS
Persistent XSS

Repository Structure
OWASP-Juice-Shop-VAPT/
│
├── README.md
├── VAPT_OWASPJuiceShop_2026.pdf
├── VAPT_OWASPJuiceShop_2026.docx
├── images/
│   ├── 1.png
│   ├── 2.png
│   ├── ...
│   └── 29.png
└── tools-used.txt
OWASP Top 10 Coverage

This project covers multiple categories from the OWASP Top 10 (2021) including:

A01 – Broken Access Control
A02 – Cryptographic Failures
A03 – Injection
A05 – Security Misconfiguration
A07 – Authentication Failures

Learning Outcomes

Through this project, I developed practical knowledge of:

Web exploitation techniques
Vulnerability chaining
Security assessment workflows
Attack surface mapping
Secure coding principles
Risk prioritization and remediation

Disclaimer

This project was conducted strictly in a controlled and legal educational environment using intentionally vulnerable applications provided for cybersecurity training purposes.

No unauthorized systems or real-world targets were attacked.

References
OWASP Juice Shop
OWASP Top 10 (2021)
TryHackMe Room
Burp Suite Documentation
ffuf GitHub
Gobuster GitHub
SecLists Wordlists
