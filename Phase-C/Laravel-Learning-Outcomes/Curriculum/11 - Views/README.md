# Outcome 8 - Views

Skill Description
----------
The view is really the simplest part of the MVC structure -- at the basic level, it's just a bunch of HTML boilerplate into which you insert the variables you've received from your controller and which will be sent to the browser. It's your actual "webpage". Views live in the `resources/views` directory , where `name_of_page.blade.php` is the corresponding naming template for the view file.

Outputs
----------
In checkpoints and simulation project:
- make use of views (you have no choice)
- make use of laravel view rendering shortcut
- appropriately make use of view templates and partials

Write a blog post about using blade template view files in laravel.



----------

## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| I can clearly explain from memory what a layout page do | [ ] | [ ]  |
| I can differentiate between a view partial and a view template | [ ] | [ ]  |
| I can differentiate between a "view template" and a `layout` | [ ] | [ ]  |
| I can differentiate between a “view partial” and  a `layout` | [ ] | [ ]  |
| I know what the outputted file type of a preprocessed `.blade.php` and  `.css.scss` file are | [ ] | [ ]  |
| I know the difference between the {!! !!} and {{{ }}} tags | [ ] | [ ]  |
| I know how to insert a partial into a view?| [ ] | [ ]  |
| I know how to tell a `view template` from a `view partial` | [ ] | [ ]  |
| I know how to share data with all views | [] | [] |
| I know how to ascertain the existence of a view before passing data to it | [] | [] |
| I know how to pass a local variable to a partial | [ ] | [ ]  |
| I know what View composers are used for | [ ] | [ ]  |
| I know how add custom blade methods to the list of existing blade methods in a laravel application. | [ ] | [ ]  |
| I know users interact with a web application through the views | [ ] | [ ]  |

----------

## **Behaviors**


| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When a building a laravel application... **Action:** I always have a layout page. | [ ] | [ ]  |
| **Context:** When I have similar html code block in multiple views... **Action:** I abstract the code block into a view partial. | [ ] | [ ]  |
| **Context:** When rendering a partial... **Action:** I always make use of laravel shorthand syntax.e.g “@include('layouts.partials.sidebar')”. | [ ] | [ ]  |
| **Context:** When working with view files... **Action:** I make use of the appropriate template extensions. E.g. “.blade.php” | [ ] | [ ]  |
| **Context:** When building a laravel application... **Action:** I add common assets to the layout file. | [ ] | [ ]  |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Views are the eyes to the soul of a laravel application. | [ ] | [ ]  |
| View composers are used to organize logic that needs to be bound to a view each time that view is rendered | [ ] | [ ]  |
| I am not limited to the default template engine (blade) that laravel provides. | [ ] | [ ]  |
