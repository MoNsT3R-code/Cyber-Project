## Cyber-Project
### ⚠️ Ethical Disclaimer: All work in this repository was performed in a strictly controlled environment for academic and research purposes without targeting any real-world production systems. Cybersecurity must always be practiced responsibly and legally.

## CSCS321A — Advanced Web Security
This repository contains my complete coursework, execution methodologies, structural write-ups, and validation proof-of-concepts for the Advanced Web Security track. It features itemized solutions for 32 vulnerability testing targets compiled from the PortSwigger Web Security Academy ecosystem.

### 📍 Quick Navigation
* [🌐 Project Overview](#-project-overview)
* [📁 Repository Structure](#-repository-structure)
* [🎯 Lab Index (32 Labs)](#-lab-index)
* [📋 Lab-by-Lab Breakdown Template](#-comprehensive-32-lab-breakdown)
* [🧠 What I Learned](#-what-i-learned)

## 🌐 Project Overview
This project comprehensively documents my practical learning journey through 32 PortSwigger labs, systematically identifying, exploiting, and mitigating critical modern web-security vulnerabilities.

Every single lab portfolio entry maps out:

- The core logic or structural application breakdown.

- Clear concept mechanics of the targeted flaw.

- Reproducible step-by-step exploitation guidelines.

- Direct image proof captures confirming payload validation or key extractions.

- Clear architectural remediation advice.

## 📁 Repository Structure

```text
Cyber-Project/
│
├── README.md
├── CSCS321A_AdvancedWebSecurity_Report.pdf
└── screenshots/
    ├── lab01.png
    ├── lab02.png
    ├── ...
    └── lab32.png

```
---
## 🎯 Lab Index (32 Labs)

| Module Classification | Lab Identifiers & Focus Areas | Exploration Strategy |
| :--- | :--- | :--- |
| **1. SQL Injection** | Labs 01–05: Login Bypass, UNION Attacks, Hidden Data Retrieval, Blind (Conditional), Blind (Time-Based) | [SQLi Lab Section](#1-sql-injection) |
| **2. Authentication** | Labs 06–10: Username Enumeration, Broken Brute-Force, Password Reset Poisoning, 2FA Bypass, Weak Tokens | [Auth Lab Section](#2-authentication) |
| **3. Directory Traversal** | Labs 11–13: Basic Traversal, Nested Encoding, Filter Bypassing Sequences | [Traversal Lab Section](#3-directory-traversal) |
| **4. Access Control** | Labs 14–17: Unprotected Admin Panels, IDOR Profiles, Parameter Tampering, Forced Browsing | [Access Control Lab Section](#4-access-control) |
| **5. Cross-Site Scripting** | Labs 18–22: Reflected XSS, Stored XSS, DOM-Based Attacks, HTML Injection, Attribute Injection | [XSS Lab Section](#5-cross-site-scripting-xss) |
| **6. CSRF** | Labs 23–25: Basic CSRF, Token Bypass Flaws, Cookie-Based Session Tracking Flaws | [CSRF Lab Section](#6-csrf) |
| **7. File Upload** | Labs 26–28: Web Shell Uploads, MIME-Type Validation Bypass, Extension Filter Blacklist Circumvention | [File Upload Lab Section](#7-file-upload-vulnerabilities) |
| **8. SSRF & Advanced** | Labs 29–32: Basic SSRF, Open Redirect Chains, Web Cache Poisoning, Host Header Injection | [SSRF Lab Section](#8-ssrf--advanced-attacks) |
|...|...|
|...|...|
|**32....**|....|





## 🔍 Summary
A concise, high-level description outlining the target web application behavior and what architectural lesson this specific playground validates.

## 💡 Concept Explanation
- Explain the underlying application logic vulnerability or input validation oversight in clear, non-complex security concepts.

## 🚀 Solution Steps
- Reconnaissance: Intercepting the target transaction signatures via a local intercept tool proxy configuration.

- Boundary Testing: Injecting special character variations into input fields to parse structural application fault behaviors.

- Exploitation: Executing the final structured payload string to extract targeted administrative keys, bypass parameters, or gain access.

### 🖼️ Validation Verification Capture

```text
/screenshots/labXX.png
```
---

##🛡️ Key Defenses & Remediation

- Flaw Root Cause: Identify the exact design pattern failure (e.g., passing dynamic string parameters straight into an unparameterized interpreter engine).

- Fix Action: Enforce secure developer strategies like strong whitelisting filters, input normalization wrappers, or explicit parameterization frameworks.

---

## 🧠 What I Learned

Across all 32 distinct PortSwigger lab execution maps, I have successfully hardened my technical engineering knowledge regarding:

- Real-World Exploitation Lifecycles: Understanding exactly how software engineering mistakes translate directly into malicious compromise targets in live production infrastructure.

- Deep Traffic Inspection: Analyzing live network transaction buffers down to raw context parameters, processing states, character encodings, and cookies.

- Filter Deflection Frameworks: Testing how naive blacklists and text filters shatter when subjected to layered encoding variants or payload structural modifications.

- Industry-Standard Security Reporting: Mastering the art of translating raw memory dumps, exploitation payloads, and graphical evidence captures into professional, actionable executive remediation logs.
