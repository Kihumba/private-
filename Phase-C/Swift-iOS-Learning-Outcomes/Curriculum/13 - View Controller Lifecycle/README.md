# Outcome 13 - View Controller Lifecycle
## Skill Description

These consists of methods that iOS automatically calls at appropriate times when a view controller transitions between states. When you create a view controller subclass, it inherits the methods defined in `UIViewController` and lets you add your own custom behavior for each method (overriding). It’s important to understand when these methods get called, so you can set up or tear down the views you're displaying at the appropriate state.

## Output
After attaining this skill, and as a demonstration of it, a person should be able to create the following:

Create an iOS project that

- Overrides the four major view controller lifecycle functions (highlighted in the Knowledge Objective).
- Has a dummy view controller that presents from any parent viewcontroller. 
- Has Animations will be performed right after the view is rendered, 
- Shows the state in a dialog (and logged in the console) after each state is reached.

## Objectives
### Knowledge

| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| What is the lifecycle of a view controller? | [ ] | [ ] |
| What event triggers `viewDidLoad()` to be called, and what state is the View Controller in at that moment| [ ] | [ ] |
| What event triggers `viewDidAppear()` to be called, and what state is the View Controller in at that moment| [ ] | [ ] |
| What event triggers `viewWillUnload()` to be called, and what state is the View Controller in at that moment| [ ] | [ ] |
| What event triggers `viewWillAppear()` to be called, and what state is the View Controller in at that moment| [ ] | [ ] |
| How does one decide what operations should and should not be carried out in the lifecycle functions? | [ ] | [ ] 
| When are the lifecycle functions called? | [ ] | [ ] |
| What are the differences between _will_ lifecycle functions and _did_ lifecycle functions in iOS? | [ ] | [ ] |
<!--| Some other important methods to override in your Controller. |   What other methods? need more details-->
<!-- | `prepareForSegue(segue: UIStoryboardSegue, sender: AnyObject?)` | [ ] | [ ] |     This is just a method call name, identify what knowledge of segue lifecycles are important and be sure to include that in the Output. -->


------

### Behaviors

| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When I create a View Controller **Action:** I override only the lifecycle methods I need | [ ] | [ ] |
| **Context:** When I write code in a lifecycle method **Action:** it reflects an understanding of what state the view controller is in at that time. | [ ] | [ ] |
| **Context:** When I want to run a procedure before the view is displayed **Action:**  I add my procedure to the `viewWillAppear` function | [ ] | [ ] |
| **Context:** When I want to render animations in a view **Action:**  I add my procedure to the `viewDidAppear` function | [ ] | [ ] |
| **Context:** When I need to run a procedure just once in a `UIViewController` **Action:** I add the procedure to the `viewDidLoad` function | [ ] | [ ] |
| **Context:** When I need to run a procedure just before a ViewController is dismissed **Action:** I add the procedure to the `viewWillUnload` function | [ ] | [ ] |

------

### Beliefs

| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|

| I believe that overriding the Lifecycle functions gives me the flexibility to control the details of the the user experience. | [ ] | [ ] |
