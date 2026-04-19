#  OWASP Top 10 Vulnerability Lab – Cybersecurity Task 3

> Hands-on exploitation and mitigation of real-world web vulnerabilities using DVWA & Kali Linux.

![Domain](https://img.shields.io/badge/Domain-Cybersecurity-blue)
![Tools](https://img.shields.io/badge/Tools-Kali%20Linux%20%7C%20DVWA-red)
![Status](https://img.shields.io/badge/Status-Completed-success)


##  Overview
This project demonstrates practical exploitation of **OWASP Top 10 vulnerabilities** in a controlled lab environment.

Each vulnerability is:
- Exploited step-by-step
- Documented with screenshots
- Secured using mitigation techniques
  

##  Skills Acquired
- Web Application Penetration Testing
- Vulnerability Assessment
- Secure Coding Practices
- Burp Suite Usage
- HTTP Security Hardening


##  Tools Used
- Kali Linux
- DVWA
- Burp Suite
- Apache Server
- Browser DevTools


###  Vulnerability Analysis and Exploitation

1. SQL Injection (Task 1)
   - Vulnerability: SQL Injection via User ID field.
   - Screenshot: SQL Injection
   <img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/7e3d6dee-785e-4f7b-a310-688d6772570e" />

2. Cross-Site Scripting (Task 2)
   - Vulnerability: Reflected and Stored XSS.
   - Screenshot: XSS
  <img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/f40cd2b8-f7ab-449d-9e34-c01978e422ca" />
     
3. CSRF (Task 3)
   - Vulnerability: Cross-Site Request Forgery.
   - Screenshot: CSRF
     <img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/ea9e4e54-73f6-43f2-b5a6-830c9d6d660a" />

4. File Inclusion (Task 4)
   - Vulnerability: Local File Inclusion (LFI).
   - Screenshot: LFI
     <img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/45a01715-75f5-492d-9bb0-67148fd20b09" />

5. Burp Suite Intercept (Task 5A)
   - Vulnerability: Man-in-the-Middle susceptibility.
   - Screenshot: Burp Intercept
     <img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/7a610b36-0935-45a2-a1f5-09e62b0872f9" />

6. Burp Suite Fuzzing (Task 5B)
   - Vulnerability: Brute-force weakness.
   - Screenshot: Burp Fuzzing
     <img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/0cdc0043-1137-471a-bf84-bda9d3c29d2a" />

7. Security Headers (Task 6)
   - Analysis: Missing critical HTTP security headers.
   - Screenshot: Security Headers
     <img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/34917175-37a5-447e-8837-64bec46ac532" />

## Key Learnings
- Small vulnerabilities can lead to full system compromise
- Input validation is critical
- Security must be implemented at every layer
