# Outcome - Eloquent and Query Builder

Skill Description
----------
The Eloquent ORM included with Laravel provides a beautiful, simple ActiveRecord implementation for working with your database. Each database table has a corresponding "Model" which is used to interact with that table. Models allow you to query for data in your tables, as well as insert new records into the table.


Outputs
----------
Lay out the data architecture you'd need to implement to build the following scenarios:
- A site for pet-sitting (watching someone's pet while they're gone). People can babysit for multiple pets and pets can have multiple petsitters.
- You like hosting people for dinner so you want to build a dinner party invitation site. A user can create parties, invite people to a party, and accept an invitation to someone else's party.
- You and your friends just love posting things and following each other. How would you set up the models so a user can follow another user?

**Note:** You will need to write the necessary Eloquent queries for retrieving data from the database.


----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| I know what an ORM is | [ ] | [ ]  |
| I know why Eloquent is more useful than just using SQL | [ ] | [ ]  |
| I know what Lazy Loading mean | [ ] | [ ]  |
| I know the difference between Lazy and Eager Loading | [ ] | [ ]  |
| I know how to make a relation evaluate into an array | [ ] | [ ]  |
| I know how to check whether a database already contains a record | [ ] | [ ]  |
| I know why #find_by useful is and how it is used | [ ] | [ ]  |
| I know the difference between what's returned using a #where query and a #find query | [ ] | [ ]  |
| I know how to join tables together in Laravel | [ ] | [ ]  |
| I know how to use collection methods on the result of a Model query result | [ ] | [ ]  |
| I know how to perform multiple queries in one statement using the Query Builder | [] | [] |
| I know when to use explicit strings for query parameters | [ ] | [ ]  |
| I know what `scopes` are and why are they useful | [ ] | [ ]  |
| I know how Laravel normally know which table and foreign key to use when you have an association (e.g. user()->favorites()) | [ ] | [ ]  |
| I know when I how to add behaviors to Models | [ ] | [ ]  |
| I know how to use the DB Facade to perform faster and complex queries  | [ ] | [ ]  |
| I know how to automatically destroy all a User's Post objects if that user is deleted? | [ ] | [ ]  |
| I know how to perform a Soft delete on a Model | [ ] | [ ]  |


----------


## **Behaviors**


| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When working with a database in any laravel application... **Action:** I use an ORM  | [ ] | [ ]  |
| **Context:** When performing CRUD operations on my database... **Action:** I use Eloquent to construct my queries. | [ ] | [ ]  |
| **Context:** When retrieving related model data that might not be used... **Action:** I use `lazy loading` | [ ] | [ ]  |
| **Context:** When retrieving related model data that are used everywhere with the main model... **Action:** I use `eager loading`  | [ ] | [ ]  |
| **Context:** When I want to retrieve a single record from the database based on the model attribute... **Action:** I use the `where` method | [ ] | [ ]  |
| **Context:** When I want to retrieve a single record based on the primary key of a table... **Action:** I use the `find` method. | [ ] | [ ]  |
| **Context:** When I need a custom chain of Eloquent methods that can be added onto an existing Relation by calling its name like a normal method... **Action:** I use Eloquent `scopes` | [ ] | [ ]  |
| **Context:** When I want to create relationships between different models... **Action:** I use Eloquent association | [ ] | [ ]  |
| **Context:** When I need to pre load(eager load) scopes... **Action:** I turn them into associations instead. | [ ] | [ ]  |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Building queries with scopes help keep things DRY. | [ ] | [ ]  |
| Query Builder methods return results faster than Eloquent methods. | [] | [] |
| ORM makes working with databases in a laravel application easier. | [ ] | [ ]  |
| ORMs built using the ActiveRecord pattern are easier to work with than those built with other patterns (e.g DataMapper pattern). | [ ] | [ ]  |
| Retrieving related data using Eloquent associations is easy. | [ ] | [ ]  |
| Conventions used in Eloquent makes it easy to get started with Eloquent ORM. | [ ] | [ ]  |
