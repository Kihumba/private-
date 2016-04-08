# Outcome - Authentication and Authorization

Skill Description
----------
The whole point of authentication is to make sure that the user is who they say they are. The standard way of managing this is through logging in your user via a sign in form. Once the user is logged in, you keep track of that user using the session until the user logs out.

A related concept is authorization. Yes, you may be signed in, but are you actually authorized to access what you're trying to access? The typical example is the difference between a regular user and an admin user. They both authenticate with the system but only the admin is authorized to make changes to certain things.

Outputs
----------
In checkpoints 2 project:
- make use of `omniauth` gem and/or `devise` gem to authenticate users of the application
- make use of `cancancan` gem to authorize users of the application
In checkpoints 3 project:
- make use of `has_secure_password` method to authenticate users of the API

----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| I can describe from memory, the difference between authentication and authorization? | [ ] | [ ]  |
| I can describe from memory, why `#has_secure_password` is a handy method | [ ] | [ ]  |
| I can describe from memory, the basic overview of how to authenticate a user with that method | [ ] | [ ]  |
| I can describe from memory, the additional steps (on a high level) that are needed to actually "remember" a user after they've closed the browser | [ ] | [ ]  |
| I can describe from memory, what the Devise gem is and why it is useful | [ ] | [ ]  |
| I can describe from memory, the necessary steps needed to add third party authentication (eg facebook, github etc) using omniauth gem | [ ] | [ ]  |
| I can describe from memory, the necessary steps needed to use `cancancan` gem to authorize users of an application | [ ] | [ ]  |


----------


## **Behaviors**


| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When I need some specific users to have access to some specific part of my application... **Action:** I authenticate users of my application | [ ] | [ ]  |
| **Context:** When I have different users with different roles eg (:member, :admin, :authors, :editors :anonymous etc)... **Action:** I grant my users defined permissions using `cancancan` gem | [ ] | [ ]  |
| **Context:** When building simple/fairly complex applications without complex access rules... **Action:** I use role based authorization | [ ] | [ ]  |
| **Context:** When building very complex applications... **Action:** I base my authorization on matching requested activities with a database of privileges | [ ] | [ ]  |
| **Context:** When I want to implement role based authorization... **Action:** I use `cancancan` or `pundit` gem. | [ ] | [ ]  |
| **Context:** When users of my application can only have one role... **Action:** I use Enum role in my user model(eg enum role: [:user, :vip, :admin]) and role field in my users table to implement role based authorization | [ ] | [ ]  |
| **Context:** When users of my application can have multiple roles... **Action:** I create a separate table called `roles` with a joining table called `usersinroles` to join a user to many roles and vice versa  | [ ] | [ ]  |
| **Context:** When I need to know the specific user who is accessing a resource or performing an action... **Action:** I authenticate the users before giving them access to the resource  | [ ] | [ ]  |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Users of my application are protected by implementation very good authentication/authorization in my application | [ ] | [ ]  |
| Users of my application have permission to view specific resource when they are authorized | [ ] | [ ]  |
| Authentication ask the question `Who are you` | [ ] | [ ]  |
| Authorization ask the question `What are you allowed to do` | [ ] | [ ]  |
| Authentication/Authorization are necessary to reduce fraud | [ ] | [ ]  |
| Every application that is mission critical eg apps that deal with money, health, very sensitive data must pay very close attention to how users they are authenticated and authorized | [ ] | [ ]  |
