# Outcome 6 - Django Views

**Skill Description**
----------
To show complete understanding of Django Views skill, one must have an understanding of the following:

- Function-Based Views
- Class-Based Views
- Sessions
- Flash Messaging
- Forms
- Authentication


**Output**
----------
After attaining this skill, and as a demonstration of it, a person should be able to do the following:

1. Create view functions to communicate with the database
2. Create view functions that output data to the user
3. Create view functions that render templates
4. Create view functions that render templates with data
5. Create forms and perform validation in Django
6. Build a user authentication system using Django


**Objectives**
----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| Difference between Function-Based Views and Class-Based Views | [ ] | [ ] |
| Syntax for creating routes that point to either FBVs or CBVs | [ ] | [ ] |
| Common Generic Class-Based Views | [ ] | [ ] |
| Commonly used Django shortcuts - `render()`, `redirect()`, `get_object_or_404()` | [ ] | [ ] |
| Syntax for setting and accessing Django Session data | [ ] | [ ] |
| Syntax for setting and accessing Flash messages in Django | [ ] | [ ] |
| Common Django Form Fields | [ ] | [ ] |
| Django Model forms - What they are and how to use them | [ ] | [ ] |
| Methods used for authentication in Django - `authenticate()` and `login` | [ ] | [ ] |
| Access control in Django using `LoginRequiredMixin` for CBVs and `@login_required` decorators for FBVs | [ ] | [ ] |


----------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When I want to create route that points to a view function... **Action:** I import the view function into the routes file and pass it as the `view` parameter of the `url()` function. | [ ] | [ ] |
| **Context:** When I want to communicate with my database within the view... **Action:** I import the models I need within the view file to enable me perform queries. | [ ] | [ ] |
| **Context:** When I want my view to render a static template... **Action:** I use the shortcut `render` function | [ ] | [ ] |
| **Context:** When I need to pass data into the template from the view... **Action:** I pass it as the `context` variable for the `render` function | [ ] | [ ] |
| **Context:** When I am writing a Class-Based View that renders a static page... **Action:** I use a subclass of the `TemplateView` class | [ ] | [ ] |
| **Context:** When using a `TemplateView` to render pages that have context data... **Action:** I override the `get_context_data()` function within my `TemplateView` subclass. | [ ] | [ ] |
| **Context:** When creating application that entail simple CRUD operations... **Action:** I leverage on Django's CRUD and Form views - `ListView`, `DetailView`, `CreateView`, `DeleteView` etc. | [ ] | [ ] |
| **Context:** When I need to set data I want to persist on the server while a user is using my application... **Action:** I add the variable to the `request.session` dictionary. | [ ] | [ ] |
| **Context:** When I want to set data I want to persist for just the next request, like status messages... **Action:** I set the message as a flash message using the `messages.add_messages()` function available in `django.contrib`. | [ ] | [ ] |
| **Context:** When I am setting flash messages... **Action:** I take advantage of message context like success, error, info and warning to make it easier to display messages in the proper format within my view. | [ ] | [ ] |
| **Context:** When I need to validate multiple data fields at once... **Action:** I make use of Django forms. | [ ] | [ ] |
| **Context:** When I want to create a form to use to validate my data... **Action:** I create the form within `forms.py` in my app or as a module within a forms directory in my app folder (Depending on how large the app is - The later is optimum for larger apps). | [ ] | [ ] |
| **Context:** When I want to create a form to use to validate my data... **Action:** I carefully specify each field that I'm expecting from the user using the appropriate data types provided by the Forms framework. | [ ] | [ ] |
| **Context:** When I want to create a form that is linked to my model... **Action:** I make use of ModelForms to make the process easier. | [ ] | [ ] |
| **Context:** When creating a form... **Action:** I specify custom validation logic within the form class. | [ ] | [ ] |
| **Context:** When I want to validate my form data... **Action:** I ensure to call the `is_valid()`. | [ ] | [ ] |
| **Context:** After I validate my form data... **Action:** I save the fields only if the form data is valid. | [ ] | [ ] |
| **Context:** When I want to ensure that a user is registered on my application... **Action:** I use the `authenticate()` method available in `django.contrib.auth`. | [ ] | [ ] |
| **Context:** When I want to login a user and add him to the current session... **Action:** I use the `login()` method available in `django.contrib.auth`. | [ ] | [ ] |
| **Context:** When I want to register a new user using the Django Authentication system... **Action:** I import the Django in-built `User` model and call its `objects.create_user()` method with the user's name, username and password. | [ ] | [ ] |
| **Context:** When I want to implement access control on my Django app... **Action:** I use the `LoginRequiredMixin` for CBVs and the `@login_required` decorator for FBVs. | [ ] | [ ] |
| **Context:** When I want to check to make sure a user is actually logged in... **Action:** I use `request.user.is_authenticated()` method. | [ ] | [ ] |



----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| I express my full control of what my users experience within my Django views . | [ ] | [ ]  |
| The more robust my logic is the more satisfied my users are. | [ ] | [ ]  |
| Django provides most of what I need to be a successful web developer. | [ ] | [ ]  |
| I am the only person that can limit how much I can create using Django as my main tool of choice. | [ ] | [ ]  |
| I use higher level abstractions when working with Views and Forms in Django because it usually mimics common actions I would perform as a developer. | [ ] | [ ]  |
