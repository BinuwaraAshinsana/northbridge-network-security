\# T1 – Ransomware and Lateral Movement



\## Threat Overview



Northbridge Savings \& Finance is vulnerable to ransomware attacks because its current network lacks proper segmentation. A ransomware infection that begins on a branch workstation could spread through the network and affect critical systems at the Head Office.



\## Threat Model



\*\*Asset:\*\*  

Branch workstations, internal servers, core banking system, and customer data.



\*\*Vulnerability:\*\*  

The network is largely flat and unsegmented. Some branch systems also use outdated software, increasing the possibility of exploitation.



\*\*Threat:\*\*  

Ransomware infection and lateral movement.



\*\*Exploit:\*\*  

An attacker compromises a vulnerable branch workstation through methods such as malicious files, phishing, or exploitation of outdated software. The compromised system is then used as an entry point to reach other accessible systems.



\*\*Attack:\*\*  

Ransomware executes on the compromised workstation and attempts to spread across reachable network resources. Because of insufficient segmentation, the attack may reach other branch systems or critical Head Office resources.



\*\*Impact:\*\*  

\- Loss of availability of critical systems

\- Encryption or loss of business data

\- Disruption of banking operations

\- Financial losses

\- Reputational damage

\- Possible regulatory consequences



\*\*Risk:\*\*  

High



\## Threat Chain



Asset → Vulnerability → Threat → Exploit → Attack → Impact → Risk



Branch workstations and critical banking systems → Flat/unsegmented network and outdated systems → Ransomware → Initial workstation compromise → Lateral movement and encryption of reachable systems → Operational disruption, data unavailability, financial and reputational damage → \*\*High Risk\*\*



\## Proposed Security Controls



The following controls can reduce this risk:



\- VLAN-based network segmentation

\- Access Control Lists (ACLs)

\- Firewall rules between security zones

\- Restricting unnecessary branch-to-branch communication

\- IDS/IPS monitoring

\- Patch management

\- Centralized security logging

\- Tested and protected backups



\## Packet Tracer Relationship



The Packet Tracer implementation demonstrates network segmentation between Staff, Server, Admin, Guest, and other network zones. ACLs and firewall controls can further restrict unnecessary communication between these networks, reducing the ability of ransomware to move laterally.

