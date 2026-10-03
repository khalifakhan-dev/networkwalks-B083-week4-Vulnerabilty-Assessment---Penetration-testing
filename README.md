# Networkwalks-B083-week4-Vulnerabilty-Assessment---Penetration-testing
Vulnerability assessment and penetration testing of an authorized website. Black box penetration testing

# Mediroza General Hospital – Web Application Penetration Test

## Overview

This project documents an authorized web application penetration-testing exercise completed as part of the NetworkWalks cybersecurity training program.

The assessment was performed against the Mediroza General Hospital training environment using a black-box penetration-testing methodology.

## Objectives

The assessment focused on:

- Reconnaissance and service enumeration
- Web application enumeration
- Authentication testing
- SQL injection testing
- Access-control testing
- Sensitive file exposure
- PDF security analysis
- Database backup exposure
- Security recommendations

## Tools Used

- Kali Linux
- Nmap
- curl
- WhatWeb
- wafw00f
- WHOIS
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker

## Methodology

The assessment followed this general process:

1. Reconnaissance
2. Service enumeration
3. Web application discovery
4. Directory and endpoint enumeration
5. Authentication testing
6. SQL injection testing
7. Authentication bypass validation
8. Sensitive file analysis
9. PDF security analysis
10. Reporting and remediation recommendations

## Key Findings

### 1. SQL Injection Authentication Bypass
A SQL injection vulnerability was identified in the patient authentication functionality.

Successful exploitation resulted in authentication bypass and access to the patient portal.

### 2. Sensitive Patient Data Exposure
Following the authentication bypass, three confidential patient laboratory reports were accessible within the authorized training environment.

### 3. Publicly Accessible Database Backup
A database backup was discovered within a web-accessible directory.

The backup contained sensitive staff and shareholder information.

### 4. Directory Listing
Directory listing was enabled on several application directories, exposing application files and helping identify sensitive resources.

### 5. Username Enumeration
The patient login functionality revealed whether a supplied username existed through different authentication responses.

## Lessons Learned

This assessment helped me develop practical experience in:

- Thinking methodically during a penetration test
- Using reconnaissance to identify attack surfaces
- Understanding web application authentication
- Identifying SQL injection vulnerabilities
- Validating security findings
- Understanding the impact of information disclosure
- Documenting findings professionally
- Providing remediation recommendations

## Important Note

This assessment was conducted in an authorized educational environment as part of NetworkWalks training.

Sensitive information has intentionally been removed from this repository.

No patient records, passwords, credentials, database dumps, session cookies, personal identification information, or other confidential evidence are included.

## Disclaimer

This repository documents security testing performed in an authorized educational environment. The techniques described were not intended for unauthorized systems.
