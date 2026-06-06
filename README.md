# DVWA + SafeLine WAF Cybersecurity Homelab

## Overview

This project demonstrates the deployment of DVWA (Damn Vulnerable Web Application) behind SafeLine WAF in a controlled cybersecurity homelab environment.

The objective was to simulate web application attacks and validate SafeLine's detection and prevention capabilities.

---

## Technologies Used

* Ubuntu Server
* Kali Linux
* VirtualBox
* DVWA
* Apache2
* MySQL
* Docker
* SafeLine WAF
* SSL/TLS

---

## Lab Architecture

Kali Linux → SafeLine WAF → DVWA → MySQL

---

## Implemented Features

* DVWA Installation
* Apache Port Reconfiguration (8080)
* DNS Resolution
* SSL Certificate Creation
* SafeLine WAF Deployment
* SQL Injection Testing
* HTTP Flood Defense
* Custom IP Blocking
* Authentication Controls

---

## Security Demonstrations

### SQL Injection

Payload:

1' OR '1'='1

Result:

SafeLine WAF detected and blocked the attack.

### HTTP Flood Attack

Generated high-volume requests from Kali Linux.

Result:

SafeLine triggered Anti-Bot protection.

### Custom Deny Rule

Blocked attacker IP address.

Result:

Access denied successfully.

---

## Key Learnings

* Web Application Firewall Deployment
* Reverse Proxy Architecture
* SSL/TLS Configuration
* Attack Detection
* Security Monitoring
* Incident Investigation

---
