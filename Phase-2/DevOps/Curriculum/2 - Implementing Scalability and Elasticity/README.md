# Implementing Scalability and Elasticity

**Skill Description**
----------
This skills involves understanding what _scalable cloud architecture_ is, why it matters, and how to implement it on any given _cloud_ service provider. 

Every provider have their own tools to implement scaling but the model/architecture is same across the board.


**Output**
----------
After attaining this skill, and as a demonstration of it, a person should be able following:

- Configure _auto-scaling_ on an AWS deployment.
- Run simulated requests to demonstrate how the deployment performs on varying load.
- Collect the essential monitoring metrics and give a one-page report with graphs on how the deployment performed.


**Objectives**
----------
## **Knowledge**

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| I can describe, from memory, the following types of Scaling | | |
| * Horizontal Scaling  | [ ] | [ ]  |
| * Vertical Scaling    | [ ] | [ ]  |
| I can describe, from memory, specific scaling **techniques** and **tools** for every _cloud architecture level_ of the application | |  |
| * Load Balancing Tier         | [ ] | [ ]  |
| * Web/Application Server Tier | [ ] | [ ]  |
| * Caching Tier                | [ ] | [ ]  |
| * Database Tier               | [ ] | [ ]  |

----------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When considering to auto-scale my deployment setup, **Action:** I separate those parts in which on-demand scaling will work and those that it will be ideal. | [ ] | [ ]  |
| **Context:** When the application is _read-intensive_, **Action:** I use a _caching implementation_ for scaling such an application. | [ ] | [ ]  |
| **Context:** When designing an application for scalability, **Action:** I plan for the potential of an application’s unprecedented success, while keeping in mind budget constraints during the initial phases of the application when resource demands are low | [ ] | [ ]  |
| **Context:** When there is a sudden increase in processing time due to addition of new features,  **Action:** I use auto-scaling for short-time mitigation until I can isolate and optimize the performance bottlenecks. | [ ] | [ ]  |


----------


## **Beliefs**

| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Even though the _Cloud_ is scalable, you cannot take advantage of the scalability if your infrastructure is not scalable at any point. | [ ] | [ ]  |
| In most classic web-based applications, the database is the eventual bottleneck, so anytime you can alleviate some of its load, the application will perform better. | [ ] | [ ]  |
| The _cloud_ provides the ideal environment for scalable applications because it allows for rapid resource allocation in times of high demand as well as resource deallocation as demand declines. | [ ] | [ ]  |
| _Overprovisioning_ is not cost effective since, while it enables an application to increase its availability in high-traffic situations, a portion of these resources sits idle during non-peak periods. | [ ] | [ ]  |
| A scalable cloud model (auto-scaling) is the most cost-effective for an unpredictable web environment, since you can dynamically provision additional resources only when they are needed and then decommission them when they are no longer required. | [ ] | [ ]  |

