# Outcome 5 - Error Handling
## Skill Description

Error handling is the process of responding to and recovering from error conditions in your program. Swift provides support for throwing, catching, propagating, and manipulating recoverable errors at runtime.

Error handling is important as programming in its dynamism could have properties and attributes set and unset at runtime.
A common scenario could be reading or writing a file programmatically. The file, being independent of the program could not exist or even have restricted read/write permissions, etc. These cases need to be taken care of, and that's were error handling comes in.

## Output

After attaining this skill, and as a demonstration of it, a person should be able to create the following:

- A Swift Playground project that handles errors generated from bad inputs into a function and performs a different operation to cater for the error thrown that allows for normal operation of the application.
- A Swift Playground Program that throws a custom error when it receives an invalid input. The custom Error should be enumerated and caught.
- A Swift Playground Program that catches any generic error as NSError, and outputs the error message.

## Objectives
### Knowledge

| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| What class is commonly used to represent errors in Swift? (`NSError`)? | [ ] | [ ] |
| What types of errors exist in Swift? | [ ] | [ ] |
| What’s the syntax for catching Errors in Swift? `do-try-catch` | [ ] | [ ] |
| How do I throw an Error? `guard-throws` | [ ] | [ ] |
| The differences between a run-time error and a compiling error. | [ ] | [ ] |

-------

### Behaviors

| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When throwing Errors that have steps or categories, **Action:** I create an enumerated ErrorType that throws different Errors in steps to increase flexibility in the Error Handling.  | [ ] | [ ] |
| **Context:** When I need to catch an Error from an Abstracted method, **Action:** I catch the Error as an NSError type and proceed to displaying the Error message as the case may be.  | [ ] | [ ] |
<!-- these behaviors do not reflect the application of the knowledge above and need to be rewritten. A better Ex:
**Context:** When I need to write some data to a file that may or may not exist, **Action:** I use a try block to open the file and throw a self-explanatory error if it fails.
-->


-------

### Beliefs

| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Handling and dealing with errors will avoid the application from crashing at runtime. | [ ] | [ ] |
