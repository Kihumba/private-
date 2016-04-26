# Outcome 5 - Django Models

**Skill Description**
----------
To show complete understanding of Django Models skill, one must have an understanding of the following:

- Model Manipulation
- Django Admin


**Output**
----------
After attaining this skill, and as a demonstration of it, a person should be able to do the following:

1. Model a database using the Django Model ORM
  - Implement relationships
  - Create a Django Admin interface for working with the models.


**Objectives**
----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| General Django model structure as being a collection of class variables representing corresponding table fields | [ ] | [ ] |
| The `ForeignKey()` class and syntax for using it to create foreign key relationships between tables | [ ] | [ ] |
| Common model relationships implemented natively within the Django Model ORM | [ ] | [ ] |
| What Signals and Recievers are | [ ] | [ ] |
| Functions available for making simple database queries using the Django Model ORM in the views - `get()`, `all()`, `filter()`, `limit()` | [ ] | [ ] |
| Identify **Querysets** as return value of Django queries | [ ] | [ ] |
| Common filter parameters available for the `filter()` function | [ ] | [ ] |
| Django Aggregation functions - `annotate()` and `aggregate()` - their uses and parameters  | [ ] | [ ] |
| Syntax for registering multiple models on the admin site | [ ] | [ ] |
| Common Django Admin field types and their parameters | [ ] | [ ] |


----------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When I want to start working on an application... **Action:** I ensure to model my data in an extremely detailed manner before I begin coding. | [ ] | [ ] |
| **Context:** When defining a Django model... **Action:** I use the appropriate model field types available in Django. | [ ] | [ ] |
| **Context:** When I want to create model relationships... **Action:** I use one of the relationships classes or `ForeignKey()` to define the relationship. | [ ] | [ ] |
| **Context:** When I want to query my database... **Action:** I use Django's Model ORM functions. | [ ] | [ ] |
| **Context:** When I need to access a model's related child objects... **Action:** I use the `related_set` syntax. | [ ] | [ ] |
| **Context:** When I need to make complex queries beyond what the `filter` syntax provides... **Action:** I use the `Q` function. | [ ] | [ ] |
| **Context:** When I need to make complex queries beyond what Django's ORM provides... **Action:** I use raw SQL queries using the `raw` function. | [ ] | [ ] |
| **Context:** When I want to create automated actions that execute for specific database operations... **Action:** I create a receiver function to respond to the signal triggered by the database operation. | [ ] | [ ] |
| **Context:** After I've created my data models... **Action:** I configure my DjangoAdmin to enable me easily access and manipulate data objects. | [ ] | [ ] |
| **Context:** Before I try to access DjangoAdmin... **Action:** I create superuser account using `manage.py createsuperuser` command | [ ] | [ ] |
| **Context:** When I'm configuring DjangoAdmin... **Action:** I register all the models I would like to have access to on the Admin site in `admin.py`. | [ ] | [ ] |
| **Context:** When I'm configuring DjangoAdmin... **Action:** I ensure that I am as detailed as possible to give me optimum control for the data objects from the interface. | [ ] | [ ] |



----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Using Django's ORM I am able to effectively manipulate any records in my database. | [ ] | [ ]  |
| Django Admin gives me optimum control of my database records. | [ ] | [ ]  |
| I can choose to use Django Admin as primary administrative interface for my application if well configured. | [ ] | [ ]  |
