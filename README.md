# FUTURE_CS_01 - Vulnerability Assessment Report for a Live Website (Future Interns Cyber Security Internship - Task 1)

## Website Tested
- http://testphp.vulnweb.com 

## Scope of Assessment
- Passive vulnerability analysis only
- No exploitation or intrusive testing
- Analysis of HTTP headers and configurations
- Identification of exposed services and common vulnerabilities

## Tools Used
- Nmap
- OWASP ZAP (Passive Scan)
- Browser Developer Tools

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

## Disclaimer
This assessment was conducted using passive techniques only.  
No exploitation or harmful actions were performed.
