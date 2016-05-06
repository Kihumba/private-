# Outcome - REST and WEB APIs

Skill Description
----------
REST is the underlying architectural principle of the web and APIs adhere to the principle of REST.
After going through this, one should be able to create an API in Rails and take advantage of all that Rails provides in order to build a standard one.

Outputs
----------
Complete Checkpoint 3

----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| How Rails knows which type of file you are expecting back when you make an HTTP request.| [ ] | [ ] |
| What is the purpose of the #respond_to method?| [ ] | [ ] |
| How do you return a User object but specify that you don't want to include certain attributes (i.e. you can't just return User.first)?| [ ] | [ ] |
| What are the two steps performed behind the scenes by the #to_json method?| [ ] | [ ] |
| How do you tell a controller action to render nothing but an error message?| [ ] | [ ] |
| How do you build your own custom error messages?| [ ] | [] |
| Why can't you use session-based controller authentication methods if you want people to access your API programmatically?| [ ] | [ ] |
| What is "Service Oriented Architecture?"| [ ] | [ ] |
| How to version APIs.| [ ] | [ ] |
| What is activemodel serializer?| [ ] | [ ] |
| How do you create a serializer for a model using active model serializer?| [ ] | [ ] |
| Serialization constraints:| | |
| <ul><li>Attributes: attributes, attribute| [ ] | [ ] |
| <ul><li>Associations| [ ] | [ ] |
| <ul><li>root| [ ] | [ ] |
| <ul><li>Embed| [ ] | [ ] |
| Adapters:| | |
| <ul><li>Default adapters| [ ] | [ ] |
| <ul><li>Json_api| [ ] | [ ] |
| How to add root key.| [ ] | [ ] |
| How to serialize a plain old ruby object.| [ ] | [ ] |
| How to add pagination links.| [ ] | [ ] |
| How to test activemodel serializers.| [ ] | [ ] |
| How to implement token authentication using JWT.| [ ] | [ ] |
| How to enable Cross Origin Resource Sharing.| [ ] | [ ] |
| Documenting APIs using Apiary, Swagger, etc.| [ ] | [ ] |
| Using redis-throttle gem to implement rate limiting.| [ ] | [ ] |


----------


## **Behaviors**


| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When making a request to an API endpoint... **Action:** I specify the appropriate content type e.g json, xml, text,etc.| [ ] | [ ]  |
| **Context:** When building an API... **Action:**  I version the build to depict updates/upgrades to the API.| [ ] | [ ]  |
| **Context:** When building an API... **Action:**  I mock the API using apiary or swagger for easy and quick documentation.| [ ] | [ ]  |
| **Context:** When I want to adjust my application’s API without making large scale changes to the underlying schema... **Action:**  I create an abstraction between the model and the JSON called serializers.| [ ] | [ ]  |
| **Context:** When I want to share data from my application with other applications... **Action:** I create endpoints for my application that others can interact with.| [ ] | [ ]  |
| **Context:** When I want to separate a user’s account from the authentication process... **Action:** I use token based authentication as the life of a token is not tied to the user’s account.| [ ] | [ ]  |
| **Context:** When building an API... **Action:** I make full use of restful resources. | [ ] | [ ]  |
| **Context:** When I need Javascript client hosted on a different domain to access my API... **Action:** I enable CORS for those domains.| [ ] | [ ]  |
| **Context:** When I need to implement token authentication for my API... **Action:** I use JWT.| [ ] | [ ]  |
| **Context:** When setting up token authentication with short lived tokens... **Action:** I use refresh token to re-generate tokens once they tokens expire.| [ ] | [ ]  |
| **Context:** When building APIs... **Action:** I enable rate limiting to prevent users/bots from issuing too many request per second/minute/hour to my API.| [ ] | [ ]  |
| **Context:** When building an API that returns json... **Action:** I follow json api specification.| [ ] | [ ]  |
| **Context:** When I need my API to handle different message format(json, xml, text... **Action:** I use respond_to along with respond_with method.| [ ] | [ ]  |

----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Without APIs, technology would not be where it is at the moment.| [ ] | [ ]  |
| APIs are easy to create.| [ ] | [ ]  |
| Most applications on the web consume one API or the other.| [ ] | [ ]  |
