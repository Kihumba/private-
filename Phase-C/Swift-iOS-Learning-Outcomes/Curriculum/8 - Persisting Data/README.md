# Outcome 8 - Persisting Data
## Skill Description

In real life applications, data is received and sent over-the-air (OTA) following the CRUD pattern (Create, Read, Update and Delete). More often than none, data will need to be accessed offline, data that might affect the way requests are made to the server or data thats written and read frequently. This Skill covers the methods available in iOS that can be used to persist data on a mobile device.

## Output
After attaining this skill, and as a demonstration of it, a person should be able to create the following:

- An iOS Project is to be created which includes `CoreData` in the project initialization. The Project will write and read Sample Data into all 3 storage systems, User Defaults (`NSUserDefaults`), `NSKeyedArchiver` and `CoreData`.

## Objectives
### Knowledge

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| Why is it important to Persist Data? | [ ] | [ ] |
| What type of data can be persisted?  | [ ] | [ ] |
| What tools / libraries can be used to persist data? | [ ] | [ ] |
| What case is un-persistent data useful? | [ ] | [ ] |
| What type of data can be stored in User Defaults (`NSUserDefaults`)? | [ ] | [ ] |
| What type of data can be stored in `NSKeyedArchiver` | [ ] | [ ] |
| What type of data can be stored in `CoreData`? | [ ] | [ ] |
| What query structure is employed in the various Data storage systems?  | [ ] | [ ] |
| What are the storage limits of the Data storage systems? | [ ] | [ ] |

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
| I believe that data should be saved on the device when its to read or written frequently by the device. | [ ] | [ ] |
| I believe that User Defaults (`NSUserDefaults`) is used to get / set data only when quick access to said data is required. | [ ] | [ ] |
| I believe that `CoreData` can be used to save relational data on a local device. | [ ] | [ ] |
| I believe that `CoreData` runs on SQLite Engine in the background. | [ ] | [ ] |
