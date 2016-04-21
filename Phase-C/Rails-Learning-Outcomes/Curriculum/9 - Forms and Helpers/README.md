# Outcome 9 - Forms and Helpers

Skill Description
----------
Forms are possibly the most complicated thing about learning web development. Not necessarily because the code itself is difficult, but because you usually want to build forms that accomplish so many different things at once.

Understanding how forms are created in HTML and then how Rails offers you some helpers to make your life easier will go a long way.

Outputs
----------
In checkpoint two and simulation project:
- use helper methods to make your views DRY and clean.


----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| I can describe what helpers are | [ ] | [ ]  |
| I know how to make a helper method out of a controller method | [ ] | [ ]  |
| I know of the following helper methods: | [ ] | [ ]  |
| <ul><li> form_tag | [ ] | [ ]  |
| <ul><li> select_tag | [ ] | [ ]  |
| <ul><li> form_for | [ ] | [ ]  |
| <ul><li> select | [ ] | [ ]  |
| <ul><li> image_tag | [ ] | [ ]  |
| <ul><li> javascript_include_tag | [ ] | [ ]  |
| <ul><li> stylesheet_link_tag | [ ] | [ ]  |
| <ul><li> content_tag | [ ] | [ ]  |
| <ul><li> current_page? | [ ] | [ ]  |
| <ul><li> link_to | [ ] | [ ]  |
| <ul><li> url_for | [ ] | [ ]  |
| <ul><li> Sanitize | [ ] | [ ]  |
| <ul><li> distance_of_time_in_words | [ ] | [ ]  |
| I know how to view what was submitted by a form | [ ] | [ ]  |
| I know what a CSRF Token is and why is it necessary | [ ] | [ ]  |
| I know how to generate CSRF token in Rails | [ ] | [ ]  |
| I know why the name attribute of a form input element is so important | [ ] | [ ]  |
| I know how to nest attributes under a single hash in params and why it is useful| [ ] | [ ]  |
| I know what to add/modify in my controller to handle nested params | [ ] | [ ]  |
| I know what special tags Rails form_tag helper gives to me | [ ] | [ ]  |
| I can differentiate between form_tag and form_for helpers | [ ] | [ ]  |
| I can differentiate between form_tag and form_for helpers | [ ] | [ ]  |
| I know how to access errors on a failed-to-save model object | [ ] | [ ]  |
| I  know which form helper automatically adds markup around errors | [ ] | [ ]  |
| I know how to access Update or Delete actions with a form | [ ] | [ ]  |
| I know how to pre populate a dropdown menu with data | [ ] | [ ]  |
| I can differentiate between the select_tag helper and the select helper | [ ] | [ ]  |
| I know what format the array to input to options_for_select need to be in| [ ] | [ ]  |
| I know why I would need to use a nested form | [ ] | [ ]  |
| I know what I need to change in the model to allow nested forms to create new objects properly | [ ] | [ ]  |
| I know how to whitelist the nested parameters properly in my controller | [ ] | [ ]  |



----------


## **Behaviors**


| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When building a rails application... **Action:** I use helpers to extract complex logic out of my views. | [ ] | [ ]  |
| **Context:** When I want to use a helper in a controller and view... **Action:** I define the method as a controller instance method and use helper_method to convert the instance method to a helper method eg current_user helper method.. | [ ] | [ ]  |
| **Context:** When building a form based on an activerecord model... **Action:** I use form_for helper method. | [ ] | [ ]  |
| **Context:** When building forms manually(without using form_tag or form_for helper method)... **Action:** I always add authentication_token using form_authenticity_token helper method. | [ ] | [ ]  |
| **Context:** When working with forms,... **Action:** I always display error messages when the form fail to save. | [ ] | [ ]  |



----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Using helpers improves development speed. | [ ] | [ ]  |
| Helpers keep our views clean and DRY. | [ ] | [ ]  |
| Helpers help make view logic easier to test. | [ ] | [ ]  |
