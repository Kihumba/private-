# Routing and Middleware

Skill Description
----------
The router is the doorman of your application. When an HTTP request arrives from the user's browser, it needs to know which controller action (method) should be run. Should we display the "new user" web page? Should we edit an existing user with whatever data got sent along? etc. The router basically match HTTP request to the appropriate action.

Outputs
----------
In checkpoint 3:
- Use Slim Routes and Middleware in building out an API

In checkpoint 4 :
- Use route helper methods
- Make use of routes and middleware in building out the project.


----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| What are Middlewares used for? | [ ] | [ ]  |
| I can clearly describe  |  |   |
| <ul><li> A Controller Middleware </li></ul>  | [ ] | [ ]  |
| <ul><li> A Route Middleware </li></ul>  | [ ] | [ ]  |
| I know which routing resource share the same url but use different verbs | [ ] | [ ]  |
| I know how to specify an ID or other variables in a route | [ ] | [ ]  |
| I know what `php artisan route:list` command is used for | [ ] | [ ]  |
| I understand the purpose of route helper methods, including | [ ] | [ ]  |
| <ul><li> Knowing the laravel helper method that creates the HTML for links | [ ] | [ ]  |
| <ul><li> Knowing how path and url helpers differ| [ ] | [ ]  |
| I know how to group a set of routes | [ ] | [ ]  |
| I understand the importance of naming routes, including | [ ] | [ ]  |
| <ul><li> The convention used to name routes | [ ] | [ ]  |
| <ul><li> How to explicitly name routes | [ ] | [ ]  |
| I understand the importance of route resources, including: | [ ] | [ ]  |
| <ul><li> How to easily write all seven RESTful routes in Laravel | [ ] | [ ]  |
| <ul><li> How to limit the restful routes created by resources | [ ] | [ ]  |
| <ul><li> How to create nested resources | [ ] | [ ]  |
| <ul><li> When to use nested resources | [ ] | [ ]  |


----------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When building a laravel application... **Action:** I specify routes for the application. | [ ] | [ ]  |
| **Context:** When I want to limit routes to specific users ... **Action:** I use a middleware | [ ] | [ ]  |
| **Context:** When I need to create all seven restful route for a resource... **Action:** I use the `resource` method. | [ ] | [ ]  |
| **Context:** When adding links to my views... **Action:** I use route helper methods as against adding the raw link. | [ ] | [ ]  |
| **Context:** When defining routes for an application that does not have a controller action... **Action:** I use a callback | [ ] | [ ]  |
| **Context:** When I want to know the different routes supported by my application... **Action:** I use the `php artisan route:list` command. | [ ] | [ ]  |
| **Context:** When building out an API... **Action:** I prefix my routes and group them with the route `group` method. | [ ] | [ ]  |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Grouping similar routes together eliminates code duplication | [ ] | [ ]  |
| Middlewares are excellent components in intercepting Http requests made to routes to perform specific actions. | [] | [] |
| I can dry up links using route helper methods. | [ ] | [ ]  |
| I can do more with less using route resources. | [ ] | [ ]  |
