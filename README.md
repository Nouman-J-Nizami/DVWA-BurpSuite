# DVWA Login Interception and HTTP Request Analysis with Burp Suite

## Overview

This project demonstrates the use of Burp Suite to intercept and analyze HTTP authentication requests within a controlled DVWA (Damn Vulnerable Web Application) environment.

The exercise focused on understanding how login requests are transmitted, identifying sensitive parameters within HTTP POST requests, and evaluating how different application security levels affect the attack surface and visibility of authentication data.

---

## Environment

- Kali Linux
- DVWA (Damn Vulnerable Web Application)
- Apache2
- MySQL / MariaDB
- Burp Suite Community Edition

---

## Objectives

- Configure and access a vulnerable web application environment
- Intercept HTTP authentication requests using Burp Suite
- Analyze login parameters and server responses
- Use Burp Repeater for request inspection
- Compare application behavior across multiple security levels
- Understand the impact of server-side security controls

---

## Activities Performed

### DVWA Configuration
- Database initialization and setup
- Authentication using default credentials
- Security level configuration

### Burp Suite Analysis
- Proxy configuration with Intercept enabled
- Login request interception
- HTTP POST request inspection
- Authentication parameter analysis
- Request forwarding to Repeater
- Response validation and error analysis

### Security Level Comparison
- LOW security analysis
- MEDIUM security analysis
- HIGH security analysis
- Evaluation of how security controls influence application behavior and information disclosure

---

## Tools and Technologies

- Burp Suite
- DVWA
- Apache2
- MySQL
- Kali Linux
- HTTP Protocol Analysis

---

## Skills Demonstrated

- Web Application Security Testing
- HTTP Request Analysis
- Authentication Workflow Analysis
- Burp Suite Proxy Usage
- Burp Repeater Operations
- Web Security Assessment
- Security Control Evaluation
- Vulnerability Analysis

---

## Key Findings

The project demonstrated how web application authentication requests can be intercepted and analyzed using Burp Suite. It also highlighted how increasing security controls on the server side reduces information exposure and decreases the effectiveness of common reconnaissance and analysis techniques.

The comparison between Low, Medium, and High security configurations provided practical insight into the relationship between application hardening and attack surface reduction.

---

## Author

**Nouman Javed Nizami**

Cybersecurity Analyst Student – Epicode
