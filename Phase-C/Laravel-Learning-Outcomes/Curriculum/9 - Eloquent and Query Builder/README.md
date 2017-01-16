# Outcome - Eloquent and Query Builder

Skill Description
----------
The Eloquent ORM included with Laravel provides a beautiful, simple ActiveRecord implementation for working with your database. Each database table has a corresponding "Model" which is used to interact with that table. Models allow you to query for data in your tables, as well as insert new records into the table.


Outputs
----------
After attaining this skill, and as a demonstration of it, I should be able to create the data architecture to build a site for pet-sitting (watching someone's pet while they're gone). People can babysit for multiple pets and pets can have multiple petsitters.

**Note:** You will need to write the necessary Eloquent queries for retrieving data from the database.


----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| The definition of an ORM | [ ] | [ ]  |
| The difference between using Eloquent vs just using SQL | [ ] | [ ]  |
| The definition of Lazy Loading | [ ] | [ ]  |
| The difference between Lazy and Eager Loading | [ ] | [ ]  |
| How to make a relation evaluate into an array | [ ] | [ ]  |
| How to check whether a database already contains a record | [ ] | [ ]  |
| How and why to use #find_by | [ ] | [ ]  |
| The difference between what is returned using a #where query and a #find query | [ ] | [ ]  |
| How to join tables together in Laravel | [ ] | [ ]  |
| How to use collection methods on the result of a Model query | [ ] | [ ]  |
| How to perform multiple queries in one statement using the Query Builder | [] | [] |
| When to use explicit strings for query parameters | [ ] | [ ]  |
| The definition of `scopes` and why are they useful | [ ] | [ ]  |
| Which table and foreign key to use when you have an association in Laravel | [ ] | [ ]  |
| When and how to add behaviors to Models | [ ] | [ ]  |
| How to use the DB Facade to perform faster and complex queries  | [ ] | [ ]  |
| How to automatically destroy all a User's Post objects if that user is deleted | [ ] | [ ]  |
| How to perform a Soft delete on a Model | [ ] | [ ]  |


----------


## **Behaviors**


| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When working with a database in any Laravel application **Action:** I use an ORM.  | [ ] | [ ]  |
| **Context:** When performing CRUD operations on my database **Action:** I use Eloquent to construct my queries. | [ ] | [ ]  |
| **Context:** When retrieving related model data that might not be used **Action:** I use `lazy loading`. | [ ] | [ ]  |
| **Context:** When retrieving related model data that are used everywhere with the main model **Action:** I use `eager loading`.  | [ ] | [ ]  |
| **Context:** When I want to retrieve a single record from the database based on the model attribute **Action:** I use the `where` method. | [ ] | [ ]  |
| **Context:** When I want to retrieve a single record based on the primary key of a table **Action:** I use the `find` method. | [ ] | [ ]  |
| **Context:** When I want to create relationships between different models **Action:** I use Eloquent association. | [ ] | [ ]  |
| **Context:** When I need to pre load (eager load) scopes **Action:** I turn them into associations instead. | [ ] | [ ]  |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| All applications have a need for speed-- Query Builder methods return results faster than Eloquent methods. | [ ] | [ ] |
| Retrieving related data using Eloquent associations is easy. | [ ] | [ ]  |
| Conventions used in Eloquent makes it easy to get started with Eloquent ORM. | [ ] | [ ]  |
