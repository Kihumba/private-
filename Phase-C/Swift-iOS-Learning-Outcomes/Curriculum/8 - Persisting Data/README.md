# Outcome 8 - Persisting Data
## Skill Description

In real life applications, data is received and sent over-the-air (OTA) following the CRUD pattern (Create, Read, Update and Delete). More often than none, data will need to be accessed offline, data that might affect the way requests are made to the server or data thats written and read frequently. This Skill covers the methods available in iOS that can be used to persist data on a mobile device.

## Output
After attaining this skill, and as a demonstration of it, a person should be able to create the following:

- An iOS Project is to be created which includes `CoreData` in the project initialization. The project must write and read sample data into all 3 storage systems, User Defaults (`NSUserDefaults`), `NSKeyedArchiver` and `CoreData`.

## Objectives
### Knowledge

| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| The uses for persisting data? | [ ] | [ ] |
| What types of data can be persisted?  | [ ] | [ ] |<!-- This is unclear. What doesn't fall into this classification? -->
| What tools / libraries can be used to persist data? | [ ] | [ ] |
| The reasons for not persisting data. | [ ] | [ ] |
| How can data be stored in User Defaults (`NSUserDefaults`)? | [ ] | [ ] |
| What kinds of data should be stored in `NSUserDefaults` | [ ] | [ ] |
| How can data be stored in Core Data (`CoreData`)? | [ ] | [ ] |
| What kinds of data should be stored in `CoreData` | [ ] | [ ] |
| How can data be stored in NSKeyedArchiver (`NSKeyedArchiver`)? | [ ] | [ ] |
| What kinds of data should be stored in `NSKeyedArchiver` | [ ] | [ ] |
| What query structure is employed in the various Data storage systems?  | [ ] | [ ] |
| Storage limits of relevant Data storage systems. | [ ] | [ ] |
| The difference between serialization and deserialization. | [ ] | [ ] |

-------

### Behaviors

| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When I have data to store locally on a device, **Action:** I use the most appropriate persistent Data stores based on the type of data. | [ ] | [ ] |
| **Context:** When I need to save relational data, **Action:** I use `CoreData`. | [ ] | [ ] |
| **Context:** When I need to serialize data manually, **Action:** I use `NSKeyedArchiver`. | [ ] | [ ] |
| **Context:** When I need to save non-relational data, **Action:** I use either `NSKeyedArchiver` or the User Defaults (`NSUserDefaults`). | [ ] | [ ] |
| **Context:** When saving key-value data or data that is relatively small (String, Int, Bool etc), **Action:** I make use of User Defaults (`NSUserDefaults`). | [ ] | [ ] |

-------

### Beliefs

| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Data should be saved on the device when its intended to be read or written to frequently by the device. | [ ] | [ ] |
<!-- This is not an appropriate belief. Alternative belief: 
Data should be saved to the device when retrieval of the data would tax resources or the data needs to persist after memory is cleared. -->
| User Defaults (`NSUserDefaults`) is used to get / set data only when quick access to said data is required. | [ ] | [ ] |
| `CoreData` can be used to save relational data on a local device. | [ ] | [ ] |
