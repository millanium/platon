# Security Testing

![](https://cdn.elegantthemes.com/blog/wp-content/uploads/2015/09/Best-WordPress-Security-Plugins-shutterstock_252971932.png)
---

## What is Security testing?

The goal of security testing is to identify the threats in the system and measure its potential vulnerabilities. It also helps in detecting all possible security risks in the system and help developers in fixing these problems through coding.

+++

## Types of Security testing

- **Vulnerability Scanning**: This is done through automated software to scan a system against known vulnerability signatures.
---
## Types of Security testing
- **Security Scanning**: It involves identifying network and system weaknesses, and later provides solutions for reducing these risks.
---
## Types of Security testing
- **Penetration testing**: This testing involves analysis of a particular system to check for potential vulnerabilities to an external hacking attempt.
---
## Types of Security testing
- **Risk Assessment**: This testing involves analysis of security risks observed in the organization. This testing recommends controls and measures to reduce the risk.
---
## Types of Security testing
- **Security Auditing**: This is an internal inspection of Applications and Operating systems for security flaws. Audit can also be done via line by line inspection of code.
---
## Types of Security testing
- **Ethical Hacking**: It's hacking an Organization Software systems. Unlike malicious hackers ,who steal for their own gains , the intent is to expose security flaws in  the system.
---
## Types of Security testing
- **Posture Assessment**: This combines Security scanning, Ethical Hacking and Risk Assessments to show an overall security posture of an organization.

---
## What is an attack?

Attacks are the techniques that attackers use to exploit the vulnerabilities in applications. Attacks are often confused with vulnerabilities, so please try to be sure that the attack you are describing is something that an attacker would do, rather than a weakness in an application.

+++

## Examples

- **Brute Force**: Is an exhaustive attack that works by testing every possible value of a parameter (password, file name, etc.) Brute_force_attack.
---
## Examples
- **Cache Poisoning**: Is an attack that seeks to introduce false or malicious data into a web cache, normally via HTTP Response Splitting.
---
## Examples
- **DNS Poisoning**: Is an attack that seeks to introduce false DNS address information into the cache of a DNS server, where it will be served to other users enabling a variety of attacks.

---

## What is Vulnerability?

A vulnerability is a hole or a weakness in the application, which can be a design flaw or an implementation bug, that allows an attacker to cause harm to the stakeholders of an application. Stakeholders include the application owner, application users, and other entities that rely on the application. The term "vulnerability" is often used very loosely.

+++
## Examples

- Lack of input validation on user input
- Lack of sufficient logging mechanism
- Fail-open error handling
- Not closing the database connection properly

---

## Sample Test Scenarios

- *Password should be encrypted*
- *Endpoints should be brute-force protected*
- *Transaction IDs should be encrypted*
- *Traffic should be protected with certificates*

---

## Methodologies

- **Tiger Box**: Collection of different operating systems and hacking tools
- **Black Box**: Allowed testing on network and technology
- **Grey Box**: Partial information is given to the hacker

---

## Intro to oWASP

- **Open Web Application Security Project**


+++

## Top 10 Attack Types

- **Injection** Injection flaws, such as SQL, OS, and LDAP injection occur when untrusted data is sent to an interpreter as part of a command or query.
---
## Top 10 Attack Types
- **Broken Authentication/Session**  Attackers compromise passwords, keys, or session tokens, or to exploit other implementation flaws to assume other users’ identities.
---
## Top 10 Attack Types
- **Cross-Site Scripting (XSS)** XSS allows attackers to execute scripts in the victim’s browser which can hijack user sessions, deface web sites, or redirect the user to malicious sites.
---
## Top 10 Attack Types
- **Sensitive Data Exposure** Attackers may steal or modify such weakly protected data to conduct credit card fraud, identity theft, or other crimes

+++

## Mobile Top 10 - 2016
- **Improper Platform Usage** It might include Android intents, platform permissions, misuse of TouchID, the Keychain, or some other security control that is part of the mobile operating system.
---
## Mobile Top 10 - 2016
- **Insecure Communication** This covers poor handshaking, incorrect SSL versions, weak negotiation, cleartext communication of sensitive assets.
---
## Mobile Top 10 - 2016
- **Insecure Authentication** Notions on Authentication or bad session management.
---
## Mobile Top 10 - 2016
- **Reverse Engineering** Backdoor functionality or internal assets that are not intended for release.
---
## Threat Modeling

It is an approach for analyzing the security of an application. It is a structured approach that enables you to identify, quantify, and address the security risks associated with an application.

+++
## Threat Modeling

![](https://pbs.twimg.com/media/CGjyvaIUIAAZIJZ.png:large)

---
## Approach to security testing

![](http://www.amanhardikar.com/mindmaps/SecurityTests.png)

---
## SQL Injection attacks

Injection flaws occur when untrusted data is sent to an interpreter as part of a command or query. The attacker’s hostile data can trick the interpreter into executing unintended commands or accessing data without proper authorization.

+++
http://sqlzoo.net/hack/
https://www.w3schools.com/sql/sql_injection.asp

---
## Hacking using Charles proxy

- Brute-force attack
- Checking the API traffic for sensitive data: Requests/Responses, Session IDs, Encryption
-

---
## Security testing tools

![](http://apps.testinsane.com/mindmaps/Uploads/Security%20Testing%20Tools.png)
