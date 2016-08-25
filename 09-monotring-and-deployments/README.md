# Outcome 09 - Monitoring Deployments

Skill Description
-----------------
The Fellow should have a clear understanding of the various log levels and how to set up logging for a service. They should know the common locations of various log files. They should understand and be able to demonstrate the basics of log rotation

They should understand the difference between logging important information and logging "noise". They should be able to demonstrate how to set up a system to send alerts when errors occur in production systems


Outputs
-------
After attaining this skill, and as a demonstration of it, a fellow should be able to complete the following:

1. An exercise that covers the following operations:
  - Setting up server monitoring for a _production_ environment using Nagios
  - Analyzing the collected metrics for 5 days and write a comprehensive report with recommendations
2. An exercise that covers the following operations:
  - Setting up application monitoring for a NodeJS application using New Relic
  - Deploying the NodeJS application to a VM on AWS
  - Setting up monitoring for the VM using AWS Cloudwatch



**Objectives**
--------------


## **Knowledge**

| Knowledge Unit   |      Studied      | Applied |
|:-----------------|:-----------------:|:---------:|
| I can describe the following from memory: | | |
| The different layers in the Open Systems Interconnection model | [ ] | [ ] |
| How to monitor user metrics and KPIs in the Application layer  | [ ] | [ ] |
| How to monitor web and browser metrics in the Presentation layer  | [ ] | [ ] |
| How to monitor sessions and transactions in the Session layer  | [ ] | [ ] |
| How to monitor App server and database metrics in the Transport layer | [ ] | [ ] |
| How to monitor bandwidth, trace routes, and requests in the Network layer | [ ] | [ ] |
| How to monitor packets, access, and data transfer in the Data Link layer | [ ] | [ ] |
| How to monitor CPU, memory, and disk usage in the Physical layer | [ ] | [ ] |
| How to identify an appropriate monitoring tool for a particular deployment IaaS monitoring, Application Performance Monitoring (APM) | [ ] | [ ] |
| Various APM (Application Performance Monitoring) metrics | [ ] | [ ] |
| How application response times affect users | [ ] | [ ] |
| How to measure Mean Time to Resolve (MTTR) | [ ] | [ ] |
| Various Database monitoring metrics | [ ] | [ ] |
| How to measure time spent in database calls | [ ] | [ ] |
| How to measure database call response time and throughput | [ ] | [ ] |
| How to perform SQL query analysis | [ ] | [ ] |
| The differences between Reactive Monitoring and Proactive Monitoring | [ ] | [ ] |
| Use cases for logging | [ ] | [ ] |
| Use cases for infrastructure logs | [ ] | [ ] |
| Use cases for App Stack logs (OS, app server, database, programming language) | [ ] | [ ] |
| Use cases for API logs | [ ] | [ ] |
| Use cases for Application logs | [ ] | [ ] |
| Use cases for Security logs | [ ] | [ ] |
| Use cases for Events, notifications, alerts | [ ] | [ ] |
| Use cases for Changes, configuration management, deployment logs | [ ] | [ ] |
| Use cases for Access logs | [ ] | [ ] |
| Use cases for Patching history logs | [ ] | [ ] |
| Use cases for machine images logs | [ ] | [ ] |


----------------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:----------------------|:------------------:|:--------:|
| **Context:** When making new code changes **Action:** I monitor for any major metric change | [ ] | [ ] |
| **Context:** When setting up any deployment environment **Action:** I make sure that specific monitoring tools are set up for every service e.g. databases, web-server, etc | [ ] | [ ] |
| **Context:** When setting up monitoring tools **Action:** I identify metrics that will be monitored in real-time and those that will be mined from log data | [ ] | [ ] |
| **Context:** When choosing a logging strategy for a distributed environment **Action:** I consider keeping the logs on a separate server from the one running the apps so the logging service does not go down with the apps (centralized logs) | [ ] | [ ] |
| **Context:** When setting up monitoring for any environment **Action:** I make sure I set up alerts and notification for critical metrics and events | [ ] | [ ] |


--------------


## **Beliefs**

| Embodied Belief   |      Felt      | Demonstrated |
|:------------------|:--------------:|:------------:|
| Monitoring is vital for identifying performance bottlenecks of any system | [ ] | [ ] |
| Proactive monitoring helps solve anticipated problems | [ ] | [ ] |
| Performance is key to a great user experience for any application | [ ] | [ ] |
| Every good monitoring strategy should be accompanied with a sound logging solution | [ ] | [ ] |
| To maintain integrity in monitoring, developer access to the _live server_ should be blocked and they should be directed to the logging app instead | [ ] | [ ] |
| Logs need to be easy to use and understand, otherwise they will be useless | [ ] | [ ] |

