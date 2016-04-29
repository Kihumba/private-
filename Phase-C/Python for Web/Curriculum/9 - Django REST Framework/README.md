# Outcome 1 - Django REST Framework

**Skill Description**
----------
To show complete understanding of HTTP and Web services skill, one must have an understanding of the following:

- Serializers
- Requests and Responses
- API Views
- Authentication and Permissions
- Viewsets and Routers


**Output**
----------
After attaining this skill, and as a demonstration of it, a person should be able to do the following:

1. Create a complete API using DRF
2. Implement Token-Based Authentication using DRF
3. Complete Checkpoint 4


**Objectives**
----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| What Serializers are and how they can be used | [ ] | [ ] |
| Types of Serializers available in DRF | [ ] | [ ] |
| Common serializer fields including for creating Relationships | [ ] | [ ] |
| Serializer methods | [ ] | [ ] |
| DRF `APIView` class for writing Class-Based Views | [ ] | [ ] |
| DRF Generic Views | [ ] | [ ] |
| Permission classes and how to add them to views | [ ] | [ ] |
| Authentication classes and how to add them to views | [ ] | [ ] |
| Viewsets as being used for creating generic API resource structures | [ ] | [ ] |
| Generating routes for viewsets automatically using Routers | [ ] | [ ] |


----------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When I want to specify format for requests to my API and responses back to a client... **Action:** I create serializer | [ ] | [ ] |
| **Context:** When I want to automatically generate a serializer from my models... **Action:** I make use of `serializers.ModelSerializer` to create my base serializer | [ ] | [ ] |
| **Context:** When I am creating a serializer from scratch... **Action:** I always use the appropriate serializer fields for the different attributes I'm expecting in the request data and that I'm returning in my response body. | [ ] | [ ] |
| **Context:** When I want to support saving instances using my serializer... **Action:** I override either or both of the `create()` and `update()` methods. | [ ] | [ ] |
| **Context:** For `ModelSerializer` when I want to override default serializer save and update actions... **Action:** I override the corresponding functions in the serializer class. | [ ] | [ ] |
| **Context:** When I want to validate a single field in my DRF serializer... **Action:** I override the `validate_<field_name>()` function in the serializer class (Where <field_name> refers to the particular field we want to validate). | [ ] | [ ] |
| **Context:** When I want to validate multiple fields in my DRF serializer... **Action:** I override the `validate()` function in the serializer class. | [ ] | [ ] |
| **Context:** When I want to create an API view fuction... **Action:** I can choose to write it using CBVs (using the `APIView` class) or FBVs (using the `@api_view()` decorator). | [ ] | [ ] |
| **Context:** When I create an API view fuction... **Action:** I can choose to write it using CBVs (using the `APIView` class) or FBVs (using the `@api_view()` decorator). | [ ] | [ ] |
| **Context:** When I create an an API using CBVs... **Action:** I use higher level abstractions like the `CreateAPIView`, `RetrieveUpdateDestroyAPIView` etc. to make writing the API more straightforward | [ ] | [ ] |
| **Context:** When I want to specify permissions for an `APIView`... **Action:** I specify them as a tuple using the `permission_classes` class variable. | [ ] | [ ] |
| **Context:** When I want to automatically create resource endpoints... **Action:** I create a viewset for each data model. | [ ] | [ ] |
| **Context:** When working with viewsets... **Action:** I create all the URLs automatically using routes. | [ ] | [ ] |



----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| I can nest serializers. | [ ] | [ ]  |
| DRF is a tool I can use to rapidly create APIs. | [ ] | [ ]  |
