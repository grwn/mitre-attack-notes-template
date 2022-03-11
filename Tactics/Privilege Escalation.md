The adversary is trying to gain higher-level permissions.

Privilege Escalation consists of techniques that adversaries use to gain higher-level permissions on a system or network. Adversaries can often enter and explore a network with unprivileged access but require elevated permissions to follow through on their objectives. Common approaches are to take advantage of system weaknesses, misconfigurations, and vulnerabilities. Examples of elevated access include: 

- SYSTEM/root level
- local administrator
- user account with admin-like access 
- user accounts with access to specific system or perform specific function

These techniques often overlap with Persistence techniques, as OS features that let an adversary persist can execute in an elevated context.

## Techniques

[[T1548 - Abuse Elevation Control Mechanism]]
[[T1134 - Access Token Manipulation]]
[[T1547 - Boot or Logon Autostart Execution]]
[[T1037 - Boot or Logon Initialization Scripts]]
[[T1543 - Create or Modify System Process]]
[[T1484 - Domain Policy Modification]]
[[T1611 - Escape to Host]]
[[T1546 - Event Triggered Execution]]
[[T1068 - Exploitation for Privilege Escalation]]
[[T1574 - Hijack Execution Flow]]
[[T1055 - Process Injection]]
[[T1053 - Scheduled Task or Job]]
[[T1078 - Valid Accounts]]