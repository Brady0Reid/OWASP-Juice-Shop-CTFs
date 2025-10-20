# OWASP Juice Shop — CTF Writeups  
**Author:** Brady Reid  
**Course:** ITT-340 — Penetration Testing (Educational lab)  
**Updated:** 2024-12-15

---

[![Live Site](https://img.shields.io/badge/Live%20Report-GitHub%20Pages-blue?logo=github)](https://brady0reid.github.io/Pen-Test-Report/)

> Collection of challenge writeups, findings, and remediation guidance based on hands-on OWASP Juice Shop CTF exercises. All testing was done in an isolated lab environment for educational purposes.

---

## Quick links
- 🔗 **Live HTML report (GitHub Pages):** https://brady0reid.github.io/Pen-Test-Report/  
- 📁 **Repository:** `./` (this repo)  
- ✉️ **Contact:** bradycreid@protonmail.com  
- 🔒 **Disclaimer:** Lab-only work. Do **not** use techniques on systems you do not own or have permission to test.

---

## Summary
This repo contains writeups for several OWASP Juice Shop Capture-The-Flag (CTF) challenges. Each writeup describes the objective, outcome, root cause, and recommended remediations. Topics covered include:

- Improper input validation (ratings / zero stars)  
- Confidential document exposure (sensitive file access)  
- DOM XSS and classic Stored XSS  
- Error handling / information leakage  
- Missing encoding and injection vectors  
- Unvalidated redirects (outdated whitelist)  
- Repetitive registration, admin login bypass (SQL injection)  
- Appendix: screenshots, request/response artifacts, and supporting diagrams

---

## Table of Contents
1. [Executive Guidelines & Versioning](#guidelines--versioning)  
2. [Improper Input Validation — Zero Stars](#improper-input-validation)  
3. [Confidential Document Exposure](#confidential-document-exposure)  
4. [DOM XSS](#dom-xss)  
5. [Error Handling (Security Misconfiguration)](#error-handling)  
6. [Missing Encoding](#missing-encoding)  
7. [Outdated Whitelist (Unvalidated Redirects)](#outdated-whitelist)  
8. [Repetitive Registration](#repetitive-registration)  
9. [Login Admin (Injection)](#login-admin)  
10. [Classic Stored XSS](#classic-stored-xss)  
11. [Appendix & Screenshots](#appendix--screenshots)

> See the full live report for detailed screenshots and the Appendix images.

---

## How to view
1. Ensure the repo contains `index.html` at the root and the appendix screenshot files (AppendixA.png … AppendixH.png).  
2. Add a blank file named `.nojekyll` in the repo root to ensure raw HTML is served.  
3. Enable GitHub Pages (Settings → Pages → Source: `main` branch, folder: `/ (root)` ).  
4. Visit the **Live HTML report** link above.

---

## Example remediation checklist (high-priority)
- Patch and replace end-of-life systems.  
- Implement strict server-side validation and schema checks.  
- Sanitize and encode all untrusted content (use DOMPurify, template auto-escaping).  
- Deploy Content Security Policy (CSP) to restrict script execution.  
- Disable verbose error output in production; log errors centrally (SIEM).  
- Enforce unique constraints and rate-limiting for accounts.  
- Use parameterized queries / ORM for DB access; apply least privilege.

---

## Appendix (files in repo)
- `AppendixA.png` — Juice Shop console / challenge solved  
- `AppendixB.png` — Blockchain/payment artifact screenshot  
- `AppendixC.png` — DOM inspection / photo wall  
- `AppendixD.png` — Burp request/response screenshot  
- `AppendixE.png` — DOM XSS iframe example  
- `AppendixF.png` — Exploit request/response details  
- `AppendixG.png` — Customer feedback form screenshot  
- `AppendixH.png` — Burp intercept JSON payload

---

## Notes & next steps
- I recommend moving any **sensitive logs** or command-level exploit notes into a private repo or instructor-only folder.  
- If you want, I can:
  - Place the Appendix images inline next to their corresponding challenge sections in `index.html`.  
  - Generate a printable PDF of the report.  
  - Add badges (tools used) and a short contributor section.

---

## Contact
Brady Reid — bradycreid@protonmail.com  
LinkedIn: https://www.linkedin.com/in/brady-reidin

---

**License:** This repository is for educational use only. Reuse or reproduction of offensive techniques is prohibited outside authorized environments.
