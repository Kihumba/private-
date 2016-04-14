# Outcome 4 - Django MVT Basics

**Skill Description**
----------
To show complete understanding of Django Basics skill, one must have an understanding of the following:

- Setup and Django Command Line basics
- Model Basics
- URL Routing and View Functions


**Output**
----------
After attaining this skill, and as a demonstration of it, a person should be able to do the following:

1. Complete the blog tutorial on the Django documentation


**Objectives**
----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| Creating a Django Project using the `django-admin` command line | [ ] | [ ] |
| Commonly used commands for Django's `manage.py` - `runserver`, `migrate`, `createmigrations`, `createsuperuser`, `startapp` - and when to use them | [ ] | [ ] |
| Difference between apps and projects | [ ] | [ ] |
| Django's default architecture and components | [ ] | [ ] |
| Request-Response flow of a Django application | [ ] | [ ] |
| Accessing and modifying common settings for Django app | [ ] | [ ] |
| Creating data models | [ ] | [ ] |
| Common model fields and their parameters | [ ] | [ ] |
| Creating and applying database migrations using the command line | [ ] | [ ] |
| Setting up project-wide and app-specific routes | [ ] | [ ] |
| URL setup regular expression syntax | [ ] | [ ] |
| View function creation syntax | [ ] | [ ] |
| Returning response from the view | [ ] | [ ] |
| Mapping URLs to view functions using the `url` function | [ ] | [ ] |


----------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When I want to start a Django project... **Action:** I create the project from the command line using the `django-admin.py startproject <project_name>` command. | [ ] | [ ] |
| **Context:** When I want to create apps within that project... **Action:** I use the `manage.py startapp <app_name>` command. | [ ] | [ ] |
| **Context:** When creating a Django project... **Action:** I divide my functionality into apps based on context e.g `authentication`, `books`, `orders`, `transactions` etc. | [ ] | [ ] |
| **Context:** When I create an app... **Action:** I add it to the `INSTALLED_APPS` list within the project settings file. | [ ] | [ ] |
| **Context:** When I want to run my application... **Action:** I do so using the `manage.py runserver <port_number>` command. | [ ] | [ ] |
| **Context:** When I want to create a new action within an app... **Action:** I start by creating a URL in the app's `urls.py` file. | [ ] | [ ] |
| **Context:** When I create a new url for my app... **Action:** I create a corresponding view function in the app's `views.py` file, import the function into the `urls.py` file and link it to the url using the `url` function. | [ ] | [ ] |
| **Context:** When I need to access my database... **Action:** I do so through my data models defined in `models.py`. | [ ] | [ ] |
| **Context:** When I want to create data models for my application... **Action:** I define the model fields and parameters in the `models.py` file of the app. | [ ] | [ ] |
| **Context:** When I create a new data model in my app... **Action:** I create and run migrations to apply the changes to my database. | [ ] | [ ] |
| **Context:** When I am creating routes for my app... **Action:** I specify project-wide routes in the project's `urls.py` and app-specific routes in the app's `urls.py`. | [ ] | [ ] |
| **Context:** When I need to access database data from my view function... **Action:** I import the model and perform the database using the ORM functions within the view functions. | [ ] | [ ] |



----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| I can create any simple MVT applications using Django. | [ ] | [ ]  |
| Django's architecture gives me a good foundation for developing large applications. | [ ] | [ ]  |
| Developing applications using the MVT architecture makes my application easy to maintain in the long run. | [ ] | [ ]  |
| Django is a powerful tool for creating extremely robust and scalable web applications. | [ ] | [ ]  |
