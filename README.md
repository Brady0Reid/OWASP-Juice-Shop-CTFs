# 🧠 OWASP Juice Shop — CTF Report  
**Author:** Brady Reid  
**Course:** ITT-340 — Penetration Testing & Ethical Hacking  
**Date:** December 2024  
**Environment:** Controlled Educational Sandbox  

[![View Live Report](https://img.shields.io/badge/View_Live_Report-Click_Here-blue?logo=githubpages&style=for-the-badge)](https://brady0reid.github.io/OWASP-Juice-Shop-CTF/)
[![Made with Kali Linux](https://img.shields.io/badge/Made%20with-Kali%20Linux-2684FF?logo=kalilinux&logoColor=white)]()
[![Uses OWASP Juice Shop](https://img.shields.io/badge/Platform-OWASP%20Juice%20Shop-orange?logo=owasp)]()
[![Status](https://img.shields.io/badge/Status-Completed-success)]()

---

## 📘 Overview
This repository documents a series of **OWASP Juice Shop Capture-the-Flag (CTF)** challenges performed as part of the **ITT-340 Penetration Testing** course at Grand Canyon University.  
The objective was to exploit web application vulnerabilities in a legal, sandboxed environment and produce structured technical documentation of each finding, including the root cause and recommended mitigation strategies.

---

## 🔎 Project Objectives
- Identify, exploit, and document vulnerabilities in **OWASP Juice Shop**.  
- Demonstrate key penetration testing methodologies (reconnaissance, exploitation, remediation).  
- Apply ethical hacking practices within a controlled lab environment.  
- Produce a professional, version-controlled penetration test report for academic assessment.

---

## 🧩 Challenge Writeups
| # | Challenge | Category | Exploit Type | Status |
|---|------------|-----------|---------------|---------|
| 1 | Improper Input Validation | Input Validation | Zero-star rating bypass | ✅ Solved |
| 2 | Confidential Document Exposure | Sensitive Data | Unauthorized file access | ✅ Solved |
| 3 | DOM XSS | Cross-Site Scripting | DOM-based payload | ✅ Solved |
| 4 | Error Handling | Security Misconfiguration | Stack trace leakage | ✅ Solved |
| 5 | Missing Encoding | Input Sanitization | Unescaped payload injection | ✅ Solved |
| 6 | Outdated Whitelist | Unvalidated Redirects | Redirect bypass | ✅ Solved |
| 7 | Repetitive Registration | Input Validation | Duplicate account creation | ✅ Solved |
| 8 | Login Admin | Injection | SQLi login bypass | ✅ Solved |
| 9 | Classic Stored XSS | XSS | Persistent JavaScript injection | ✅ Solved |

---

## 🧾 Version Control
| Version | Date | Author | Change Summary |
|----------|------|---------|----------------|
| 1.0 | 12/15/2024 | Brady Reid | Initial writeup – Improper Input Validation |
| 1.2 | 12/15/2024 | Brady Reid | Added Confidential Document Exposure |
| 1.3 | 12/15/2024 | Brady Reid | Added DOM XSS |
| 1.4 | 12/15/2024 | Brady Reid | Added Error Handling findings |
| 1.5 | 12/15/2024 | Brady Reid | Added Missing Encoding |
| 2.0 | 12/15/2024 | Brady Reid | Added Outdated Whitelist redirect analysis |
| 2.3 | 12/15/2024 | Brady Reid | Added Repetitive Registration |
| 2.4 | 12/15/2024 | Brady Reid | Added Login Admin injection |
| 2.5 | 12/15/2024 | Brady Reid | Added Classic Stored XSS and Appendices |

---

## 🧮 Tools & Technologies
| Category | Tools Used |
|-----------|------------|
| **Operating System** | Kali Linux 2024.2 |
| **Web Exploitation** | OWASP Juice Shop, Burp Suite, Firefox DevTools |
| **Reconnaissance** | Nmap, Whois, Wappalyzer |
| **Exploitation** | Burp Intruder, Repeater, XSS payloads |
| **Reporting** | Markdown, HTML5, GitHub Pages |

---

## 📸 Appendix (Screenshots)
- Appendix A → Juice Shop dashboard & solved challenge proof  
- Appendix B → Blockchain transaction (redirect validation)  
- Appendix C → DOM Photo Wall inspection  
- Appendix D → Burp Suite HTTP request/response  
- Appendix E → DOM XSS iframe payload  
- Appendix F → Exploit response capture  
- Appendix G → Feedback form injection  
- Appendix H → JSON payload in Burp Repeater  

All appendix files are stored in the repo root for reference.  

---

## 🔐 Ethical Use & Disclaimer
This documentation is for **educational and authorized penetration testing only.**  
All testing occurred within a private sandbox environment (OWASP Juice Shop).  
No production or third-party systems were targeted.  

**Unauthorized access or exploitation of systems is illegal and unethical.**  
This report is designed to **teach responsible cybersecurity practices.**

---

## 👨‍💻 Author
**Brady C. Reid**  
Grand Canyon University — B.S. Information Technology & Cybersecurity  
📧 **bradycreid@protonmail.com**  
🔗 [LinkedIn](https://www.linkedin.com/in/brady-reidin)  
💻 [GitHub Portfolio](https://github.com/Brady0Reid)

---

### 🌐 Live Demo  
👉 **Visit the full interactive report:**  
📄 [https://brady0reid.github.io/OWASP-Juice-Shop-CTF/](https://brady0reid.github.io/OWASP-Juice-Shop-CTF/)

---

**© 2025 Brady C. Reid — Educational Use Only**
