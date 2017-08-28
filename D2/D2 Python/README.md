# Asynchronous Programming With Twisted

## Skill description:

A fellow is able to use Twisted's concurrency model to write asynchronous, event-driven networked programs in Python.


## Output:

*Task:* Imagine you have a function which sends an email summarizing some information on your application, demonstrate how your email sending function would work using Twister’s ‘non-blocking calls’ model


### Knowledge:
| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| What Is Asynchronous programming? | [ ] | [ ] |
| What are the advantages and disadvantages of Asynchronous programming
| What is Twisted? | [ ] | [ ] |
| How concurrent programming works. | [ ] | [ ] |
| How to use Twisted framework models to write asynchronous, event-driven networked programs in Python | [ ] | [ ] | 
| How to use callbacks model for alerting an application that some data is ready for it is known | [ ] | [ ] |
| How to use deferred object to manage the callback sequence. | [ ] | [ ] |
| How to use errbacks method to handle errors. | [ ] | [ ] |


### Behaviors:

Context: When I’m dealing with many connections in one thread, Action: I use Twisted’s non-blocking calls model to schedule events by calling a registered function when each connection is ready for reading or writing.
Context:  When I want a function to requests the data in my application, Action: I let the library call the callback function when the data is ready.
Context: When I want to tell a Deferred what to do with the data once it arrives, Action: I add a callback — asking the Deferred to call a function once the data arrives.
Context: When I want to detect errors in my application, Action: I add error handlers ('errbacks') to a Deferred for it to call when an error occurs.


Beliefs:

Asynchronous programming primarily depends on non-blocking code
Twisted's deferred abstraction, symbolizes a 'promised' result that can pass an eventual result to handler functions.
The Asynchronous model performs best when:
There are a large number of tasks so there is likely always at least one task that can make progress.
The tasks perform lots of I/O, causing a synchronous program to waste lots of time blocking when other tasks could be running.
The tasks are largely independent from one another so there is little need for inter-task communication (and thus for one task to wait upon another).


### Resources: 
[Twisted Matrix](https://twistedmatrix.com/trac/)

[Twisted Doc](http://twistedmatrix.com/documents/8.2.0/core/howto/async.html)

