# Penetration-Testing-on-DVWA


# 🛡️ Web Application Threat Report: DVWA

This repository contains a comprehensive **web application security assessment and threat mapping report** for **DVWA (Damn Vulnerable Web Application)**.

DVWA is an intentionally vulnerable web application designed for learning and practicing web application security testing. This project simulates **real-world attack scenarios** aligned with the **OWASP Top 10 vulnerabilities** and demonstrates how common flaws are identified, exploited, analyzed, and mitigated in a controlled environment.

---

## 🕵️‍♂️ Identified Vulnerabilities

### 🔐 DVWA Vulnerabilities

| # | Vulnerability | Affected URL | Severity | Description |
|---|--------------|--------------|----------|-------------|
| 1 | SQL Injection | /vulnerabilities/sqli/ | High | Allows attackers to manipulate backend SQL queries and extract sensitive database data. |
| 2 | Blind SQL Injection | /vulnerabilities/sqli_blind/ | High | Data is inferred through server behavior and response timing without visible output. |
| 3 | Stored Cross-Site Scripting (XSS) | /vulnerabilities/xss_stored/ | Medium | Malicious scripts are stored on the server and executed for all users accessing the page. |
| 4 | Reflected Cross-Site Scripting (XSS) | /vulnerabilities/xss_reflected/ | Medium | Injected scripts are reflected in server responses and executed in the victim’s browser. |
| 5 | DOM-Based Cross-Site Scripting (XSS) | /vulnerabilities/xss_d/ | Medium | Client-side JavaScript manipulation allows execution of malicious scripts in the DOM. |
| 6 | Cross-Site Request Forgery (CSRF) | /vulnerabilities/csrf/ | Low–Medium | Forces authenticated users to perform unauthorized actions without their consent. |

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
- Cybersecurity students and learners  
- Penetration testing and VAPT practice  
- Understanding OWASP Top 10 vulnerabilities  
- Academic submissions and security portfolios  

All testing was performed in a **controlled lab environment** on intentionally vulnerable software.

---

⚠️ **Disclaimer:**  
This project is strictly for educational purposes. The techniques demonstrated here should only be applied to systems you own or have explicit permission to test.
