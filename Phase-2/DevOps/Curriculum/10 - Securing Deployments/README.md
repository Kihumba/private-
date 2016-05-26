# Outcome 10 - Securing Deployments

Skill Description
-----------------
Applying security policies to secure cloud managed machines


Outputs
-------
After attaining this skill, and as a demonstration of it, a fellow should be able to do the following:

- Setup hooks to scan for secure credentials/token before code is checked in to a repo
- Ensure credentials for production systems are stored in a secure vault and restrict access to it
- Isolate security credentials/tokens for all different environments
- Put together tools to monitor and analyze system logs for suspicious activities
- Run processes with the least required set of permissions to prevent priviledge escalation
- Set file permissions
- View all open ports/connections on a system
- Setup and configure ssh daemon for private key authentication
- Apply OS security patches to a system
- Restrict access to unused ports
- Define firewall rules to control access to the machine
- Log all connections to deployed machines
- Securing data transfer using SSL


## **Knowledge**

| Knowledge Unit   |      Studied      | Memorized |
|:-----------------|:-----------------:|:---------:|
| I can describe, from memory, how to set file permissions for the following entities: | | |
| * User (read,write,execute) | [ ] | [ ]  |
| * Group (read,write,execute) | [ ] | [ ]  |
| * World (read,write,execute) | [ ] | [ ]  |
| I can describe, from memory, how to install/update software on a system | [ ] | [ ] |
| I can describe, from memory, how to disable root ssh login on a system | [ ] | [ ] |
| I can describe, from memory, how to run a process with elevated privileges | [ ] | [ ] |
| I can describe, from memory, how to run a process with restricted privileges | [ ] | [ ] |
| I can describe, from memory, how to view a list of all open ports/connections on a system | [ ] | [ ] |
| I can describe, from memory, how to restrict access to system ports | [ ] | [ ] |
| I can describe, from memory, how to apply firewall rules | [ ] | [ ] |



## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:----------------------|:------------------:|:--------:|
| **Context:** Before deploying code to a repository **Action:** I remove all security credentials/tokens if any | [ ] | [ ]  |
| **Context:** Before deploying code to production systems **Action:** I run a list of common attacks against the system to ensure the system is not vulnerable | [ ] | [ ]  |
| **Context:** AFter a CVE is disclosed and patched **Action:** I apply the patch to production systems in a timely manner | [ ] | [ ]  |
| **Context:** When a security credential/token is leaked **Action:** I generate new credentials and replace them on production systems in a timely manner | [ ] | [ ]  |
| **Context:** When suspicious activity is detected by monitoring scripts **Action:** I send alerts and notifications | [ ] | [ ]  |
| **Context:** When I run a process on a production system **Action** I run with the least required set of permissions to prevent privilege escalation | [ ] | [ ] |



## **Beliefs**

| Embodied Belief   |      Felt      | Demonstrated |
|:------------------|:--------------:|:------------:|
| Communications between client and server should be encrypted with HTTPS during transport | [ ] | [ ] |
| Security credentials/tokens should be rotated on a frequent basis | [ ] | [ ] |
| Security credentials/tokens should not be stored on a publicly accessible repository | [ ] | [ ] |
| Security credentials/tokens should be different for each environment and stored separately | [ ] | [ ] |
| Security credentials/tokens should not be reused across different environments (test, staging, production, e.t.c) | [ ] | [ ] |
| Security is vital in the software deployment lifecycle | [ ] | [ ] |
