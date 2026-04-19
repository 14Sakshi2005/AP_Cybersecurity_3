# Security Testing Report

## Objective
Identify and exploit OWASP Top 10 vulnerabilities in DVWA.

---

## 1. SQL Injection
Extracted usernames and passwords using SQL payloads.  
Mitigation: Prepared Statements, parameterized queries.

---

## 2. Cross-Site Scripting (XSS)
Executed scripts via stored and reflected inputs.  
Mitigation: Input validation, output encoding, CSP.

---

## 3. CSRF
Performed unauthorized password change using forged request.  
Mitigation: CSRF tokens, SameSite cookies.

---

## 4. File Inclusion
Accessed sensitive files using LFI/RFI.  
Mitigation: Input validation, file whitelisting.

---

## 5. Burp Suite Testing
Intercepted and modified HTTP requests.  
Used Intruder for fuzzing.

---

## 6. Security Headers
Analyzed and implemented secure HTTP headers.

---

## Conclusion
This lab demonstrated how common vulnerabilities can be exploited and mitigated using secure practices.
