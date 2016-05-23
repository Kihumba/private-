# Outcome - Callbacks and Filters

Skill Description
----------
Callbacks are a common way for you to execute code at specific times in the life cycle of an object, for instance just before it is created, after it is saved, after it is destroyed, after an action is executed, before an action is executed, etc. These can be very useful if you've got something to execute whenever an object hits one of those lifecycle points, like modifying the user's email to be lowercase when creating her account. Callbacks are a way of saying something like "Hey Active Record", when you've finished creating a new User object, give me a call so I can run this method before anything else happens or "Hey Controller" before you execute this controller action, give me a call so I can run this method before anything else happens.

Callbacks used in rails controllers are called filters.

Outputs
----------
In checkpoints and simulation project:
- make use of controller filter for authorizing controller actions and cleaning up data
- make use of ActiveRecord callback functions


----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| I know what callbacks are used for | [ ] | [ ]  |
| I know the major lifecycle stages of an Active Record object | [ ] | [ ]  |
| I know how do you build an "around" callback | [ ] | [ ]  |
| I know how to specify a particular action to run a callback for | [ ] | [ ]  |
| I know the following controller filters | [ ] | [ ]  |
| <ul><li> before_action| [ ] | [ ]  |
| <ul><li> after_action| [ ] | [ ]  |
| <ul><li> around_action| [ ] | [ ]  |
| I know the following ActiveRecord callback functions | [ ] | [ ]  |
| <ul><li> before_create | [ ] | [ ]  |
| <ul><li> after_create | [ ] | [ ]  |
| <ul><li> before_save | [ ] | [ ]  |
| <ul><li> after_save | [ ] | [ ]  |
| <ul><li> before_validation | [ ] | [ ]  |
| <ul><li> after_validation | [ ] | [ ]  |
| <ul><li> before_destroy | [ ] | [ ]  |
| <ul><li> after_destroy | [ ] | [ ]  |
| I know how to register a Controller filter function or an ActiveRecord callback function | [ ] | [ ]  |
| I know how to register a conditional Controller filter function or ActiveRecord callback function | [ ] | [ ]  |



----------


## **Behaviors**


| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When I need a method executed before an action... **Action:** I use before filter/callback  | [ ] | [ ]  |
| **Context:** When I need a method executed after an action... **Action:** I use after filter/callback  | [ ] | [ ]  |
| **Context:** When I need a method which actually yield's at some point to the original action... **Action:** I use around filter/callback  | [ ] | [ ]  |
| **Context:** Before using a callback/filter... **Action:** I always register it. | [ ] | [ ]  |
| **Context:** When I need to execute a callback/filter based on some condition... **Action:** I use conditional filter  | [ ] | [ ]  |
| **Context:** When I need to call a controller filter method for specific controller actions... **Action:** I use :only option when registering the filter  | [ ] | [ ]  |
| **Context:** When I need to call a controller filter method for all controller actions except some specific ones... **Action:** I use :except option when registering the filter  | [ ] | [ ]  |
| **Context:** When I only want to run an ActiveRecord callback when a particular controller action calls it... **Action:** I use :on option when registering the callback  | [ ] | [ ]  |
| **Context:** When I need to run an ActiveRecord callback before and after model validations... **Action:** I use `before_validation` and `after_validation` methods  | [ ] | [ ]  |
| **Context:** When I need to run an ActiveRecord callback before and after model creation... **Action:** I use `before_create` and `after_create` methods  | [ ] | [ ]  |
| **Context:** When I need to run an ActiveRecord callback before and after saving a model... **Action:** I use `before_save` and `after_save` methods  | [ ] | [ ]  |
| **Context:** When I need to run an ActiveRecord callback before and after deleting a record... **Action:** I use `before_destroy` and `after_destroy` methods  | [ ] | [ ]  |
| **Context:** When I want an ActiveRecord callback chain to be halted... **Action:** I return false or raise an exception in any of the registered callback method  | [ ] | [ ]  |



----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Callbacks help keep our code organize | [ ] | [ ]  |
| Callbacks are used for cleaning up attribute formatting eg. before_validation on Create | [ ] | [ ]  |
| Callback classes are easy to test in isolation | [ ] | [ ]  |
| All callback methods must be registered  | [ ] | [ ]  |
| Callbacks provide hooks into specific points in the life cycle of an object  | [ ] | [ ]  |
