# Outcome 7 - Multithreading
## Skill Description

Keeping your app responsive is easier said than done. Once your app needs to perform more than a handful of tasks, things get complicated quickly. There isn’t much time to perform heavy work in the main run loop and still provide a responsive UI. Such tasks could be delegate to run in the background (new threads), so they don't affect or slow down the UI interaction of the application.


## Outputs

After attaining this skill, and as a demonstration of it, a person should be able to create the following:

- An iOS project that performs an operation in a background thread and displays the result in the main thread on completion.

## Objectives
### Knowledge

| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| What is Multithreading? | [ ] | [ ] |
| When it's important to run tasks in parallel. | [ ] | [ ] |
| What are the available Multithreading methods in Swift? | [ ] | [ ] |
| How is the _Grand General Dispatcher_ used? | [ ] | [ ] |
| What are queues? | [ ] | [ ] |
| What are threads? | [ ] | [ ] |
| How to use _NSOperation_. | [ ] | [ ] |
| How to use _NSThread_. | [ ] | [ ] |

-------

### Behaviors

| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When I run processes that could block the updating of the UI  **Action:** I run the processes on a new background thread.  | [ ] | [ ] |
| **Context:** When I create a background thread, **Action:** the thread should be created on a non-blocking queue, not on the main queue. | [ ] | [ ] |
| **Context:** When I need to run a method that interacts with the User Interface, **Action:** I run the process on the main queue and UI thread. | [ ] | [ ] |
| **Context:** When I need to run two or more processes asynchronously, **Action:** I run them on new threads in parallel. | [ ] | [ ] |

-------

### Beliefs

| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Running background processes on new threads will prevent my app's UI from freezing. | [ ] | [ ] |
| Swift handles running asynchronous code in a way that allows me to take advantage of event driven processes. | [ ] | [ ] |