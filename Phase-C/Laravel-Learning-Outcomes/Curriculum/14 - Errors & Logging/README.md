# Outcome - Errors and Logging

Skill Description
----------
This outcome touches on Logging, Error and Exception Handling. Laravel provides support for a variety of powerful log handlers.

Outputs
----------
- In checkpoint four and simulation project, make use of exception handling techniques and Loggers.
- Write a blog post on Error Handling and Logging in Laravel.


----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| I know how to handle Exceptions using the `report` and `render` methods in the `App\Exceptions\Handler` class. | [ ] | [ ]  |
| I know how to set up custom HTTP Error Pages. | [ ] | [ ]  |
| I can use the `Log` Facade to log different kinds of error | [ ] | [ ] |
| <ul><li> Log::emergency($error) </li></ul> | [ ] | [ ]  |
| <ul><li> Log::alert($error) </li></ul> | [ ] | [ ]  |
| <ul><li> Log::critical($error) </li></ul> | [ ] | [ ]  |
| <ul><li> Log::error($error) </li></ul> | [ ] | [ ]  |
| <ul><li> Log::warning($error) </li></ul> | [ ] | [ ]  |
| <ul><li> Log::notice($error) </li></ul> | [ ] | [ ]  |
| <ul><li> Log::info($error) </li></ul> | [ ] | [ ]  |
| <ul><li> Log::debug($error) </li></ul> | [ ] | [ ]  |
| I know error logs are stored in the `storage/logs` directory | [ ] | [ ] |
| I can configure logs to be stored externally in services such as Bugsnag. | [ ] | [ ]  |
| I can configure different modes for logging such as `daily`, `single`, `syslog` and `errorlog` | [ ] | [ ] |



----------


## **Behaviors**


| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When building an application in development environment... **Action:** I set the APP_DEBUG environment variable to true. | [ ] | [ ]  |
| **Context:** When running an application in production... **Action:** I check the log files for silent failures, errors and exceptions. | [ ] | [ ]  |
| **Context:** When I don't need a certain exception to be logged.. **Action:** I use the `$dontReport` property of the Exception Handler. | [ ] | [ ]  |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Well-written applications will log all activities and error traces for audit and monitoring.  | [ ] | [ ]  |
| Log files provides detailed information about errors happening in your application. | [ ] | [ ]  |
| Applications should always fail safe. Structured Exception handling and functional error checking aids in building such applications. | [ ] | [ ]  |
