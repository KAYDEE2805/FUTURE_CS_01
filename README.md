# FUTURE_CS_01
<h2>TASK 1: WEB APPLICATION SECURITY TESTING</h2>
This repository is a documentation of my work on Task 1 of my cybersecurity internship, where I performed vulnerability testing on OWASP Juice-shop. Manual techniques, and scanning tools were used to identify and exploit common web application vulnerabilities, mapped them to the OWASP Top 10, and also compiled a full security assessment report.<br>
<h2>OBJECTIVE</h2>
To explore and exploit common web application flaws in a controlled environment, using industry-standard tools, and to document findinds with screenshots, impact analysis, and remediation strategies.
<h2>TOOLS USED</h2>
OWASP Juice-Shop<br>
Burpsuit – Open-source vulnerability scanner<br>
Kali Linux (optional) – Security testing OS<br>
Firefox Developer Tools - Manual inspection and request capture<br>
Google Docs / Word - Report compilation
<h2>VULNERABILITY TESTED</h2>
<b>1. SQL Injection (Data Schema)</b><br>
Impact: Critical (breaking into the database of the website)<br>
OWASP Mapping: A03:2021 – Injection<br>
Remediation: Use of Properly Constructed Stored Procedures<br>
Screenshot: ! [SQL Injection Exploi] (sql-injection.png)<br>
<br>
<b>2. Broken Access Control</b><br>
Impact: High (breaking the GDRP law by Loging in into a deleted account without password)
OWASP Mapping: A03:2021 – Injection| A01:2021 - Broken Access Control<br>
Remediation: mplement access restrictions and regular audits to ensure that only those employees who need access have it.<br>
Screenshot: ! [Broken Access Control] (screenshots/BAC.png)<br><br>
<b>3.Broken Authentication (Successful login)</b>
Impact: Medium (Admin loged in without consent due weak password)<br>
OWASP Mapping: A07:2021-Identification and Authentication Failures <br>
Remediation: use  a strong password<br>
Screenshot: ![Password Strength] (BA.png)
<h2>DELIVERABLES</h2>
Security Report with risk rating (PDF)<br>
OWASP Top 10 Compliance checklist<br>
Screenshots of each exploit<br>
Source code of CSRF attack page<br>
GitHub documentation<br>
<h2>SKILLS GAINED</h2>
Web application vulnerability scanning<br>
Security documentation and reporting<br>
Knowledge of OWASP Top 10 threats<br>
Ethical hacking and penetration testing<br>
Threat modeling and risk analysis<br>
<h2>AUTHOR</h2>
KAZEEM DAVID OLUWAROTIMI<br>
Cybersecurity Intern<br>
Location: Remote<br>
