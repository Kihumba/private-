# Outcome - ActiveRecord

Skill Description
----------
The Fellow understands the function of Active Record within the Rails framework, and how it allows their application to interact with a database.

Outputs
----------
After attaining this skill, and as a demonstration of it, I should be able to lay out the data architecture I would need to implement to build a Rails app that enables users to post and follow other users. 

**Note:** I will also be able to write the necessary ActiveRecord queries for retrieving data from the database.


----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| The defiition of an ORM | [ ] | [ ]  |
| Why ActiveRecord is more useful than just using SQL | [ ] | [ ]  |
| Why ActiveRecord::Relation is important and what it means | [ ] | [ ]  |
| The definition of Lazy Evaluation | [ ] | [ ]  |
| The difference between Lazy Evaluation and Eager Evaluation | [ ] | [ ]  |
| How to make a relation evaluate into an array | [ ] | [ ]  |
| How to check whether a database already contains a record | [ ] | [ ]  |
| Why #find_by is useful and how it is used | [ ] | [ ]  |
| The difference between what is returned using a #where query and a #find query | [ ] | [ ]  |
| How to join tables together in Rails | [ ] | [ ]  |
| When to use symbols / hashes and when to use explicit strings for query parameters | [ ] | [ ]  |
| The definition of `scopes` and why are they useful | [ ] | [ ]  |
| What needs to happen for a class method to act like a scope | [ ] | [ ]  |
| How Rails normally determines which table and foreign key to use when you have an association (e.g. User.first.posts) | [ ] | [ ]  |
| When I would need to specify particular options in an association (:class_name, :foreigh_key, :source) | [ ] | [ ]  |
| The definition of a polymorphic association and when to use one | [ ] | [ ]  |
| The difference between using the association to create a new object vs. calling YourObject.new, and which is the preferred method | [ ] | [ ]  |
| How to automatically destroy all a User's Post objects if that user is deleted | [ ] | [ ]  |
| How to set up a self-association, such as with Users following Users | [ ] | [ ]  |


----------


## **Behaviors**


| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When working with a database in any Rails application **Action:** I use an ORM  | [ ] | [ ]  |
| **Context:** When performing CRUD operation on my database **Action:** I use ActiveRecord to construct my queries | [ ] | [ ]  |
| **Context:** When retrieving related model data that might not be used **Action:** I use `lazy loading`/`lazy evaluation` | [ ] | [ ]  |
| **Context:** When retrieving related model data that are used everywhere with the main model **Action:** I use `eager loading`/`eager evaluation`  | [ ] | [ ]  |
| **Context:** When I want to retrieve a single record from the database based on the model attribute **Action:** I use the `find_by` method | [ ] | [ ]  |
| **Context:** When I want to retrieve a single record based on the primary key of a table **Action:** I use the `find` method | [ ] | [ ]  |
| **Context:** When I need a custom chain of ActiveRecord methods **Action:** I use ActiveRecord `scopes` | [ ] | [ ]  |
| **Context:** When I want to create relationships between different models **Action:** I use ActiveRecord association | [ ] | [ ]  |
| **Context:** When I need to pre-load(eager load) scopes **Action:** I turn them into associations instead | [ ] | [ ]  |
| **Context:** When I do more than chain built-in scopes into larger scopes **Action:** I use class methods | [ ] | [ ]  |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Using ORM makes working with databases in a Rails application simpler. | [ ] | [ ]  |
| ORMs built using the ActiveRecord pattern are easier to work with than those built with other patterns (e.g DataMapper pattern). | [ ] | [ ]  |
| Retrieving related data using ActiveRecord associations is easy. | [ ] | [ ]  |
| Conventions used in ActiveRecord makes it easy to get started with ActiveRecord ORM. | [ ] | [ ]  |
