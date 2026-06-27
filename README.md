# SafeLine WAF Homelab

![Platform](https://img.shields.io/badge/Platform-VirtualBox-blue)
![OS](https://img.shields.io/badge/OS-Ubuntu%20%7C%20Parrot-orange)
![Security](https://img.shields.io/badge/Security-Web%20Application%20Firewall-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)


<img width="451" height="220" alt="safeline-waf drawio" src="https://github.com/user-attachments/assets/a5753c9c-f240-4d0f-b818-92b6e5e508f1" />


## Overview
Designed and deployed a cybersecurity homelab using Virtualbox to secure a Damn Vulnerable Web Application(DVWA) using SafeLine Web Application Firewall.

## Tools
| Tool | Purpose |
| ---- | ------- |
| VirtualBox | Virtualization Platform |
| Parrot OS | Attack Simulation |
| Ubuntu Server | Web Server Host |
| SafeLine WAF | Web Application Firewall |
| Apache | Web Server |
| MySQL | Database |
| PHP | DVWA Backend |
| OpenSSL | Self-Signed Certificate Generation |

## Objectives
- Deploy a vulnerable web application
- Configure HTTPS using self signed certificates
- Test SQL injection attacks
- Analyse WAF protection mechanisms

## Skills demonstrated
- Web Application Firewall (WAF)
- Reverse Proxy Configuration
- HTTPS and SSL Certificates
- Linux Server Administration
- Network Troubleshooting
- SQL Injection Testing
- HTTP Flood Detection
- Security Monitoring

## Setup
### Application Deployment
- Installed the LAMP stack on Ubuntu server
- Deployed DVWA
- Configured MySQL backend
- Modified Apache to listen on port 8080

### HTTPS Configuration
- Generated self-signed SSL certificates
- Configured and imported certificates to SafeLine
- Enabled HTTPS access

### WAF Configuration
- Configured SafeLine WAF
- Added DVWA as a protected application
- Configured reverse proxy settings
- Attached SSL certificates

## Testing
- Performed SQL Injection testing to validate that SafeLine blocked malicious attacks while allowing legitimate requests
- HTTP Flood Protection Testing 
- Authenticated sign-in configuration
- Custom deny rule implementations

## Results
Successfully deployed SafeLine WAF in front of DVWA using reverse proxy configuration

SafeLine successfully :
- Blocked SQL injection attempts
- Applied custom authorization rules
- Protected HTTPS traffic using self-signed SSL certificates
- Logged detected attacks for security monitoring and analysis

## What I Learned
- Deploying and configuring reverse proxy architecture
- Managing HTTPS using SSL certificates
- Understanding how Web Application Firewalls inspect and filter traffic
- Troubleshooting Apache, networking and VirtualBox connectivity
