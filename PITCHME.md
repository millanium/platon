# Security Testing

![](https://cdn.elegantthemes.com/blog/wp-content/uploads/2015/09/Best-WordPress-Security-Plugins-shutterstock_252971932.png)
---

## What is Security testing?

The goal of security testing is to identify the threats in the system and measure its potential vulnerabilities. It also helps in detecting all possible security risks in the system and help developers in fixing these problems through coding.

+++

## Types of Security testing

- **Vulnerability Scanning**: This is done through automated software to scan a system against known vulnerability signatures.
- **Security Scanning**: It involves identifying network and system weaknesses, and later provides solutions for reducing these risks. This scanning can be performed for both Manual and Automated scanning.
- **Penetration testing**: This kind of testing simulates an attack from a malicious hacker. This testing involves analysis of a particular system to check for potential vulnerabilities to an external hacking attempt.
- **Risk Assessment**: This testing involves analysis of security risks observed in the organization. Risks are classified as Low, Medium and High. This testing recommends controls and measures to reduce the risk.
- **Security Auditing**: This is an internal inspection of Applications and Operating systems for security flaws. Audit can also be done via line by line inspection of code
- **Ethical Hacking**: It's hacking an Organization Software systems. Unlike malicious hackers ,who steal for their own gains , the intent is to expose security flaws in  the system.
- **Posture Assessment**: This combines Security scanning, Ethical Hacking and Risk Assessments to show an overall security posture of an organization.


---
## What is an attack?

Attacks are the techniques that attackers use to exploit the vulnerabilities in applications. Attacks are often confused with vulnerabilities, so please try to be sure that the attack you are describing is something that an attacker would do, rather than a weakness in an application.

+++

## Examples

- **Brute Force**: Is an exhaustive attack that works by testing every possible value of a parameter (password, file name, etc.) Brute_force_attack
- **Cache Poisoning**: Is an attack that seeks to introduce false or malicious data into a web cache, normally via HTTP Response Splitting. Cache_Poisoning
- **DNS Poisoning**: Is an attack that seeks to introduce false DNS address information into the cache of a DNS server, where it will be served to other users enabling a variety of attacks. (e.g., Phishing)

+++

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
- **Broken Authentication/Session**  Attackers compromise passwords, keys, or session tokens, or to exploit other implementation flaws to assume other users’ identities.
- **Cross-Site Scripting (XSS)** XSS allows attackers to execute scripts in the victim’s browser which can hijack user sessions, deface web sites, or redirect the user to malicious sites.
- **Sensitive Data Exposure** Attackers may steal or modify such weakly protected data to conduct credit card fraud, identity theft, or other crimes



+++

## Mobile Top 10 - 2016

- **Improper Platform Usage** It might include Android intents, platform permissions, misuse of TouchID, the Keychain, or some other security control that is part of the mobile operating system.
- **Insecure Communication** This covers poor handshaking, incorrect SSL versions, weak negotiation, cleartext communication of sensitive assets.
- **Insecure Authentication** Notions on Authentication or bad session management
- **Reverse Engineering** Backdoor functionality or internal assets that are not intended for release.
