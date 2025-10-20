# 🧠 OWASP Juice Shop — CTF Report  
**Author:** Brady Reid  
**Course:** ITT-340 — Penetration Testing & Ethical Hacking  
**Date:** December 2024  
**Environment:** Controlled Educational Sandbox  

[![View Live Report](https://img.shields.io/badge/View_Live_Report-Click_Here-blue?logo=githubpages&style=for-the-badge)](https://brady0reid.github.io/OWASP-Juice-Shop-CTFs/)
[![Made with Kali Linux](https://img.shields.io/badge/Made%20with-Kali%20Linux-2684FF?logo=kalilinux&logoColor=white)]()
[![Uses OWASP Juice Shop](https://img.shields.io/badge/Platform-OWASP%20Juice%20Shop-orange?logo=owasp)]()
[![Status](https://img.shields.io/badge/Status-Completed-success)]()

---

## 📘 Overview
This repository documents a series of **OWASP Juice Shop Capture-the-Flag (CTF)** challenges completed as part of the **ITT-340 Penetration Testing** course at Grand Canyon University.  
The objective was to exploit web application vulnerabilities in a sandboxed environment and produce structured, professional documentation of findings and remediations.

---

## 🔎 Project Objectives
- Identify, exploit, and document vulnerabilities in OWASP Juice Shop.  
- Demonstrate end-to-end testing lifecycle (recon → exploit → report).  
- Apply ethical hacking techniques responsibly.  
- Produce a polished academic deliverable demonstrating professional reporting standards.

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
| **OS** | Kali Linux 2024.2 |
| **Platform** | OWASP Juice Shop |
| **Scanning / Exploitation** | Burp Suite, Nmap, Firefox DevTools |
| **Analysis / Reporting** | Markdown, HTML5, GitHub Pages |

---

## 📸 Appendix
Appendix A–H contain screenshots and supporting diagrams:
- A → Dashboard / solved challenge  
- B → Blockchain artifact  
- C → DOM inspection  
- D → Burp request/response  
- E → DOM XSS iframe  
- F → Exploit capture  
- G → Feedback form  
- H → JSON payload  

---

## 🔐 Disclaimer
All tests were conducted ethically in a **controlled educational environment** using **OWASP Juice Shop**.  
No real-world systems or production data were involved.

> Unauthorized penetration testing or exploitation is illegal and unethical.

---

## 👨‍💻 Author
**Brady D. Reid**  
Grand Canyon University — B.S. Information Technology & Cybersecurity  
📧 **bradycreid@protonmail.com**  
🔗 [LinkedIn](https://www.linkedin.com/in/brady-reidin)  
💻 [GitHub Portfolio](https://github.com/Brady0Reid)

---

### 🌐 Live Report
👉 View the full HTML report:  
**[https://brady0reid.github.io/OWASP-Juice-Shop-CTFs/](https://brady0reid.github.io/OWASP-Juice-Shop-CTFs/)**

---

**© 2025 Brady C. Reid — Educational Use Only**
