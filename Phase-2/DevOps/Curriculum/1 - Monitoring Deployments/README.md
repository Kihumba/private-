# Monitoring Deployments

**Skill Description**
----------
Monitoring and analysis application/deployment behavior (trends, anomalies and thresholds) using analytics tools to quickly see opportunities to optimize performance.


**Output**
----------
After attaining this skill, and as a demonstration of it, a person should be able to do the following:

- Set up monitoring for a _production_ environment, using appropriate tools for that particular environment. (Preferably the tools should be open-source with no cost implications).
- Analyze the collected metrics for 5 days and write a comprehensive report with recommendations.


**Objectives**
----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| I can describe, from memory, the various levels of monitoring and their metrics: | | |
| * Application: user metrics, KPIs               | [ ] | [ ]  |
| * Presentation: web, browser metrics            | [ ] | [ ]  |
| * Session: session, transactions                | [ ] | [ ]  |
| * Transport: App server, database               | [ ] | [ ]  |
| * Network: bandwidth, trace routes, requests    | [ ] | [ ]  |
| * Data Link: packets, access, data transfer     | [ ] | [ ]  |
| * Physical: CPU, memory, disk                   | [ ] | [ ]  |
| Identifying an appropriate monitoring tool for a particular deployment e.g. IaaS monitoring, Application Performance Monitoring (APM) | [ ] | [ ]  |
| I can describe, from memory, the various APM (Application Performance Monitoring) metrics: | | |
| * Application response times | [ ] | [ ]  |
| * Most time consuming transactions | [ ] | [ ]  |
| * Mean Time to Resolve (MTTR) | [ ] | [ ]  |
| I can describe, from memory, the various Database monitoring metrics: | | |
| * Time spent in database calls | [ ] | [ ]  |
| * Database call response time and throughput | [ ] | [ ]  |
| * SQL query analysis | [ ] | [ ]  |
| Difference between _reactive monitoring_ and _proactive monitoring_ | [ ] | [ ]  |
| I can describe, from memory, the various logs that are vital for any proper monitoring: | | |
| * Infrastructure logs | [ ] | [ ]  |
| * App Stack logs (OS, app server, database, programming language) | [ ] | [ ]  |
| * API logs | [ ] | [ ]  |
| * Application logs | [ ] | [ ]  |
| * Security logs | [ ] | [ ]  |
| * Events, notifications, alerts | [ ] | [ ]  |
| * Changes, configuration management, deployment | [ ] | [ ]  |
| * Access | [ ] | [ ]  |
| * Patching history, machine images | [ ] | [ ]  |



## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When making new code changes, **Action:** I monitor for any major metric change. | [ ] | [ ]  |
| **Context:** When setting up any deployment environment, **Action:** I make sure that specific monitoring tools are set up for every service e.g. databases, web-server, etc. | [ ] | [ ]  |
| **Context:** When setting up monitoring tools, **Action:** I identify metrics that will be monitored in real-time and those that will be mined from log data. | [ ] | [ ]  |
| **Context:** When choosing a logging strategy for a distributed environment, **Action:** I consider keeping the logs on a separate server from the one running the apps so the logging service does not go down with the apps (centralized logs). | [ ] | [ ]  |
| **Context:** When setting up monitoring for any environment, **Action:** I make sure I set up alerts and notification for critical metrics and events. | [ ] | [ ]  |


## **Beliefs**

| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Monitoring is vital for identifying performance bottlenecks of any system. | [ ] | [ ]  |
| Proactive monitoring helps solve anticipated problems. | [ ] | [ ]  |
| Performance is key to a great user experience for any application. | [ ] | [ ]  |
| Every good monitoring strategy should accompanied with a sound logging solution | [ ] | [ ]  |
| To maintain integrity in monitoring, developer access to the _live server_ should be blocked and they should be directed to the logging app instead. | [ ] | [ ]  |
| Logs need to be easy to use and understand, otherwise they will be useless. | [ ] | [ ]  |




