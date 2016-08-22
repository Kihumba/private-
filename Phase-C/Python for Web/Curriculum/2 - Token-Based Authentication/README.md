# Outcome 2 - Token-Based Authentication

**Skill Description**
----------
Complete understanding of this skill means a good grasp of the best practices associated with:

- Process of Token-Based Authentication
- Creating Tokens
- Workflow associated with using Tokens for Authentication


**Output**
----------
After attaining this skill, and as a demonstration of it, a person should be able to do the following:

1. Implement Token-Based Authentication on Checkpoint 2


**Objectives**
----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| Differences between Token-Based Authentication and Server-Based Authentication. | [ ] | [ ] |
| Steps involved in Token-Based Authentication <ul><li>User logs in</li><li>User Data is encoded as token using a secret key</li><li>Token is sent back to the client</li><li>Token is stored in the client using LocalStorage</li><li>Token in sent in the header with all subsequent requests.</li></ul> | [ ] | [ ] |
| Pros and Cons of Token-Based Authentication. | [ ] | [ ] |
| Anatomy of a JWT Token - Header, Payload and Signature - and what each section contains. | [ ] | [ ] |
| Process of encoding and decoding JWT Token. | [ ] | [ ] |


----------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When I want to implement stateless transactions on my application... **Action:** I make use Token-Based Authentication. | [ ] | [ ] |
| **Context:** After creating a token for my user... **Action:** I always ensure store the token on the client for subsequent requests. | [ ] | [ ] |
| **Context:** When making use of Token-Based Authentication... **Action:** I add the token to the `Authorization` Header of every HTTP request to a protected route. | [ ] | [ ] |
| **Context:** When I want to create a public API that makes use of Token-Based Authentication... **Action:** I allow my server accept requests from all domains using `Access-Control-Allow-Origin: *` | [ ] | [ ] |
| **Context:** When creating tokens... **Action:** I encode enough data to identify the user from the token. | [ ] | [ ] |
| **Context:** When creating tokens... **Action:** I always ensure to set a reasonable expiry time for my tokens. | [ ] | [ ] |
| **Context:** When using tokens in my web application... **Action:** I encode the data using the key and use the same key to decode the token. | [ ] | [ ] |
| **Context:** When validating tokens... **Action:** I always check that the token is valid, not expired and has the appropriate user data. | [ ] | [ ] |





----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Token-Based Authentication can and will reduce the processing load on my server. | [ ] | [ ] |
| My application is very secure when using Token-Based Authentication. | [ ] | [ ] |
| My application is much more scalable when I use Token-Based Authentication. | [ ] | [ ] |
