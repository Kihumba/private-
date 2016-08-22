# Outcome 8 - Testing in Django

**Skill Description**
----------
To show complete understanding of Django Testing skill, one must have an understanding of the following:

- Testing Routes in Django
- Unit Testing within Django
- E2E Testing with Selenium


**Output**
----------
After attaining this skill, and as a demonstration of it, a person should be able to do the following:

1. Write tests for a Django application


**Objectives**
----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| Commands for running Django tests | [ ] | [ ] |
| Available `TestCase` assertions | [ ] | [ ] |
| Methods available in the `Client()` class for testing HTTP routes | [ ] | [ ] |


----------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When testing my application... **Action:** I ensure to test the routes, models, utility functions and the UI (using Selenium). | [ ] | [ ] |
| **Context:** When writing tests for my application... **Action:** I specify a different configuration for the test using a separate settings file. | [ ] | [ ] |
| **Context:** When writing tests for my application... **Action:** I use different files for different types of tests e.g `test_routes` for routes, `test_e2e` for selenium tests, `test_models` for model tests. | [ ] | [ ] |
| **Context:** When testing my models... **Action:** I make use of fixtures to initialize my database with large amounts of data. | [ ] | [ ] |
| **Context:** When creating tests for my application... **Action:** I put all the initialization operations within the `setup()` function of the class. | [ ] | [ ] |
| **Context:** When testing routes... **Action:** I create a `Client` object in the `setup()` method and use the object's methods to make test HTTP requests. | [ ] | [ ] |
| **Context:** When writing assertions for route tests... **Action:** I test the status code as well as the data returned from the request. | [ ] | [ ] |
| **Context:** When creating route tests... **Action:** I test for error conditions by supplying erroneous inputs. | [ ] | [ ] |
| **Context:** When writing tests for my application... **Action:** I creating E2E tests that test visual components on the page. | [ ] | [ ] |
| **Context:** When writing E2E test for my application... **Action:** I ensure to capture every operation performed by users in a step by step manner. | [ ] | [ ] |
| **Context:** When writing E2E test for my application... **Action:** I subclass for `StaticLiveServerTestCase` to ensure the static files are properly loaded. | [ ] | [ ] |
| **Context:** When we want to test the presence of an element on my page... **Action:** I use the wait syntax to make sure the element has loaded properly on the page. | [ ] | [ ] |
| **Context:** When testing my models... **Action:** I make use of fixtures to initialize my database with large amounts of data. | [ ] | [ ] |
| **Context:** When running tests from my command line... **Action:** I ensure to run the tests with the test configuration module set using the `--settings` parameter. | [ ] | [ ] |



----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Writing tests for my application reduces the possibilities of having errors on my app. | [ ] | [ ]  |
| Writing E2E tests, I'm able to simulate real-life user interactions with my app and cater for different scenarios. | [ ] | [ ]  |
