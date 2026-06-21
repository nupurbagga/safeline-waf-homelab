# safeline-waf-homelab
Web Application Firewall Homelab

## Overview
Built a cybersecurity homelab in order to deploy a Safeline Web Application Firewall in front of a Damn Vulnerable Web Application(DVWA)

##  Environment
- VirtualBox
- Kali Linux
- Ubuntu Server
- Safeline WAF
- DVWA
- Apache
- MySQL
- PHP

## Objectives
- Deploy a vulnerable web application
- Configure HTTPS using self signed certificates
- Test SQL injection attacks
- Analyse WAF protection mechanisms and methods

## Setup
### Web Application Firewall
- Installed LAMP stack
- Deployed DVWA
- Configured MySQL backend
- Modified Apache to use port 8080

### HTTPS Configuration
- Generated self-signed SSL certificates
- Configured and imported certificates to Safeline
- Enabled HTTPS access

### WAF Configuration
- Configured Safeline WAF
- Added DVWA as a protected application
- Configured reverse proxy settings
- Attached SSL certificates

## Testing
- Performed SQL Injection attacks
- HTTP flood defense training
- Authenticated sign-in configuration
- Custom deny rule implementations

## Results
Safeline WAF was successfully deployed on DVWA and detected and blocked it from malicious SQL injection requests while allowing legitimate traffic.
