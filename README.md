# Penetration Testing Assignment Report

A comprehensive penetration testing report for the "Development and Safety of Information Systems" course (2025-2026) at AUEB.

## Overview

This report documents the security assessment of four vulnerable web applications, following a structured penetration testing methodology across the complete attack lifecycle.

## Target Applications

1. **OWASP Security Shepherd** - Structured security training framework
2. **OWASP Juice Shop** - Modern vulnerable e-commerce application
3. **DVWA** (Damn Vulnerable Web App) - Classic penetration testing platform
4. **TryHackMe Mr Robot CTF** - Real-world scenario CTF challenge

## Methodology

Each assessment follows a standardized four-phase penetration testing approach:

### Phase 1: Reconnaissance
- Network discovery and mapping
- Port scanning and service enumeration
- Web application discovery and fingerprinting

### Phase 2: Vulnerability Assessment
- Automated vulnerability scanning (OWASP ZAP, Nessus)
- Manual vulnerability testing
- Risk classification and prioritization

### Phase 3: Exploitation
- Manual exploitation of identified vulnerabilities
- Proof-of-concepts (PoCs)
- Impact assessment

### Phase 4: Post-Exploitation & Remediation
- Privilege escalation techniques
- Data extraction and analysis
- Remediation recommendations
- Security hardening suggestions

## Key Findings

### Web Application Vulnerabilities

- **SQL Injection** - UNION-based, Boolean-based, Time-based variants
- **Cross-Site Scripting (XSS)** - Reflected and Stored XSS attacks
- **Authentication Bypass** - Credential manipulation and JWT exploitation
- **Path Traversal & LFI** - Local File Inclusion and directory traversal
- **Unrestricted File Upload** - Remote Code Execution via file uploads
- **Business Logic Bypass** - Application logic manipulation
- **Cryptographic Weaknesses** - Insecure hashing and encryption practices
- **Sensitive Data Exposure** - Unauthorized access to confidential information

## Tools & Technologies Used

- **Reconnaissance**: Nmap, Burp Suite, Web browsers
- **Scanning**: OWASP ZAP, Nessus, WPScan
- **Exploitation**: Burp Suite, SQLmap, Manual testing
- **Analysis**: Python scripts, Custom tools
- **Reporting**: Detailed documentation with screenshots and PoCs

## Report Structure

```
├── OWASP Security Shepherd
│   ├── Executive Summary
│   ├── Reconnaissance Phase
│   ├── Vulnerability Assessment
│   ├── Exploitation & Findings
│   └── Remediation Recommendations
├── OWASP Juice Shop
│   ├── Executive Summary
│   ├── Reconnaissance Phase
│   ├── Vulnerability Assessment
│   ├── Exploitation & Findings
│   └── Remediation Recommendations
├── DVWA (Damn Vulnerable Web App)
│   ├── Executive Summary
│   ├── Reconnaissance Phase
│   ├── Vulnerability Assessment
│   ├── Exploitation & Findings
│   └── Remediation Recommendations
└── TryHackMe Mr Robot CTF
    ├── Executive Summary
    ├── Reconnaissance Phase
    ├── Vulnerability Assessment
    ├── Exploitation & Findings
    └── Remediation Recommendations
```

## Key Learning Outcomes

- Practical application of OWASP Top 10 vulnerabilities
- Hands-on penetration testing methodologies
- Vulnerability assessment and exploitation techniques
- Report writing and documentation best practices
- Security remediation and hardening strategies



## Course Information

- **Course**: Development and Safety of Information Systems
- **Institution**: Athens University of Economics and Business (AUEB)
- **Academic Year**: 2025-2026

## Disclaimer

This report documents vulnerabilities found in deliberately vulnerable applications for educational purposes. The methodologies and techniques described are intended for authorized security testing only. Unauthorized access to computer systems is illegal.

## License

Educational material - For academic use only.
