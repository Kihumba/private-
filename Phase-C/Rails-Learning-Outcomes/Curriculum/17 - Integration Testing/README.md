# Outcome - Integration Testing

Skill Description
----------
Integration testing is a component of Extreme Programming (XP).
With integration testing, we are able to verify that all components of our applications function as it is supposed to. Also, integration testing exposes problems with components of our application before it is exposed to the real world.

Outputs
----------
In checkpoint 2 and 3:
- write integration tests using capybara and request specs respectively.
In simulation project,
- write integration tests for all feature implemented.

----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| Difference between unit and integration.| [ ] | [ ] |
| What is capybara.| [ ] | [ ] |
| What is cucumber.| [ ] | [ ] |
| Difference between capybara and cucumber.| [ ] | [ ] |
| Relationship between integration tests and end-to-end test.| [ ] | [ ] |
| The importance of writing integration tests.| [ ] | [ ] |
| Different types of capybara javascript driver.| [ ] | [ ] |
| Why should you set js: true in your describe block.| [ ] | [ ] |
| What’s the relationship between phantomjs, selenium, capybara-webkit browser and poltergeist.| [ ] | [ ] |
| Describe the interaction performed by capybara javascript browsers.| [ ] | [ ] |
| What’s the relationship between capybara and outside-in-testing.| [ ] | [ ] |
| Why do you need to truncate database records instead of using transactions which are much faster when dealing with capybara.| [ ] | [ ] |
| What’s the difference between scenario and feature when dealing with capybara tests.| [ ] | [ ] |
| Why are erratic tests so prevalent in capybara tests.| [ ] | [ ] |
| Describe the following capybara DSL methods and matchers:| | |
| **Navigation**| | |
| <ul><li>Visit| [ ] | [ ] |
| <ul><li>Have\_current\_path| [ ] | [ ] |
| **Clicking links and buttons**| | |
| <ul><li>Click_link| [ ] | [ ] |
| <ul><li>Click_on| [ ] | [ ] |
| <ul><li>Click_button| [ ] | [ ] |
| **Interacting with forms**| | |
| <ul><li>Fill_in| [ ] | [ ] |
| <ul><li>Choose| [ ] | [ ] |
| <ul><li>Check| [ ] | [ ] |
| <ul><li>Uncheck| [ ] | [ ] |
| <ul><li>Select| [ ] | [ ] |
| <ul><li>Querying| [ ] | [ ] |
| <ul><li>Page.has_selectors?| [ ] | [ ] |
| <ul><li>Page.has_content?| [ ] | [ ] |
| <ul><li>Page.has_css?| [ ] | [ ] |
| <ul><li>Page.has_xpath?| [ ] | [ ] |
| <ul><li>Have_selector| [ ] | [ ] |
| <ul><li>Have_css| [ ] | [ ] |
| <ul><li>Have_content| [ ] | [ ] |
| <ul><li>Have_xpath| [ ] | [ ] |
| **Finding**| | |
| <ul><li>Find| [ ] | [ ] |
| <ul><li>All| [ ] | [ ] |
| <ul><li>Find_field| [ ] | [ ] |
| <ul><li>Find_link| [ ] | [ ] |
| <ul><li>Find_button| [ ] | [ ] |
| **Scoping**| | |
| <ul><li>Within| [ ] | [ ] |
| <ul><li>Within_fieldset| [ ] | [ ] |
| <ul><li>Within_table| [ ] | [ ] |
| How do you execute javascript in your capybara tests.| [ ] | [ ] |
| What’s the relationship between capybara, asynchronous javascript and race conditions.| [ ] | [ ] |
| What tricks can you use the minimize the number of race conditions your app encounters when capybara API.| [ ] | [ ] |


----------


## **Behaviors**


| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When building a rails application... **Action:** I use capybara and/or cucumber to write my integration tests.| [ ] | [ ]  |
| **Context:** When writing integration test with capybara... **Action:** I use a driver that supports javascript instead of the default rack-test driver.| [ ] | [ ]  |
| **Context:** When choosing a javascript driver for capybara... **Action:** I choose one that uses phantomjs(headless browser) eg capybara-webkit or poltergeist which are faster than ones that use normal browsers.| [ ] | [ ]  |
| **Context:** When writing integration tests using capybara... **Action:** I extract common functionality into local methods eg sign_in method.| [ ] | [ ]  |
| **Context:** When writing capybara tests... **Action:** I use rspec to run my tests.| [ ] | [ ]  |
| **Context:** When I need to find first matching element using capybara API... **Action:** I use find(“.active”, match: :first) instead of first(“.active”) to avoid race conditions.| [ ] | [ ]  |
| **Context:** When I need to interact with all matching element... **Action:** I use find(“.active”, match: :first) to find the first element first before using all(“.active”) to grab all matching element.| [ ] | [ ]  |
| **Context:** When I need to execute javascript code that manipulates down... **Action:**  I first find the dom element using capybara API before executing the javascript. Eg before executing execute_script(“$(‘.active’).focus()”) I first find all the elements with active class using find(“.active”)..| [ ] | [ ]  |
| **Context:** When I need to check field values in capybara tests... **Action:** I use provided capybara matchers. Eg use expect(page).to have_field("Username", with: "Joe") instead of expect(find_field("Username").value).to eq("Joe").| [ ] | [ ]  |
| **Context:** When looking for matching css... **Action:** I use provided capybara matchers. Eg use expect(page).not_to have_css(‘.active’) instead of expect(has_css?(‘.active’).to be_false.| [ ] | [ ]  |
| **Context:** When using capybara with a javascript browser... **Action:** I truncate my database since transaction won’t work when dealing with different contexts(browser and capybara).| [ ] | [ ]  |
| **Context:** When writing test using capybara... **Action:** I create both happy scenarios and sad scenarios.| [ ] | [ ]  |
| **Context:** When writing integration tests... **Action:** I place myself in mind of the current user under test(admin, customer etc).| [ ] | [ ]  |
| **Context:** When writing integration tests... **Action:** I consider what should happen independent of the existing implementation(me as a user, not as a developer).| [ ] | [ ]  |
| **Context:** When writing integration tests... **Action:** I translate feature acceptance specification into my tests.| [ ] | [ ]  |

----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Maintain application stability using integration tests.| [ ] | [ ]  |
| Integration tests are modelled after acceptance specifications.| [ ] | [ ]  |
| All software must contain integration tests.| [ ] | [ ]  |
