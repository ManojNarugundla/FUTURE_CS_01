# Vulnerability Assessment Report

## About the Project

This project was completed as part of the Future Interns Cyber Security Internship.

The objective of this task was to assess the security of a live website and identify common vulnerabilities using security tools.

## Target Website

demo.testfire.net

## Tools Used

* Nmap
* OWASP ZAP (Passive Scan)
* Browser Developer Tools
* Canva

## Vulnerabilities Found

* Content Security Policy (CSP) Header Not Set
* Missing Anti-clickjacking Header
* Cookie Without Secure Flag
* Cookie No HttpOnly Flag
* Server Information Disclosure
* X-Content-Type-Options Header Missing

## Recommendations

* Implement Content Security Policy (CSP)
* Configure X-Frame-Options Header
* Enable Secure and HttpOnly Cookie Flags
* Hide Server Information
* Add X-Content-Type-Options Header

## Files Included

* Report.pdf
* nmap_scan.png
* zap_alerts.png
* csp_header.png
* anti_clickjacking.png

## Conclusion

The vulnerability assessment helped identify security weaknesses in the website and provided recommendations to improve its security.

## Author

Manoj Narugundla

Future Interns – Cyber Security Internship
