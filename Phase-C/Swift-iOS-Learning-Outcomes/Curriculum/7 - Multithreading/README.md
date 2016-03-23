# Outcome 7 - Multithreading
Skill Description
-----
Keeping your app responsive is easier said than done. Once your app needs to perform more than a handful of tasks, things get complicated quickly. There isn’t much time to perform heavy work in the main run loop and still provide a responsive UI. Such tasks could be delegate to run in the background (new threads), so they don’t affect or slow down the UI interaction of the application.


Outputs
-------
After attaining this skill, and as a demonstration of it, a person should be able to create the following:

1. An iOS project that performs an operation in a background thread before doing the same on the main thread

## Knowledge

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| What is Multithreading? | [ ] | [ ] |
| Why it is important to run tasks in parallel. | [ ] | [ ] |
| What are the available Multithreading methods in Swift? | [ ] | [ ] |
| How is the _Grand General Dispatcher_ used? | [ ] | [ ] |
| What are queues? | [ ] | [ ] |
| How is _NSOperation_ used? | [ ] | [ ] |
| How is _NSThread_ used? | [ ] | [ ] |


## Behaviors

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When I run processes that should not distort the user interface of an application  **Action:** I run the processes on a new background thread.  | [ ] | [ ] |
| **Context:** When I create a background thread, **Action:** the thread should be created on a background queue, not on the main queue. | [ ] | [ ] |
| **Context:** When I need to run a method that interacts with the User Interface, **Action:** I run the process on the main queue, which is the UI Thread. | [ ] | [ ] |
| **Context:** When I need to run two or more processes that consume resources, **Action:** I run them on new threads in parallel. | [ ] | [ ] |

## Beliefs

| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| I believe that running background processes on new threads will prevent my app from Freezing. | [ ] | [ ] |
| I believe that running two or more processes in parallel will make them complete and produce results on time and asynchronously. | [ ] | [ ] |
