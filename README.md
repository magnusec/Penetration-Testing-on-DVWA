

# Penetration-Testing-on-DVWA

This repository contains a comprehensive **web application security assessment and threat mapping report** for **DVWA (Damn Vulnerable Web Application)**.

DVWA is an intentionally vulnerable web application designed for learning and practicing web application security testing. This project simulates **real-world attack scenarios** aligned with the **OWASP Top 10 vulnerabilities** and demonstrates how common flaws are identified, exploited, analyzed, and mitigated in a controlled environment.

---

## Vulnerabilities




| # | Vulnerability | Severity | Impact  | Mitigation  |
|---|--------------|----------|----------------|-------------------|
| 1 | SQL Injection | High | Allows attackers to bypass authentication, extract sensitive database data, and manipulate backend records. | Use prepared statements, parameterized queries, and strict input validation. |
| 2 | Blind SQL Injection | High | Enables silent extraction of sensitive database information through response timing without visible errors. | Implement secure query handling, parameterized queries, and monitor abnormal response delays. |
| 3 | Stored Cross-Site Scripting (XSS) | Medium | Leads to persistent execution of malicious scripts, resulting in session hijacking and credential theft. | Sanitize user input and apply proper output encoding before rendering content. |
| 4 | Reflected Cross-Site Scripting (XSS) | Medium | Allows execution of malicious scripts via crafted links, enabling phishing and session compromise. | Encode all reflected input and validate request parameters strictly. |
| 5 | DOM-Based Cross-Site Scripting (XSS) | Medium | Causes client-side script execution, leading to browser-based session and data compromise. | Avoid unsafe JavaScript methods and sanitize input before DOM insertion. |
| 6 | Cross-Site Request Forgery (CSRF) | Low| Forces authenticated users to perform unauthorized actions without their knowledge. | Implement anti-CSRF tokens and validate request origin and intent. |


---

## 📘 What’s Inside the Report?

The detailed **DVWA security assessment report** included in this repository covers:

- ✅ Introduction & Executive Summary  
- ✅ Testing Tools and Methodology  
- ✅ Technical Breakdown of Each Vulnerability  
- ✅ Proof of Concept (PoC) with Payloads  
- ✅ Real-World Attacker Scenarios  
- ✅ Risk Analysis & Impact Assessment  
- ✅ Mitigation Strategies and Recommendations  
- ✅ Conclusion and Security Takeaways  

---

## 🎯 Purpose of This Project

This project is intended for:
- Cybersecurity students
- Understanding OWASP Top 10 vulnerabilities
- Penetration testing and VAPT practice    
- Academic reference and security portfolios  

All testing was performed in a **controlled lab environment** on intentionally vulnerable software.

---

⚠️ **Disclaimer:**  
This project is strictly for educational purposes. The techniques demonstrated here should only be applied to systems you own or have explicit permission to test.
