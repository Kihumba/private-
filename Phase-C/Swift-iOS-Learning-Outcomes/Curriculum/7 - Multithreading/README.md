# Outcome 7 - Multithreading
## Skill Description

Keeping your app responsive is easier said than done. Once your app needs to perform more than a handful of tasks, things get complicated quickly. There isn’t much time to perform heavy work in the main run loop and still provide a responsive UI. Such tasks could be delegate to run in the background (new threads), so they don't affect or slow down the UI interaction of the application.


## Outputs

After attaining this skill, and as a demonstration of it, a person should be able to create the following:

- An iOS project that performs an operation in a background thread and displays the result in the main thread on completion.

- **Detailed and Documented coverage of this skill can be shown by completing _Checkpoint 2_, available upon request.**

## Objectives
### Knowledge

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| Multithreading, working with different queues in Swift. | [ ] | [ ] |
| Importance of running tasks in Parallel (Async over Sync). | [ ] | [ ] |
| Using the _Grand General Dispatcher_. | [ ] | [ ] |
| The generic Queues available in Swift. | [ ] | [ ] |
| Multithreading with _NSOperation_. | [ ] | [ ] |
| Multithreading with _NSThread_ used. | [ ] | [ ] |

-------

### Behaviors

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When I run processes that should not distort the user interface of an application  **Action:** I run the processes on a new background thread.  | [ ] | [ ] |
| **Context:** When I create a background thread, **Action:** the thread should be created on a non-blocking queue, not on the main queue. | [ ] | [ ] |
| **Context:** When I need to run a method that interacts with the User Interface, **Action:** I run the process on the main queue. | [ ] | [ ] |
| **Context:** When I need to run two or more processes that consume resources, **Action:** I run them on new threads in parallel. | [ ] | [ ] |

-------

### Beliefs

| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| My Application will not Freeze or stutter if I run blocking processes on background queues. | [ ] | [ ] |
| Processes that run in parallel will complete and return results asynchronously. | [ ] | [ ] |
