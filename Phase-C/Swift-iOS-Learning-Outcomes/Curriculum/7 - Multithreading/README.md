# Outcome 7 - Multithreading
## Skill Description

The Fellow will be able to able to run tasks in parallel, utilizing the threads available on the device to run blocking processes in the background to avoid User Experience distortion.


## Outputs

After attaining this skill, and as a demonstration of it, I will create the following:

1. A process in an iOS project that performs an operation in a background thread and displays the result in the main thread on completion.

2. A **Checkpoint 2** project submission meeting all the required specifications.

## Objectives
### Knowledge

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| I can describe the following from memory: | | |
| Working with different queues in Swift | [ ] | [ ] |
| The generic queues available in Swift | [ ] | [ ] |
| The importance of running tasks in parallel | [ ] | [ ] |
| How to use the _Grand General Dispatcher_ | [ ] | [ ] |
| Multithreading with _NSOperation_ | [ ] | [ ] |
| Multithreading with _NSThread_ | [ ] | [ ] |

-------

### Behaviors

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When I run processes that should not distort the user interface of an application  **Action:** I run the processes on a new background thread.  | [ ] | [ ] |
| **Context:** When I create a background thread, **Action:** I create the thread on a non-blocking queue | [ ] | [ ] |
| **Context:** When I need to run a method that interacts with the User Interface, **Action:** I run the process on the main queue | [ ] | [ ] |
| **Context:** When I need to run two or more processes that consume resources, **Action:** I run them on new threads in parallel | [ ] | [ ] |

-------

### Beliefs

| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| My Application will not Freeze or stutter if I run blocking processes on background queues | [ ] | [ ] |
| Processes that run in parallel will complete and return results asynchronously | [ ] | [ ] |
