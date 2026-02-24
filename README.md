# FUTURE_CS_01 - Vulnerability Assessment Report for a Live Website (Future Interns Cyber Security Internship - Task 1)

## 📌 Project Overview
This project presents a vulnerability assessment conducted on a live test website using non-intrusive and passive security testing techniques. The goal was to identify common web application security weaknesses and provide practical remediation steps.

## 🌐 Website Tested
- http://testphp.vulnweb.com 

## 🔍 Scope of Assessment
- Publicly accessible web pages
- Passive vulnerability analysis only
- No exploitation or intrusive testing
- Analysis of HTTP headers and configurations
- Server and technology information disclosure
- Cookie security configurations
- Identification of exposed services and common vulnerabilities

## 🛠️ Tools Used
- Nmap → Network scanning (open ports)
- OWASP ZAP → Passive vulnerability scanning
- Browser Developer Tools → Header and response analysis

## Repository Structure
- `Vulnerability_Assessment_Report.pdf` → Full assessment report
- `Evidence/` → Supporting screenshots and outputs:
  - `headers.png` → HTTP response headers (DevTools)
  - `zap.png` → OWASP ZAP findings
  - `nmap.png` → Nmap scan results

## Findings Summary
- Missing security headers
- Server information disclosure
- Insecure cookie configuration
- Weak HTTPS/TLS configuration
- Open port exposure

## ⚠️ Disclaimer
This project was conducted for educational purposes only. All testing was passive and non-intrusive on a publicly available test website.

## 📚 References
- OWASP Top 10
- OWASP ZAP Documentation
- Nmap Official Documentation
