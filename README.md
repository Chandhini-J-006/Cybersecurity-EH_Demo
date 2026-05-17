# DVWA VAPT Report 🔐

A professional Vulnerability Assessment & Penetration Testing (VAPT) report conducted on the DVWA (Damn Vulnerable Web Application) running inside the Metasploitable2 lab environment.

This project demonstrates practical web application security testing methodologies aligned with industry standards such as OWASP Top 10, OWASP ASVS, SANS, and NIST.

---

## 📌 Project Overview

This assessment focused on identifying security weaknesses within DVWA using both automated and manual penetration testing techniques.

The report highlights:
- Vulnerabilities discovered
- Exploitation techniques
- Risk assessment
- Security impact
- Remediation recommendations

### Key Objectives
- Perform web application penetration testing
- Identify exploitable vulnerabilities
- Assess risks using CVSS v3.1
- Demonstrate real-world attack scenarios
- Provide remediation strategies

---

## 🧪 Testing Environment

| Component | Details |
|---|---|
| Application | DVWA (Damn Vulnerable Web Application) |
| Environment | Metasploitable2 Virtual Machine |
| Backend Database | MySQL |
| Authentication | Form-Based Login |
| Platform | Kali Linux |
| Assessment Type | White-Box Penetration Testing |

---

## 🛠️ Tools Used

The following cybersecurity tools were used during the assessment:

- Burp Suite Professional
- SQLMap
- OWASP ZAP
- Nmap
- Kali Linux
- Custom Python Scripts

---

## 🔍 Scope of Assessment

The penetration test included:

- Information Gathering & Reconnaissance
- Authentication Testing
- Authorization Testing
- Session Management Security
- Business Logic Testing
- Input Validation Testing
- Data Transfer Security
- Configuration Management Testing

---

## 🚨 Major Vulnerability Identified

### SQL Injection Vulnerability

A critical SQL Injection flaw was discovered in the `id` parameter of DVWA.

### Impact
- Unauthorized database access
- Credential extraction
- Data manipulation
- Possible system compromise

### Example Payload
```sql
1' OR '1'='1
