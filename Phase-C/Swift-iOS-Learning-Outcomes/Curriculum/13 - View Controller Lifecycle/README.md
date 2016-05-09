# Outcome 13 - View Controller Lifecycle
## Skill Description

These consists of methods that iOS automatically calls at appropriate times when a view controller transitions between states. When you create a view controller subclass, it inherits the methods defined in `UIViewController` and lets you add your own custom behavior for each method (overriding). It’s important to understand when these methods get called, so you can set up or tear down the views you're displaying at the appropriate state.

## Output
After attaining this skill, and as a demonstration of it, a person should be able to create the following:

- Create an iOS project that overrides the four major View Controller Lifecycle functions (highlighted in the Knowledge Objective). The dummy view controller should be presented from any parent View Controller. Animations will be rendered right after the View is rendered, a simple text (describing the state) is shown in a dialog (and logged in the console) after each state is reached.

## Objectives
### Knowledge

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| _What states trigger the methods below_ |
| `viewDidLoad()` | [ ] | [ ] |
| `viewDidAppear(animated: Bool)` | [ ] | [ ] |
| `viewWillUnload()` | [ ] | [ ] |
| `viewWillAppear(animated: Bool)` | [ ] | [ ] |
| How often are the Lifecycle functions called? | [ ] | [ ] |
| The _will_ Lifecycle functions are called before the _did_ Lifecycle functions in iOS. | [ ] | [ ] |
| Some other important methods to override in your Controller. |
| `prepareForSegue(segue: UIStoryboardSegue, sender: AnyObject?)` | [ ] | [ ] |
| The Operations that should be carried out in these functions. | [ ] | [ ] |

------

### Behaviors

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| When I create a View Controller, I override the methods I need, to run my procedures at the appropriate Application State. | [ ] | [ ] |
| When I need to run a procedure in the View Controller, I add my procedure to the `viewWillAppear` function, which runs just before the Views are displayed. | [ ] | [ ] |
| When I need to render animations in a View, I add my procedure to the `viewDidAppear` function, which is called just after the View has been rendered. | [ ] | [ ] |
| When I need to run a procedure just once in a `UIViewController`, I add the procedure to the `viewDidLoad` function, as it only runs once after the `UIViewController` has been loaded (excluding memory warning exceptions). | [ ] | [ ] |
| When I need to run a procedure just before a ViewController is dismissed, I add my procedure to the `viewWillUnload` function, which runs just before the `viewDidUnload` (read-only) function is called. | [ ] | [ ] |

------

### Beliefs

| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| The user experience of my Application can be controlled to the detail when I  overriding the Lifecycle functions. | [ ] | [ ] |
