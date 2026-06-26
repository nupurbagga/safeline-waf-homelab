# SafeLine WAF Homelab

![Platform](https://img.shields.io/badge/Platform-VirtualBox-blue)
![OS](https://img.shields.io/badge/OS-Ubuntu-orange)
![Security](https://img.shields.io/badge/Security-Web%20Application%20Firewall-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

# safeline-waf-homelab
Web Application Firewall Homelab

<img width="451" height="220" alt="safeline homelab drawio" src="https://github.com/user-attachments/assets/ec6e83c2-c617-4e86-9d54-ebc083149093" />


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

## Skills demonstrated
- Web Application Firewall (WAF)
- Reverse Proxy Configuration
- HTTPS/SSL Certificates
- Linux Server Administration
- Network Troubleshooting
- SQL Injection testing
- HTTP Flood Detection
- Security Monitoring

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
- Performed SQL Injection attacks to validate that Safeline blocked malicious attacks while allowing legitimate requests
- HTTP flood defense training 
- Authenticated sign-in configuration
- Custom deny rule implementations

## Results
Successfully deployed Safeline WAF in front of DVWA using reverse proxy configuration

Validated :
- Blocking SQL injection attempts
- Applying custom authorization rules
- Protecting HTTPS traffic using self-signed certificates
- Logging detected attacks for security monitoring and analysis


