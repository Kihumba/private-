# Outcome - Authentication and Authorization

Skill Description
----------
The Fellow effectively uses authentication to make sure the user is who they claim to be on their application. The Fellow also effectively uses authorization to make sure that when someone is signed in they are only interacting with the application in a way that they are meant to (for example, the difference between a regular user and an admin user). 


Outputs
----------
In checkpoints 2 project:
- make use of `omniauth` gem and/or `devise` gem to authenticate users of the application
- make use of `cancancan` gem to authorize users of the application
In checkpoints 3 project:
- make use of `has_secure_password` method to authenticate users of the API

----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| The difference between authentication and authorization | [ ] | [ ]  |
| How to use `#has_secure_password` to authenticate a user | [ ] | [ ]  |
| The additional steps (on a high level) that are needed to  "remember" a user after they've closed the browser | [ ] | [ ]  |
| The definition of the Devise gem is and why it is useful | [ ] | [ ]  |
| The necessary steps needed to add third party authentication (eg facebook, github etc) using omniauth gem | [ ] | [ ]  |
| How to use `cancancan` gem to authorize users of an application | [ ] | [ ]  |


----------


## **Behaviors**


| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When I need some specific users to have access to some specific part of my application **Action:** I authenticate users of my application | [ ] | [ ]  |
| **Context:** When I have different users with different roles eg (:member, :admin, :authors, :editors :anonymous etc) **Action:** I grant my users defined permissions using `cancancan` gem | [ ] | [ ]  |
| **Context:** When building applications without complex access rules **Action:** I use role based authorization | [ ] | [ ]  |
| **Context:** When building very complex applications **Action:** I base my authorization on matching requested activities with a database of privileges | [ ] | [ ]  |
| **Context:** When I want to implement role-based authorization **Action:** I use `cancancan` or `pundit` gem. | [ ] | [ ]  |
| **Context:** When users of my application can only have one role **Action:** I use Enum role in my user model to implement role based authorization | [ ] | [ ]  |
| **Context:** When users of my application can have multiple roles **Action:** I create a separate table called `roles` with a joining table called `usersinroles` to join a user to many roles and vice versa  | [ ] | [ ]  |
| **Context:** When I need to know the specific user who is accessing a resource or performing an action **Action:** I authenticate the users before giving them access to the resource  | [ ] | [ ]  |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Good authentication/authorization system help protect my users | [ ] | [ ]  |
| Authentication allows my app to ask the user `Who are you?` | [ ] | [ ]  |
| Authorization allows my app to ask the user `What are you allowed to do?` | [ ] | [ ]  |
| Authentication and authorization of users in high stake apps are mission critical when building them. | [ ] | [ ]  |
