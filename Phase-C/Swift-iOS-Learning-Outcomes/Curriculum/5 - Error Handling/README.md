# Outcome 5 - Error Handling
## Skill Description

Error handling is the process of responding to and recovering from error conditions in your program. Swift provides support for throwing, catching, propagating, and manipulating recoverable errors at runtime.

Error handling is important as programming in its dynamism could have properties and attributes set and unset at runtime.
A common scenario could be reading or writing a file programmatically. The file, being independent of the program could not exist or even have restricted read/write permissions, etc. These cases need to be taken care of, and that's were error handling comes in.

## Output

After attaining this skill, and as a demonstration of it, a person should be able to create the following:

- A Swift Playground project that handles errors generated from bad inputs into a function and performs a different operation to cater for the error thrown that allows for normal operation of the application.
- A Swift Playground Program that throws a custom error when it receives and invalid input, without any form of error handling. The custom Error should be enumerated and catch as such.
- A Swift Playground Program that catches any generic error as NSError, and outputs the error message.

- **Detailed and Documented coverage of this skill can be shown by completing _Checkpoint 1_, available upon request.**


## Objectives
### Knowledge

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| The properties of common error class in Swift `NSError` (domain, code). | [ ] | [ ] |
| Types of Errors in Swift. | [ ] | [ ] |
| Handling errors in Swift using `do-try-catch` blocks. | [ ] | [ ] |
| Throwing errors using `guard-throws`. | [ ] | [ ] |

-------

### Behaviors

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When dealing with Errors in Swift, **Action:** I can easily relate its structure with Exceptions in other programming languages and leverage on that as the case may be. | [ ] | [ ] |
| **Context:** When throwing Errors that have steps or categories, **Action:** I create an enumerated ErrorType that throws different Errors in steps to increase flexibility in the Error Handling.  | [ ] | [ ] |
| **Context:** When I need to catch an Error from an Abstracted method, **Action:** I catch the Error as an NSError type and proceed to displaying the Error message as the case may be.  | [ ] | [ ] |

-------

### Beliefs

| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Applications can crash at runtime if errors are not handled. | [ ] | [ ] |
