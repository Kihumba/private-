# Outcome - Events

Skill Description
----------
The Fellow uses callbacks to execute code at specific times in the life cycle of an object (just before it is created, after it is saved, after it is destroyed, after an action is executed, before an action is executed, etc). 


Outputs
----------
After attaining this skill, and as a demonstration of it, I should be able to create an app that makes use of the controller filter for authorizing controller actions and cleaning up data. 

----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| The definition of callbacks and what they are used for | [ ] | [ ]  |
| The relationship with callbacks and filters | [ ] | [ ]  |
| The major lifecycle stages of an Active Record object | [ ] | [ ]  |
| Hoe to build an "around" callback | [ ] | [ ]  |
| How to specify a particular action to run a callback for | [ ] | [ ]  |
| The most commonly used controller filters | [ ] | [ ]  |
| The most commonly used ActiveRecord callback functions | [ ] | [ ]  |
| How to register a Controller filter function or an ActiveRecord callback function | [ ] | [ ]  |
| How to register a conditional Controller filter function or ActiveRecord callback function | [ ] | [ ]  |



----------


## **Behaviors**


| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When I need a method executed before or after an action **Action:** I use before filter/callback  | [ ] | [ ]  |
| **Context:** Before using a callback/filter **Action:** I always register it. | [ ] | [ ]  |
| **Context:** When I need to execute a callback/filter based on some condition **Action:** I use conditional filter  | [ ] | [ ]  |
| **Context:** When I need to call a controller filter method for specific controller actions **Action:** I use :only option when registering the filter  | [ ] | [ ]  |
| **Context:** When I need to call a controller filter method for all controller actions except some specific ones **Action:** I use :except option when registering the filter  | [ ] | [ ]  |
| **Context:** When I only want to run an ActiveRecord callback when a particular controller action calls it **Action:** I use :on option when registering the callback  | [ ] | [ ]  |
| **Context:** When I need to run an ActiveRecord callback before and after model validations **Action:** I use `before_validation` and `after_validation` methods  | [ ] | [ ]  |
| **Context:** When I need to run an ActiveRecord callback before and after model creation **Action:** I use `before_create` and `after_create` methods  | [ ] | [ ]  |
| **Context:** When I need to run an ActiveRecord callback before and after saving a model **Action:** I use `before_save` and `after_save` methods  | [ ] | [ ]  |
| **Context:** When I need to run an ActiveRecord callback before and after deleting a record **Action:** I use `before_destroy` and `after_destroy` methods  | [ ] | [ ]  |
| **Context:** When I want an ActiveRecord callback chain to be halted **Action:** I return false or raise an exception in any of the registered callback methods  | [ ] | [ ]  |



----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Callbacks are a way of saying, "Hey Active Record! Give me a call so I can run this method at the right time!" | [ ] | [ ]  |
| Callback classes are easy to test in isolation | [ ] | [ ]  |
