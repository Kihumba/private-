# Outcome 3 - API Design using Flask

**Skill Description**
----------
To show complete understanding of the Flask skill, one must have an understanding of the following:

- Flask Basics, Routing and URLs
- Requests and Responses
- Sessions, Cookies and Flash Messaging
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

#### Flask Basics, Routing and URLs

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| Initializing a Flask application and the different parameters for running the application | [ ] | [ ] |
| URL Definition syntax in Flask using the `@app.route()` decorator as well as the `app.add_url_rule()` function | [ ] | [ ] |
| Reverse URL generation using `url_for()` | [ ] | [ ] |
| Handling different HTTP methods using the `request.method` variable | [ ] | [ ] |

#### Requests and Responses

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| The `request` object  | [ ] | [ ] |
| Accessing request data from URLs, JSON and Forms using `request.args`, `request.json` and `request.form` respectively.  | [ ] | [ ] |
| `Response` object anatomy | [ ] | [ ] |
| Returning different types of output from Flask view functions | [ ] | [ ] |
| Creating responses using the `make_response()` function  | [ ] | [ ] |

#### Sessions and Cookies

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| Accessing and modifying session data using the `session` object | [ ] | [ ] |
| Storing cookies using the response object's `set_cookie()` method and accessing cookie data from the request object | [ ] | [ ] |

#### Forms

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| Flask forms as an efficient way to implement validation rules and error handling for user inputted data. | [ ] | [ ] |
| Creating Form classes using the base `Form` class from the Flask-WTF extension. | [ ] | [ ] |
| Commonly encountered Field types - `StringField`, `IntegerField`, `BooleanField`, `FileField`, `URLField`. | [ ] | [ ] |
| Using common Flask-WTF Validators - `DataRequired`, `Length`, `Email`, `EqualTo`, `URL` - to check form data. | [ ] | [ ] |
| Accessing form data from within the view functions. | [ ] | [ ] |
| Validating form input using the `validate_on_submit()` function. | [ ] | [ ] |

#### Error Handling

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| Using the `redirect()` function to other routes. | [ ] | [ ] |
| Using the `abort()` function to abort a request early with a code. | [ ] | [ ] |
| Creating custom error handlers using the `@app.errorhandler()` decorator. | [ ] | [ ] |
| Creating and using custom exceptions in Flask. | [ ] | [ ] |

#### Using SQLAlchemy

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| Creating model classes using SQLAlchemy. Inheriting from the base `Model` class | [ ] | [ ] |
| Creating and destroying databases using the `create_all()` and `drop_all()` functions | [ ] | [ ] |
| Creating model fields using the `Column` class and common model field types and their parameters - `Integer`, `String`, `Boolean`, `DateTime` | [ ] | [ ] |
| Creating a primary key using the `primary_key` parameter. | [ ] | [ ] |
| Creating Foreign key relationships using `ForeignKey()` as a parameter when creating a column. | [ ] | [ ] |
| Creating nested object relationships using the `backref` parameter. | [ ] | [ ] |
| Common SQLAlchemy model methods - `filter()`, `filter_by()`, `get()`, `limit()`, `order_by()`, `all()` - and how to use them appropriately.  | [ ] | [ ] |
| Concept of migrations and using SQLAlchemy-migrate to create database migrations | [ ] | [ ] |
| Using the SQLAlchemy `paginate()` function to create paginated records | [ ] | [ ] |

#### Testing Flask Applications

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| Creating a test client for use in test cases | [ ] | [ ] |
| Methods used for making HTTP requests to our test client | [ ] | [ ] |

----------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When creating routes for my Flask API... **Action:** I ensure to properly specify the methods I would like the view function to accept. | [ ] | [ ] |
| **Context:** When creating view functions for my Flask API... **Action:** I use the `request.method` variable to handle different requests to the same url. | [ ] | [ ] |
| **Context:** When creating links between API methods I define... **Action:** I use the `url_for()` function to create easily readable references to different view functions within my codebase. | [ ] | [ ] |
| **Context:** When I want to access data sent to my API from my client... **Action:** I access it through the `request` object. | [ ] | [ ] |
| **Context:** When I want to create a custom response object... **Action:** I use the `make_response()` function to create the response object before returning it. | [ ] | [ ] |
| **Context:** When I need to persist data across a session... **Action:** I make use of the Flask `session` object. | [ ] | [ ] |
| **Context:** When I need to validate multiple values at once... **Action:** I use Flask-WTF forms to create validation rules to ensure data is sanitized. | [ ] | [ ] |
| **Context:** When creating Flask-WTF forms... **Action:** I ensure to take advantage of the various field types and parameters to properly specify the data I'm expecting from my client. | [ ] | [ ] |
| **Context:** When there's an error during runtime in my Flask API... **Action:** I make use of the `abort()` function to stop the current request cycle. | [ ] | [ ] |
| **Context:** When I anticipate that I will encounter an error multiple times during application execution... **Action:** I create custom error handlers to respond to specific HTTP status codes. | [ ] | [ ] |
| **Context:** When I need to model data to be used in my Flask API... **Action:** I make use of SQLAlchemy to define data models. | [ ] | [ ] |
| **Context:** Before I run my application... **Action:** I ensure to run `create_all()` at least once to ensure my database is constructed from my models. | [ ] | [ ] |
| **Context:** When creating data models using SQLAlchemy... **Action:** I ensure to use the right field types specific to the data being stored in the database. | [ ] | [ ] |
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
