# Outcome - Fat Code Refactoring Techniques

Skill Description
----------
It is very important that we know how to refactor code. This outcome touches on some best practices as well as refactoring techniques that are useful while building a rails application.

Outputs
----------
- Write a blog post on refactoring techniques.
- Implement these techniques in checkpoints and simulation projects.

----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| Why do we need to follow best practices?| [ ] | [ ] |
| Objectives of refactoring code:| | |
| <ul><li>DRY| [ ] | [ ] |
| <ul><li>Easy to test| [ ] | [ ] |
| <ul><li>Clarity| [ ] | [ ] |
| <ul><li>Easy to find| [ ] | [ ] |
| <ul><li>Easy to change| [ ] | [ ] |
| Refactoring techniques:| | |
| **Concerns**| | |
| <ul><li>Why Concerns?| [ ] | [ ] |
| <ul><li>What are Concerns?| [ ] | [ ] |
| <ul><li>How to use Concerns.| [ ] | [ ] |
| <ul><li>Advantages of Concerns.| [ ] | [ ] |
| <ul><li>Disadvantages of Concerns.| [ ] | [ ] |
| **Draper Decorators**| | |
| <ul><li>Why Draper Decorators?| [ ] | [ ] |
| <ul><li>What are Draper Decorators?| [ ] | [ ] |
| <ul><li>How to use Draper Decorators.| [ ] | [ ] |
| <ul><li>Advantages of Draper Decorators.| [ ] | [ ] |
| <ul><li>Disadvantages of Draper Decorators.| [ ] | [ ] |
| <ul><li>Using the Draper gem.| [ ] | [ ] |
| <ul><li>Applicable situations.| [ ] | [ ] |
| **Presenters**| | |
| <ul><li>Why Presenters?| [ ] | [ ] |
| <ul><li>What are Presenters?| [ ] | [ ] |
| <ul><li>How to use Presenters.| [ ] | [ ] |
| <ul><li>Advantages of Presenters.| [ ] | [ ] |
| <ul><li>Disadvantages of Presenters.| [ ] | [ ] |
| <ul><li>Applicable situations| [ ] | [ ] |
| <ul><li>Move logic to models.| [ ] | [ ] |
| <ul><li>Split up controllers| [ ] | [ ] |
| <ul><li>Validation Classes| [ ] | [ ] |
| <ul><li>Partials| [ ] | [ ] |
| Decompose large models:| | |
| <ul><li>Service objects| [ ] | [ ] |
| <ul><li>Value objects| [ ] | [ ] |
| <ul><li>Form objects| [ ] | [ ] |
| <ul><li>Query objects| [ ] | [ ] |
| <ul><li>Policy objects| [ ] | [ ] |
| KISS (Keep it simple stupid):| | |
| <ul><li>Methods < 5 lines| [ ] | [ ] |
| <ul><li>Classes < 100 lines| [ ] | [ ] |
| <ul><li>One instance variable in view| [ ] | [ ] |
| Presenters versus Decorators.| [ ] | [ ] |

----------


## **Behaviors**


| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When I have a huge model file or an even larger spec file... **Action:** I break up the model and spec using Rails concerns. | [ ] | [ ]  |
| **Context:** When I have a huge model file or an even larger spec file... **Action:** I break up the model and spec logically and by domain.| [ ] | [ ]  |
| **Context:** When I have duplicated code in two or more models... **Action:** I come up with a concern that applies to the models.| [ ] | [ ]  |
| **Context:** When I need to interact with multiple models in order to perform an action... **Action:** I use service objects.| [ ] | [ ]  |
| **Context:** When I have presentation code in model or model concerns... **Action:** I move the presentation code into a Draper Decorator for the model.| [ ] | [ ]  |
| **Context:** When you have an attribute or small group of attributes that have logic associated with them... **Action:** I create a value object for the attribute(s).| [ ] | [ ]  |
| **Context:** When I have complex action that reaches across multiple models and the action is not a core concern of the underlying model... **Action:** I use service object.| [ ] | [ ]  |
| **Context:** When I have multiple ActiveRecord models that will be updated by a single form submission... **Action:** I use form object to encapsulate aggregation.| [ ] | [ ]  |
| **Context:** When I have presentation code relating to one model but multiple controllers/views... **Action:** I use move the code into a Draper Decorator.| [ ] | [ ]  |
| **Context:** When I have complex SQL queries littering the definition of my ActiveRecord subclass (either as scopes or class methods)... **Action:** I extract the sql query into query object.| [ ] | [ ]  |
| **Context:** When I want to format complex data for user display... **Action:** I use a Decorator.| [ ] | [ ]  |
| **Context:** When I have duplicated rendering code in several files... **Action:** I use a partial.| [ ] | [ ]  |
| **Context:** When I have a very large presentation code... **Action:** I use partials.| [ ] | [ ]  |
| **Context:** When I have too many instance variables in the controller action... **Action:** I create a Presenter/View Objects to wrap up the values and logic going from the controller to the view.| [ ] | [ ]  |
| **Context:** When I have a controller file that is huge with many actions and many private methods... **Action:** I split up the controller into multiple files by having the routing file map to different controllers.| [ ] | [ ]  |
| **Context:** When I have excessive model logic in a complicated controller method... **Action:** I move model logic out of the controller and into the models.| [ ] | [ ]  |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Don’t invent patterns that don’t need to be invented.| [ ] | [ ]  |
| World class developers KISS.| [ ] | [ ]  |
