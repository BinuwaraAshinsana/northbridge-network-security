\# T2 – Social Engineering and Credential Theft



\## Threat Overview



Northbridge Savings \& Finance is vulnerable to social engineering and credential theft. An employee has already received a fraudulent message pretending to be from the IT Helpdesk and requesting their password. The risk is increased by the lack of security awareness training, MFA, and strong centralized authentication controls.



\## Threat Model



\*\*Asset:\*\*  

Employee credentials, email accounts, internal systems, core banking systems, and customer information.



\*\*Vulnerability:\*\*  

Northbridge currently lacks security awareness training and Multi-Factor Authentication (MFA). Password reuse and password sharing also increase the risk of compromised credentials being successfully used.



\*\*Threat:\*\*  

Social engineering, phishing, and credential theft.



\*\*Exploit:\*\*  

An attacker impersonates a trusted person or department, such as the IT Helpdesk, and convinces an employee to disclose their username and password or enter credentials into a fraudulent system.



\*\*Attack:\*\*  

The attacker uses the stolen credentials to gain unauthorized access to Northbridge systems. If the same credentials are reused across multiple systems, the attacker may obtain further access to internal resources.



\*\*Impact:\*\*  

\- Unauthorized access to company systems

\- Compromise of employee accounts

\- Theft or exposure of customer information

\- Unauthorized access to sensitive financial systems

\- Further internal attacks using the compromised account

\- Financial and reputational damage



\*\*Risk:\*\*  

High



\## Threat Chain



Asset → Vulnerability → Threat → Exploit → Attack → Impact → Risk



Employee credentials and sensitive systems → No MFA, insufficient awareness training, and weak password practices → Social engineering/phishing → Credential harvesting through fake IT Helpdesk communication → Attacker uses stolen credentials for unauthorized access → Account compromise, data exposure, and further attacks → \*\*High Risk\*\*



\## Proposed Security Controls



The following controls can reduce this risk:



\- Multi-Factor Authentication (MFA)

\- Centralized AAA

\- Individual user and administrator accounts

\- Strong password policies

\- Security awareness and phishing training

\- Removal of shared VPN accounts

\- Role-based access control

\- Centralized authentication logging

\- Monitoring of suspicious login activity



\## Packet Tracer Relationship



The Packet Tracer implementation includes an AAA server for centralized authentication. Network devices can be configured to authenticate administrators through AAA instead of relying only on shared local credentials.



Centralized authentication also improves accountability because administrative access can be associated with individual user accounts.

