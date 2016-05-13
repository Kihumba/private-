# Outcome - Testing in Laravel

Skill Description
----------
Testing is a component of Extreme Programming (XP). We basically have Unit and Functional/Integrated tests.
With integration testing, we are able to verify that all components of our applications function as it is supposed to. Also, integration testing exposes problems with components of our application before it is exposed to the real world.
With Unit testing, you can test each individual component isolation.


Outputs
----------
In checkpoint 4:
- Write integration tests using Laravel's Inbuilt Integration test Suite In simulation project for all the features implemented.

----------
## **Knowledge**

| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| I know the difference between unit and integration tests.| [ ] | [ ] |
| I know Codeception is an alternative testing framework for performing integrated and unit testing in Laravel apps | [] | [] |
| Relationship between integration tests and end-to-end test.| [ ] | [ ] |
| I know the importance of writing integration tests.| [ ] | [ ] |
| I know the importance of writing unit tests. | [ ] | [ ] |
| I know how to set up and use file database such as Sqlite for testing  | [ ] | [ ] |
| I know how to use model factories to generate and authenticate user data for testing | [ ] | [ ] |
| I know how to isolate my routes and controllers from any middleware concerns when testing | [ ] | [ ] |
| I know how to make custom HTTP Requests with the `call` method when testing routes or APIs | [ ] | [ ] |
| I know how to use additional helper assertion methods during integration testing such as: | | |
| <ul><li>$this->assertViewHas($key, $value = null); </li></ul>| [ ] | [ ] |
| <ul><li>$this->assertViewHasAll(array $bindings); </li></ul>| [ ] | [ ] |
| <ul><li>$this->assertViewMissing($key); </li></ul>| [ ] | [ ] |
| <ul><li>$this->assertSessionHas($key, $value = null); </li></ul>| [ ] | [ ] |
| <ul><li>$this->assertResponseStatus($code); </li></ul>| [ ] | [ ] |
| <ul><li>$this->assertResponseOk(); </li></ul>| [ ] | [ ] |
| I know how to unit test my Controllers | [ ] | [ ] |
| I know how to test JSON APIs using the following methods | [ ] | [ ] |
| I know how to reset the database after each test | [ ] | [ ] |
| I know how to mock the following when testing: |  | |
| <ul><li>Events </li></ul>| [ ] | [ ] |
| <ul><li>Jobs </li></ul>| [ ] | [ ] |
| <ul><li>Facades </li></ul>| [ ] | [ ] |
| I know how to test my Models and their relationships | [ ] | [ ] |
| What’s the relationship between phantomjs, selenium and PHPUnit.| [ ] | [ ] |
| Describe the interaction performed by capybara javascript browsers.| [ ] | [ ] |
| Why do you need to truncate database records instead of using transactions which are much faster when dealing with capybara.| [ ] | [ ] |
| Describe the following Integrated tes methods:| | |
| **Navigation**| | |
| <ul><li>$this->visit| [ ] | [ ] |
| **Clicking links and buttons**| | |
| <ul><li>$this->click | [ ] | [ ] |
| <ul><li>$this->press| [ ] | [ ] |
| **Interacting with forms**| | |
| <ul><li>$this->type| [ ] | [ ] |
| <ul><li>$this->select| [ ] | [ ] |
| <ul><li>$this->check| [ ] | [ ] |
| <ul><li>$this->uncheck| [ ] | [ ] |
| <ul><li>$this->attachSelect| [ ] | [ ] |
| I know how to speed up my tests running time | [ ] | [ ] |


----------


## **Behaviors**


| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When building a laravel application... **Action:** I use the inbuilt test suite to write my integration tests.| [ ] | [ ]  |
| **Context:** When writing integration test in a laravel application... **Action:** I can use Codeception | [ ] | [ ]  |
| **Context:** When choosing a javascript driver while using Selenium for integration testing... **Action:** I choose one that uses phantomjs(headless browser).| [ ] | [ ]  |
| **Context:** When writing integration tests... **Action:** I create both happy scenarios and sad scenarios.| [ ] | [ ]  |
| **Context:** When writing integration tests... **Action:** I place myself in mind of the current user under test(admin, customer etc).| [ ] | [ ]  |
| **Context:** When writing integration tests... **Action:** I consider what should happen independent of the existing implementation(me as a user, not as a developer).| [ ] | [ ]  |
| **Context:** When writing integration tests... **Action:** I translate feature acceptance specification into my tests.| [ ] | [ ]  |
| **Context:** When writing integration tests... **Action:** I use sqlite file database to speed up my tests | [ ] | [ ] |

----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Maintain application stability using integration tests.| [ ] | [ ]  |
| Integration tests are modelled after acceptance specifications.| [ ] | [ ]  |
| All software must contain integration tests.| [ ] | [ ]  |
| Unit tests ensure software logic works as expected | [ ] | [ ] |