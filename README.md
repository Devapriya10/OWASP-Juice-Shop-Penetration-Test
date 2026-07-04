# OWASP Juice Shop Penetration Test

## 📌 Project Overview

This project demonstrates a **manual web application penetration test** performed against the intentionally vulnerable **OWASP Juice Shop** application in a controlled laboratory environment.

The assessment focused on identifying and validating common web application vulnerabilities based on the **OWASP Top 10** using industry-standard penetration testing methodologies. Testing was conducted using **Burp Suite Professional**, **Kali Linux**, and **Mozilla Firefox**.

---

## 🎯 Objectives

The primary objectives of this project were:

- Identify common web application vulnerabilities
- Assess authentication and authorization mechanisms
- Evaluate input validation
- Identify security misconfigurations
- Document findings with supporting evidence
- Provide remediation recommendations

---

## 🖥️ Testing Environment

| Component | Details |
|----------|---------|
| Operating System | Kali Linux |
| Browser | Mozilla Firefox |
| Intercepting Proxy | Burp Suite Professional |
| Deployment | Docker |
| Target Application | OWASP Juice Shop |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Burp Suite Professional | HTTP interception, request manipulation, and vulnerability validation |
| Kali Linux | Penetration testing platform |
| Mozilla Firefox | Web browser |
| Docker | Hosting OWASP Juice Shop locally |

---

## 🔍 Methodology

The assessment followed a structured penetration testing approach:

1. Reconnaissance
2. Application Exploration
3. HTTP Request Interception
4. Authentication Testing
5. Authorization Testing
6. Input Validation Testing
7. Vulnerability Verification
8. Documentation and Reporting

---

## 📊 Findings Summary

| Finding | Severity | Status |
|---------|----------|--------|
| Login Admin | Critical | Verified |
| DOM Cross-Site Scripting (XSS) | High | Verified |
| Reset Jim Password | High | Verified |
| Forgotten Developer Backup | High | Verified |
| Five-Star Feedback | Medium | Verified |
| Poison Null Byte | Medium | Verified |
| Error Handling | Low | Verified |
| Privacy Policy Review | Informational | Verified |

---

## 📈 Risk Distribution

| Severity | Count |
|----------|------:|
| Critical | 1 |
| High | 3 |
| Medium | 2 |
| Low | 1 |
| Informational | 1 |

---

## 💻 Skills Demonstrated

- Web Application Penetration Testing
- HTTP Request Analysis
- Authentication Testing
- Authorization Testing
- Cross-Site Scripting (XSS) Testing
- Security Misconfiguration Testing
- Information Disclosure Testing
- Security Documentation
- Technical Report Writing

---

## 📂 Repository Structure

```
OWASP-Juice-Shop-Penetration-Test/

├── README.md
├── Report/
│   └── Web_Application_Penetration_Test_Report.pdf
├── Screenshots/
│   ├── DOM_XSS.pdf
│   ├── Login_Admin.pdf
│   ├── Reset_Jim_Password.pdf
│   ├── Forgotten_Backup.pdf
│   ├── Five_Star_Feedback.pdf
│   ├── Poison_Null_Byte.pdf
│   ├── Error_Handling.pdf
│   └── Privacy_Policy.pdf
├── Tools/
│   └── Tools_Used.md
```

---

## 📄 Report

The complete penetration testing report is available in the **Report** folder. It includes:

- Executive Summary
- Testing Methodology
- Detailed Findings
- Risk Ratings
- Screenshots
- Remediation Recommendations
- Conclusion

---

## ⚠️ Disclaimer

This project was conducted **only against the intentionally vulnerable OWASP Juice Shop application** within a controlled local environment for educational and portfolio purposes. No unauthorized testing was performed against production systems or third-party applications.

---

## 👩‍💻 Author

**Deva Priya**

Cybersecurity Enthusiast

LinkedIn: *www.linkedin.com/in/deva-priya-440052229*

Email: *devapriyaunni7@gmail.com*
