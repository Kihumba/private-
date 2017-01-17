# Outcome 06 - Continuous Integration/Continuous Deployment

Skill Description
-----------------
The Fellow will be able to set up an environment for continuous integration using ConcourseCI, Jenkins or similar tools and merge development work with a Master/Trunk/Mainline branch. The Fellow will also be able to write automated and unit tests, and deploy code to the production environment as soon as it has passed testing and is ready. 


Outputs
-------
After attaining this skill, and as a demonstration of it, a fellow should be able to create the following:

1. A completed exercise that covers the following operations:
  - Creating a source control repository to manage versions of a release
  - Creating a CI pipeline using ConcourseCI for the engineering team to run tests when a commit is checked in, tag successful builds
  - Configuring the CI pipeline to build and tag docker images containing the successful build and push it to a container registry
  - Configuring the pipeline to deploy successful images to a test namespace on Kubernetes


**Objectives**
--------------


## **Knowledge**

| Knowledge Unit   |      Studied      | Applied |
|:-----------------|:-----------------:|:---------:|
| How to create a CI pipeline | [ ] | [ ] |
| How to automate test builds | [ ] | [ ] |
| How to version successful test builds | [ ] | [ ] |
| The difference between automated tests and unit tests | [ ] | [ ] |
| How to set up production-like environments for testing | [ ] | [ ] |
| The definition of Continuous Delivery and the importance of a good Continuous Integration process | [ ] | [ ] |
| How to execute the blue-green deployment strategy | [ ] | [ ] |

----------------


## **Behaviors**

| Observable Behavior   |      Practiced      | Observed |
|:----------------------|:------------------:|:--------:|
| **Context:** Before committing code to a repository **Action:** I run tests locally | [ ] | [ ] |
| **Context:** When a build fails tests on CI **Action:** I fix it in a timely manner and then redeploy | [ ] | [ ] |
| **Context:** When deploying a release to production in an automated manner **Action:** I use the blue-green deployment strategy to avoid downtime during deployment | [ ] | [ ] |


--------------


## **Beliefs**

| Embodied Belief   |      Felt          | Demonstrated |
|:------------------|:------------------:|:------------:|
| Code should only be deployed to production when it passes all tests | [ ] | [ ] |
| Adapt fast and deploy releases frequently | [ ] | [ ] |
| Software releases should be tested on an environment similar to the production environment | [ ] | [ ] |
| CD systems enable releasing deployable software at any time | [ ] | [ ] |
| CI systems provide feedback about failure and enables developers to have more confidence in making their changes | [ ] | [ ] |
| Automating repetitive processes saves time and effort | [ ] | [ ] |
