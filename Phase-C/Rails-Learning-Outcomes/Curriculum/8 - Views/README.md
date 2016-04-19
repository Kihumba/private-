# Outcome 8 - Views

Skill Description
----------
The view is really the simplest part of the MVC structure -- at the basic level, it's just a bunch of HTML boilerplate into which you insert the variables you've received from your controller and which will be sent to the browser. It's your actual "webpage". Views live in the directory `app/views/controller_name/action_name.html.erb`, where `controller_name` is the name of the controller the view is linked to and `action_name.html.erb` is the corresponding method inside the controller that was run immediately prior to rendering the view.

Outputs
----------
In checkpoints and simulation project:
- make use of views (you have no choice)
- make use of magical rails rendering shortcut
- appropriately make use of view templates and partials

Write a blog post about preprocessors in rails.



----------

## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| I can clearly explain from memory what a layout page do | [ ] | [ ]  |
| I can differentiate between a view partial and a view template | [ ] | [ ]  |
| I can differentiate between a "view template" and a `layout` | [ ] | [ ]  |
| I can differentiate between a “view partial” and  a `layout` | [ ] | [ ]  |
| I can clearly describe `Preprocessor`, including why they are useful | [ ] | [ ]  |
| I can explain how to make sure a preprocessor runs on a rails file | [ ] | [ ]  |
| I know what the outputted filetype of a preprocessed `.html.erb ` and  `.css.scss` file are | [ ] | [ ]  |
| I know the difference between the <%= and <% tags | [ ] | [ ]  |
| I know how to insert a partial into a view?| [ ] | [ ]  |
| I know how to tell a `view template` from a `view partial` | [ ] | [ ]  |
| I know how to pass a local variable to a partial | [ ] | [ ]  |
| I know the magical Rails shortcut for rendering `a user`, `a bunch of users` | [ ] | [ ]  |
| I know what asset tags are and why are they used | [ ] | [ ]  |
| I know how to use other template engines in a rails application. | [ ] | [ ]  |
| I know users interact with a web application through the views | [ ] | [ ]  |

----------

## **Behaviors**


| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When a building a rails application... **Action:** I always have a layout page. | [ ] | [ ]  |
| **Context:** When I have similar html code block in multiple views... **Action:** I abstract the code block into a view partial. | [ ] | [ ]  |
| **Context:** When rendering a partial... **Action:** I always make use of rails shorthand syntax.e.g “render @users”. | [ ] | [ ]  |
| **Context:** When working with view files... **Action:** I make use of the appropriate template extensions. E.g. “.erb”, “.slim”, etc. | [ ] | [ ]  |
| **Context:** When building a rails application... **Action:** I add common assets to the layout file. | [ ] | [ ]  |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Views are the eyes to the soul of a rails application. | [ ] | [ ]  |
| Preprocessors are indispensable | [ ] | [ ]  |
| I am not limited to the default template engine (erb) that rails provides. | [ ] | [ ]  |
