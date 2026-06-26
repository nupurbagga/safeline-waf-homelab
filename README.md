# SafeLine WAF Homelab

![Platform](https://img.shields.io/badge/Platform-VirtualBox-blue)
![OS](https://img.shields.io/badge/OS-Ubuntu-orange)
![Security](https://img.shields.io/badge/Security-Web%20Application%20Firewall-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)


<img width="451" height="220" alt="safeline homelab drawio" src="https://github.com/user-attachments/assets/ec6e83c2-c617-4e86-9d54-ebc083149093" />


## Overview
Designed and deployed a cybersecurity homelab using Virtualbox to secure a Damn Vulnerable Web Application(DVWA) using Safeline Web Application Firewall.

## Tools
| VirtualBox | Virtualization Platform |
| Kali Linux | Attack simulation |
| Ubuntu Server | Web Server Host |
| Safeline WAF | Web Applicaiton Firewall |
| Apache | Web Server |
| MySQL | Database |
| PHP | DVWA Backend |
| OpenSSL | Self-signed certificate generation |

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
- SQL Injection Testing
- HTTP Flood Detection
- Security Monitoring

## Setup
### Application Deployment
- Installed LAMP stack on Ubuntu server
- Deployed DVWA
- Configured MySQL backend
- Modified Apache to listen on port 8080

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
- HTTP Flood Protection Testing 
- Authenticated sign-in configuration
- Custom deny rule implementations

## Results
Successfully deployed Safeline WAF in front of DVWA using reverse proxy configuration

Safeline successfully :
- Blocked SQL injection attempts
- Applied custom authorization rules
- Protected HTTPS traffic using self-signed certificates
- Logged detected attacks for security monitoring and analysis

## What I Learned
- Deploying and configuring reverse proxy architecture
- Managing HTTPS using SSL certificates
- Understanding how Web Application Firewall inspects and filters traffic
- Troubleshooting Apache, networking and VirtualBox connectivity
