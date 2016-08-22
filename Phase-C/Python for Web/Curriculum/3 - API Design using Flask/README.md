# Outcome 3 - API Design using Flask

**Skill Description**
----------
To show complete understanding of the Flask skill, one must have an understanding of the following:

- Flask Basics, Routing and URLs
- Requests and Responses
- Sessions and Cookies
- Forms
- Error Handling
- Using SQLAlchemy
- Testing Flask Applications


**Output**
----------
After attaining this skill, and as a demonstration of it, a person should be able to do the following:

1. Complete Checkpoint 2


**Objectives**
----------
## **Knowledge**

| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| Initializing a Flask application and the different parameters for running the application. | [ ] | [ ] |
| URL Definition syntax in Flask using the `@app.route()` decorator as well as the `app.add_url_rule()` function. | [ ] | [ ] |
| Reverse URL generation using `url_for()`. | [ ] | [ ] |
| The `request` object attributes and functions. | [ ] | [ ] |
| Different variables that hold request data from JSON, Forms or URL - `request.args`, `request.json` and `request.form`.  | [ ] | [ ] |
| `Response` object anatomy. | [ ] | [ ] |
| Functions used to return different types of output from Flask view functions. | [ ] | [ ] |
| Functions for accessing and modifying session data using the `session` object. | [ ] | [ ] |
| Functions for accessing and modifying cookie data from the request object. | [ ] | [ ] |
| Flask forms as an efficient way to implement validation rules and error handling for user inputted data. | [ ] | [ ] |
| Commonly encountered SQLAlchemy Field types - `StringField`, `IntegerField`, `BooleanField`, `FileField`, `URLField`. | [ ] | [ ] |
| Common Flask-WTF Validators - `DataRequired`, `Length`, `Email`, `EqualTo`, `URL` - to check form data. | [ ] | [ ] |
| Validating form input using the `validate_on_submit()` function. | [ ] | [ ] |
| Special functions available in Flask and what they do - `redirect()` to redirect to other routes, `abort()` to abort a request early . | [ ] | [ ] |
| Creating and using custom exceptions in Flask. | [ ] | [ ] |
| Creating model classes using SQLAlchemy. Inheriting from the base `Model` class | [ ] | [ ] |
| Syntax for creating model fields using the `Column` class | [ ] | [ ] |
| Common model field types and their parameters - `Integer`, `String`, `Boolean`, `DateTime` | [ ] | [ ] |
| `create_all()` and `drop_all()` functions for creating and destroying the database. | [ ] | [ ] |
| Foreign Key relationships in SQLAlchemy and how to implement them using `ForeignKey()` as a parameter when creating a column. | [ ] | [ ] |
| Nested object relationships using the `backref` parameter. | [ ] | [ ] |
| Common SQLAlchemy model methods - `filter()`, `filter_by()`, `get()`, `limit()`, `order_by()`, `all()` - and how to use them appropriately.  | [ ] | [ ] |
| Concept of migrations and using SQLAlchemy-migrate to create database migrations | [ ] | [ ] |
| Using the SQLAlchemy `paginate()` function to create paginated records | [ ] | [ ] |
| Creating a test client for use in test cases | [ ] | [ ] |
| Methods used for making HTTP requests to our test client | [ ] | [ ] |

----------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When creating routes for my Flask API... **Action:** I ensure to properly specify the methods I would like the view function to accept. | [ ] | [ ] |
| **Context:** When creating view functions for my Flask API... **Action:** I use the `request.method` variable to handle different request methods to the same url. | [ ] | [ ] |
| **Context:** When creating links between API methods I define... **Action:** I use the `url_for()` function to create easily readable references to different view functions within my codebase. | [ ] | [ ] |
| **Context:** When I want to access data sent to my API from my client... **Action:** I access it through the `request` object. | [ ] | [ ] |
| **Context:** When I want to access data sent to my API from my client... **Action:** I determine whether to use `request.args`, `request.json` or `request.forms` depending on how the data is sent. | [ ] | [ ] |
| **Context:** When I want to create a custom response object... **Action:** I use the `make_response()` function to create the response object before returning it. | [ ] | [ ] |
| **Context:** When I want to output JSON from my view function... **Action:** I convert to JSON using the `jsonify()` function. | [ ] | [ ] |
| **Context:** When I need to persist data across a session... **Action:** I add it to the Flask `session` dictionary. | [ ] | [ ] |
| **Context:** When I need to validate multiple values at once... **Action:** I use Flask-WTF forms to create validation rules to ensure data is sanitized. | [ ] | [ ] |
| **Context:** When creating Flask-WTF forms... **Action:** I ensure to take advantage of the various field types and parameters to properly specify the data I'm expecting from my client. | [ ] | [ ] |
| **Context:** When I want to validate fields in my form... **Action:** I use the `validate_on_submit()` function for the form. | [ ] | [ ] |
| **Context:** When there's an error during runtime in my Flask API... **Action:** I make use of the `abort()` function to stop the current request cycle. | [ ] | [ ] |
| **Context:** When I anticipate that I will encounter an error multiple times during application execution... **Action:** I create custom error handlers as functions decorated with `@app.errorhandler()` to respond to specific HTTP status codes. | [ ] | [ ] |
| **Context:** When I need to model data to be used in my Flask API... **Action:** I make use of SQLAlchemy to define data models. | [ ] | [ ] |
| **Context:** Before I run my application... **Action:** I ensure to run `create_all()` at least once to ensure my database is constructed from my models. | [ ] | [ ] |
| **Context:** When I need to refresh my database to reflect the new changes in my models... **Action:** I ensure to run `drop_all()` to delete the entire database and `create_all() to recreate it`. | [ ] | [ ] |
| **Context:** When creating data models using SQLAlchemy... **Action:** I ensure to use the right field types specific to the data being stored in the database. | [ ] | [ ] |
| **Context:** When I want to create Foreign key relationships between fields... **Action:** I use the `ForeignKey` class and the `backref` attribute to specify the relationship. | [ ] | [ ] |
| **Context:** When I want to indicate a field as primary key... **Action:** I specify `primary_key=True` when constructing the field using the `Column` class. | [ ] | [ ] |
| **Context:** When I need to access data from my view functions... **Action:** I query the database using the SQLAlchemy data models and its functions. | [ ] | [ ] |
| **Context:** When I need to make frequent changes to my data model... **Action:** I use migrations to ensure that my database structure is continuously updated. | [ ] | [ ] |
| **Context:** When my API is returning a lot of data... **Action:** I ensure to paginate the records coming back to the client. | [ ] | [ ] |
| **Context:** When I'm writing test for my flask application... **Action:** I ensure to create a test client within my `setUp()` function. | [ ] | [ ] |
| **Context:** When I want to test the different endpoints in my API... **Action:** I use the functions provided by the test client object to make HTTP requests to the test app. | [ ] | [ ] |
| **Context:** When writing tests for my Flask API... **Action:** I ensure to test all the API endpoints using varying parameter types. | [ ] | [ ] |
| **Context:** When writing tests for my Flask API... **Action:** I ensure to test exceptional cases. | [ ] | [ ] |



----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| I can create APIs that are complex, scalable and robust using Flask. | [ ] | [ ]  |
