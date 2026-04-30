# Secure E-Commerce Website (Digital Art & Print Store)

## Project Overview
This project focuses on designing and analyzing a secure e-commerce platform using WordPress and WooCommerce. The system is deployed on a free hosting platform and evaluated for real-world security vulnerabilities.

## Live Website
//digitalartandprintstore.ct.ws//

## Technologies Used
- WordPress
- WooCommerce
- MySQL Database
- Free Hosting (InfinityFree)

## System Architecture
Client → Web Server → Application Layer → Database → Security Layer

- Client: Browser
- Server: WordPress Hosting
- Application: WooCommerce
- Database: MySQL
- Security: Wordfence Plugin

## Security Tools Used
- OWASP ZAP (Vulnerability Scanner)
- Wordfence (Firewall & Malware Scanner)

## Vulnerabilities Identified
- Cross-Site Scripting (XSS)
- SQL Injection
- Missing Security Headers (CSP, HSTS, X-Frame-Options)
- Security Misconfigurations

## Security Implementation
- SSL Enforcement using HTTPS redirect
- Wordfence firewall (35% coverage)
- 100% brute-force protection
- Malware scanning enabled

## Key Findings
- 9 alerts detected using OWASP ZAP
- Some alerts (Spring4Shell) identified as false positives
- System is moderately secure but requires improvements

## Recommendations
- Enforce HSTS and HTTPS
- Add security headers
- Update outdated plugins
- Improve firewall configuration
- Use secure paid hosting

## Conclusion
The project successfully demonstrates real-world security analysis of an e-commerce platform using both external and internal security tools. It highlights the importance of layered security and continuous monitoring.
