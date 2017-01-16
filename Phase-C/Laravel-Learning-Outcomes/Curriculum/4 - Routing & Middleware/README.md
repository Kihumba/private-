# Routing and Middleware

Skill Description
----------
The router is the doorman of your application. When an HTTP request arrives from the user's browser, it needs to know which controller action (method) should be run. Should we display the "new user" web page? Should we edit an existing user with whatever data got sent along? etc. The router basically match HTTP request to the appropriate action.

Outputs
----------
After attaining this skill, and as a demonstration of it, I should be able to build out an API using Slim Routes and Middleware. 

----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| The definition of Middlewares and what they are used for | [ ] | [ ]  |
| The difference between a Controller Middleware and a Route Middleware | [ ] | [ ]  |
| How to specify an ID or other variables in a route | [ ] | [ ]  |
| The purpose of various route helper methods | [ ] | [ ]  |
| The difference between path and url helpers| [ ] | [ ]  |
| How to group a set of routes | [ ] | [ ]  |
| The importance of naming routes | [ ] | [ ]  |
| The importance of route resources| [ ] | [ ]  |
| How to easily write all seven RESTful routes in Laravel | [ ] | [ ]  |
| How to limit the restful routes created by resources | [ ] | [ ]  |
| How to create nested resources | [ ] | [ ]  |
| When to use nested resources | [ ] | [ ]  |


----------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When building a Laravel application **Action:** I specify routes for the application. | [ ] | [ ]  |
| **Context:** When I want to limit routes to specific users **Action:** I use a Middleware. | [ ] | [ ]  |
| **Context:** When I need to create all seven RESTful routes for a resource **Action:** I use the `resource` method. | [ ] | [ ]  |
| **Context:** When adding links to my views **Action:** I use route helper methods instead of adding the raw link. | [ ] | [ ]  |
| **Context:** When defining routes for an application that does not have a controller action **Action:** I use a callback. | [ ] | [ ]  |
| **Context:** When I want to know the different routes supported by my application **Action:** I use the `php artisan route:list` command. | [ ] | [ ]  |
| **Context:** When building out an API **Action:** I prefix my routes and group them with the route `group` method. | [ ] | [ ]  |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Grouping similar routes together eliminates code duplication. | [ ] | [ ]  |
| A router is the doorman for my application. | [ ] | [ ]  |
