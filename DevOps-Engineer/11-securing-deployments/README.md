# Outcome 11 - Securing Deployments

Skill Description
-----------------
The Fellow understands how to apply security policies to secure machines deployed to a cloud


Outputs
-------
After attaining this skill, and as a demonstration of it, a Fellow should be able to complete the following:

1. An exercise that covers the following operations:
  - Setting up hooks to scan for secure credentials/token before code is checked in to a repo
  - Ensuring credentials for production systems are stored in a secure vault and restricting access to it
  - Isolating security credentials/tokens for all different environments
  - Putting together tools to monitor and analyze system logs for suspicious activities
  - Running processes with the least required set of permissions to prevent privilege escalation
  - Setting up and configuring ssh daemon for private key authentication
  - Applying OS security patches to a system
  - Defining firewall rules to control access to the machine
  - Logging all connections to deployed machines
  - Securing data transfer using SSL


**Objectives**
--------------


## **Knowledge**

| Knowledge Unit   |      Studied      | Memorized |
|:-----------------|:-----------------:|:---------:|
| I can describe the following from memory: | | |
| How to install/update software on a system | [ ] | [ ] |
| How to disable root ssh login on a system | [ ] | [ ] |
| How to run a process with elevated privileges | [ ] | [ ] |
| How to run a process with restricted privileges | [ ] | [ ] |
| How to view a list of all open ports/connections on a system | [ ] | [ ] |
| How to restrict access to system ports | [ ] | [ ] |
| How to apply firewall rules | [ ] | [ ] |
| How to run a list of common attacks against the code to check for disclosed security vulnerabilities | [ ] | [ ] |


----------------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:----------------------|:------------------:|:--------:|
| **Context:** Before deploying code to a repository **Action:** I remove all security credentials/tokens if any | [ ] | [ ]  |
| **Context:** Before deploying code to production systems **Action:** I run a list of common attacks against the system to ensure the system is not vulnerable | [ ] | [ ]  |
| **Context:** After a Common Vulnerability and Exposure (CVE) is disclosed and patched **Action:** I apply the patch to production systems in a timely manner | [ ] | [ ]  |
| **Context:** When a security credential/token is leaked **Action:** I generate new credentials and replace them on production systems in a timely manner | [ ] | [ ]  |
| **Context:** When suspicious activity is detected by monitoring scripts **Action:** I send alerts and notifications | [ ] | [ ]  |
| **Context:** When I run a process on a production system **Action** I run with the least required set of permissions to prevent privilege escalation | [ ] | [ ] |


--------------


## **Beliefs**

| Embodied Belief   |      Felt      | Demonstrated |
|:------------------|:--------------:|:------------:|
| Communications between client and server should be encrypted with HTTPS during transport | [ ] | [ ] |
| Security credentials/tokens should be rotated on a frequent basis | [ ] | [ ] |
| Security credentials/tokens should not be stored on a publicly accessible repository | [ ] | [ ] |
| Security credentials/tokens should be different for each environment and stored separately | [ ] | [ ] |
| Security credentials/tokens should not be reused across different environments (test, staging, production, e.t.c) | [ ] | [ ] |
| Security is vital in the software deployment lifecycle | [ ] | [ ] |
| Contributing to insecure code, puts my users, my client, and Andela at tremendous risk | [ ] | [ ] |