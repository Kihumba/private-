# Outcome - Mailers

Skill Description
----------
Sending emails in an application is one of the most common features any application possesses today. This outcome treats sending mails using Rails inbuilt mailing service Mailers.

Outputs
----------
Use mailers and mail services in checkpoint 2 and simulation project.
Write a blog post on 3 most popularly used mail services, their similarities and differences.


----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
| What is a mailer? | [ ] | [ ]  |
| How do you set up a new mailer from the command line? | [ ] | [ ]  |
| How are mailers similar to controllers? To models? | [ ] | [ ]  |
| How do you pass instance variables from the mailer to the mailer view? | [ ] | [ ]  |
| Why do you need both a text and HTML version of your mails? | [ ] | [ ]  |
| How do you send an email directly from the Rails console? | [ ] | [ ]  |
| How can you take advantage of add-ons and third-party programs to send email? | [ ] | [ ]  |
| What is the letter_opener gem good for?| [ ] | [ ]  |
| Why can't you use *_path link helpers in mailer views?| [ ] | [ ]  |
| How do you style up a pretty looking HTML email?| [ ] | [ ]  |


----------


## **Behaviors**


| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When I need to send emails... **Action:** I use rails mailer. | [ ] | [ ]  |
| **Context:** When generating a mailer class... **Action:** I use the command line to set it up using rails generate mailer [mailer name] | [ ] | [ ]  |
| **Context:** When setting up mailers... **Action:** I set up background jobs to handle sending mails. | [ ] | [ ]  |
| **Context:** When setting up mailing functionality in the development environment... **Action:** I use letter_opener gem to test that the email functionality works without sending a bunch of emails to users. | [ ] | [ ]  |
| **Context:** When setting up mailing functionality in the production environment... **Action:** I use mail services like sendgrid, mailchimp, mailgun etc. since they can handle email load efficiently. | [ ] | [ ]  |
| **Context:** When I am adding links to emails... **Action:** I use full URLs with the _url helper method as against _path since the user will be opening the email and clicking the link at an external source. | [ ] | [ ]  |
| **Context:** When styling emails... **Action:** I use inline css or style tag.  | [ ] | [ ] |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| With mailers, I can set up a mailing service with ease. | [ ] | [ ]  |
| Emails sent from the main application affects performance. | [ ] | [ ]  |
| Mail services are powerful and reliable. | [ ] | [ ]  |
| I don’t have to send emails to a user’s inbox before I know that a mail functionality works. | [ ] | [ ]  |
