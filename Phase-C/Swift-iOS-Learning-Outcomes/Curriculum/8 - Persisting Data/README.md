# Outcome 8 - Persisting Data
## Skill Description

In real life applications, data is received and sent over-the-air (OTA) following the CRUD pattern (Create, Read, Update and Delete). More often than none, data will need to be accessed offline, data that might affect the way requests are made to the server or data thats written and read frequently. This Skill covers the methods available in iOS that can be used to persist data on a mobile device.

## Output
After attaining this skill, and as a demonstration of it, a person should be able to create the following:

- An iOS Project is to be created which includes `CoreData` in the project initialization. The Project will write and read Sample Data into all 3 storage systems, User Defaults (`NSUserDefaults`), `NSKeyedArchiver` and `CoreData`.

- **Detailed and Documented coverage of this skill can be shown by completing _Checkpoint 2_, available upon request.**

## Objectives
### Knowledge

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| The importance of Persisting Data. | [ ] | [ ] |
| The Tools / libraries used to persist data. | [ ] | [ ] |
| What case is un-persistent data useful? | [ ] | [ ] |
| Storing data in User Defaults (`NSUserDefaults`). | [ ] | [ ] |
| Storing data in `NSKeyedArchiver`. | [ ] | [ ] |
| Storing data in `CoreData`. | [ ] | [ ] |
| Data query methods (reading and writing) used with  |
| `NSUserDefaults` | [ ] | [ ] |
| `NSKeyedArchiver` | [ ] | [ ] |
| `CoreData` | [ ] | [ ] |
| The data storage limits and recommended usage of  |
| `NSUserDefaults` | [ ] | [ ] |
| `NSKeyedArchiver` | [ ] | [ ] |
| `CoreData` | [ ] | [ ] |

-------

### Behaviors

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When I have data to store locally on a device, **Action:** I use the most appropriate persistent Data stores based on the data format. | [ ] | [ ] |
| **Context:** When I need to save relational data, **Action:** I use `CoreData`. | [ ] | [ ] |
| **Context:** When I use `NSKeyedArchiver`, **Action:** I serialize the data manually. | [ ] | [ ] |
| **Context:** When I need to save non-relational data, **Action:** I can use `NSKeyedArchiver` or the User Defaults (`NSUserDefaults`). | [ ] | [ ] |
| **Context:** When saving key-value data or data that is relatively small (String, Int, Bool etc), **Action:** I make use of User Defaults (`NSUserDefaults`). | [ ] | [ ] |

-------

### Beliefs

| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Data is saved on the device when its to read or written frequently. | [ ] | [ ] |
| User Defaults (`NSUserDefaults`) gives me the ability to store lite data for quick access. | [ ] | [ ] |
| `CoreData` runs on SQLite Engine and will allow me store relational data. | [ ] | [ ] |
