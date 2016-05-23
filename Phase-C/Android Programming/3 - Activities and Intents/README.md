# Outcome 3 - Activities and Intents

## Skill Description
Every screen in an Android application is an Activity. Activities render the user interface and provides the interactivity between the application and the users. Intents bind activities together at runtime. An application usually consists of multiple activities that are loosely bound to each other. Typically, one activity in an application is specified as the "main" activity, which is presented to the user when launching the application for the first time.  Each time a new activity starts, the previous activity is stopped, but the system preserves the activity in a stack (the "back stack").

## Output
After attaining this skill, and as a demonstration of it, a person should be able to create the following:
- _Build a simple android app which has 3 activities_
  - First activity is a fancy splash screen
  - Second activity shows up after the splash screen vanishes, this activity has an imageView, "upload picture", "take picture" buttons
  - Users should be able able to upload a picture to the imageView or take a picture with camera and load to the imageView
  - Third activity is a settings activity which the "Do not display splashscreen on load option"
- Users should be able to use the back arrow button to move back to previous activities

## Objectives

### Knowledge

| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| What is an Android Activity?| [ ] | [ ] |
| What is the Android Activity lifecycle? How is it harnessed in a typical Android app? | [ ] | [ ] |
| What different activity templates exist for use from the Android studio?| [ ] | [ ] |
| What are intents? What are the use cases of intents? | [ ] | [ ] |
| What are intent filters? How are they used? | [ ] | [ ] |
| What are fragments? What are the cases for using fragments? How to use fragments?| [ ] | [ ] |
| How do we asynchronously load data? We use loaders, then what are loaders? How do they work?| [ ] | [ ] |
| How do we use the backstack  to navigate back between activities? | [ ] | [ ] |

----------

### Behaviors

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When building the views of my android app ... **Action:** I come up with varieties of activities using the Activity template available on the Android studio.| [ ] | [ ]  |
| **Context:**  When creating layouts that share some components ... **Action:** I use only one activity and inflate fragments into the provided content holder within the activity. I put the common components shared by the fragments on the activity. |   [ ]   |   [ ] |
| **Context:** When I need to load data on the background ... **Action:** I use loaders | [ ] | [ ]  |

----------

### Beliefs

| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| Using Android Studio templates saves me time.| [ ] | [ ]  |
| Fragments annihilate code repetition |   [ ]   |   [ ] |
| Using Loaders enhances the user experience  |   [ ]   |   [ ] |