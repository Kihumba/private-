# Outcome

Skill Description
----------
Active Record is one of the seven Ruby gems working harmoniously together to make up the rails framework. It takes care of all the database related stuff. It's known as an "ORM". ORM stands for Object-Relational-Mapping. It basically means that Active Record takes data which is stored in a database table using rows and columns, which needs to be modified or retrieved by writing SQL statements (if you're using a SQL database), and it lets you interact with that data as though it was a normal Ruby object.

Outputs
----------
Lay out the data architecture you'd need to implement to build the following scenarios:
- A site for pet-sitting (watching someone's pet while they're gone). People can babysit for multiple pets and pets can have multiple petsitters.
- You like hosting people for dinner so you want to build a dinner party invitation site. A user can create parties, invite people to a party, and accept an invitation to someone else's party.
- You and your friends just love posting things and following each other. How would you set up the models so a user can follow another user?

**Note:** You will need to write the necessary ActiveRecord queries for retrieving data from the database.


----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| I can describe from memory, what an ORM is | [ ] | [ ]  |
| I can describe from memory, why ActiveRecord is more useful than just using SQL | [ ] | [ ]  |
| I can describe from memory, why ActiveRecord::Relation is important and what it means | [ ] | [ ]  |
| I can describe from memory, what Lazy Evaluation mean | [ ] | [ ]  |
| I can describe from memory, the difference between Lazy Evaluation and Eager Evaluation | [ ] | [ ]  |
| I can describe from memory, how to make a relation evaluate into an array | [ ] | [ ]  |
| I can describe from memory, how to check whether a database already contains a record | [ ] | [ ]  |
| I can describe from memory, why #find_by useful is and how it is used | [ ] | [ ]  |
| I can describe from memory, the difference between what's returned using a #where query and a #find query | [ ] | [ ]  |
| I can describe from memory, how to join tables together in Rails | [ ] | [ ]  |
| I can describe from memory, when to use symbols / hashes and when to use explicit strings for query parameters | [ ] | [ ]  |
| I can describe from memory, what `scopes` are and why are they useful | [ ] | [ ]  |
| I can describe from memory, What needs to happen for a class method to act like a scope | [ ] | [ ]  |
| I can describe from memory, how Rails normally know which table and foreign key to use when you have an association (e.g. User.first.posts) | [ ] | [ ]  |
| I can describe from memory, when I would need to specify the :class_name option in an association | [ ] | [ ]  |
| I can describe from memory, when I would need to specify the :foreign_key option in an association | [ ] | [ ]  |
| I can describe from memory, when I would need to specify the :source option in an association | [ ] | [ ]  |
| I can describe from memory, what polymorphic association are and when I would you use one | [ ] | [ ]  |
| I can describe from memory, what the two ways to use the association to create a new object instead of just calling YourObject.new including why it is useful and the preferred method | [ ] | [ ]  |
| I can describe from memory, how to automatically destroy all a User's Post objects if that user is deleted? | [ ] | [ ]  |
| I can describe from memory, how to set up a self-association, like with Users following Users | [ ] | [ ]  |


----------


## **Behaviors**


| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When working with a database in any rails application... **Action:** I use an ORM  | [ ] | [ ]  |
| **Context:** When performing CRUD operation on my database... **Action:** I use ActiveRecord to construct my queries. | [ ] | [ ]  |
| **Context:** When retrieving related model data that might not be used... **Action:** I use `lazy loading`/`lazy evaluation` | [ ] | [ ]  |
| **Context:** When retrieving related model data that are used everywhere with the main model... **Action:** I use `eager loading`/`eager evaluation`  | [ ] | [ ]  |
| **Context:** When I want to retrieve a single record from the database based on the model attribute... **Action:** I use the `find_by` method | [ ] | [ ]  |
| **Context:** When I want to retrieve a single record based on the primary key of a table... **Action:** I use the `find` method. | [ ] | [ ]  |
| **Context:** When I need a custom chain of ActiveRecord methods that can be added onto an existing Relation by calling its name like a normal method... **Action:** I use ActiveRecord `scopes` | [ ] | [ ]  |
| **Context:** When I want to create relationships between different models... **Action:** I use ActiveRecord association | [ ] | [ ]  |
| **Context:** When I need to pre load(eager load) scopes... **Action:** I turn them into associations instead. | [ ] | [ ]  |
| **Context:** When I do more than chain built-in scopes into larger scopes... **Action:** I use class methods | [ ] | [ ]  |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Building queries with scopes help keep things DRY. | [ ] | [ ]  |
| Using ORM makes working with databases in a rails application easier. | [ ] | [ ]  |
| ORMs built using the ActiveRecord pattern are easier to work with than those built with other patterns (e.g DataMapper pattern). | [ ] | [ ]  |
| Retrieving related data using ActiveRecord associations is easy. | [ ] | [ ]  |
| Conventions used in ActiveRecord makes it easy to get started with ActiveRecord ORM. | [ ] | [ ]  |
