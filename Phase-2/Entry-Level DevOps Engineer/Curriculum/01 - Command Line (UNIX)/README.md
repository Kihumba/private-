# Outcome 01 - Command Line (UNIX)

Skill Description
-----------------
The fellow knows the fundamentals of Command Line Unix and knows how to use various Linux/Unix system utilities to perform system administration tasks


Outputs
-------
After attaining this skill, and as a demonstration of it, a fellow should be able to complete the following exercises:

1. Files and Directories
  - Create directory named `some-dir` in the `/tmp` folder
  - Find text `some-text` in all files in directory `/tmp/some-dir`
  - Find files that start with `a` in directory `/tmp/some-dir`
  - List all hidden files and directories that start with letter `a` in the directory `/tmp/some-dir`
  - Display the first 4 lines of the file `/tmp/somefile.txt`
  - Display the last 4 lines of the file `/tmp/somefile.txt`
  - Append text `To Append` to file `/tmp/append.txt`
  - Add text `To Add` to file `/tmp/append.txt` overwriting its contents
  - Change permission of file `/tmp/some-file` to `read only`
  - Change permission of file `/tmp/some-script` to `executable`

2. Software Packages on Linux
  - Add the python software repository `ppa:fkrull/deadsnakes` to the list of available repositories on a system
  - Install the software `python3.5`
  - Uninstall the software `python3.5`

3. Scheduling
  - Schedule a cron entry to add the current system time to file `/tmp/some-file` every 2 hours

4. Processes & Signals
  - List all running processes
  - List all processes owned by the user **some-user**
  - Kill process with PID `12123`
  - Send the interrupt signal to process with PID `12124`
  - Run command `sleep 10` in the background
  - Run command `date` and redirect output to file `/tmp/some-file`

5. Devices
  - Format device `/dev/some-device` as type `xfs`
  - Mount device `/dev/some-device` as type `xfs` to `/myxfs`
  - Unmount device `/dev/some-device`
  - Display the size of the root partition


**Objectives**
--------------

## **Knowledge**

| Knowledge Unit   |      Studied      | Applied |
|:-----------------|:-----------------:|:---------:|
| I can describe the following from memory: | | |
| The functions of package managers in linux distros | [ ] | [ ] |
| Managing files and directories | [ ] | [ ] |
| How to mount, unmount and format devices on a unix system | [ ] | [ ] |
| Scheduling processes | [ ] | [ ] |
| Sending signals to processes | [ ] | [ ] |
| How Shell options control execution in a bash script | [ ] | [ ] |


----------------


## **Behaviors**

| Observable Behavior   |      Practiced      | Observed |
|:----------------------|:------------------:|:--------:|
| **Context:** Before installing software packages **Action:** I update the package sources in my OS distro | [ ] | [ ]  |
| **Context:** When mounting a partition **Action:** I pass in the proper mount flags | [ ] | [ ]  |
| **Context:** When writing scripts **Action:** I enable the shell option to exit immediately when an error occurs | [ ] | [ ]  |
| **Context:** When writing scripts **Action:** I enable the shell option to exit immediately when an unbound variable is found | [ ] | [ ]  |
| **Context:** When writing scripts **Action:** I log actions in the script to provide visibility on command execution | [ ] | [ ]  |
| **Context:** When calling shell commands with arguments **Action:** I quote command arguments | [ ] | [ ]  |
| **Context:** When writing scripts **Action:** I take advantage of and use the various single function utilities in Linux to solve complex tasks | [ ] | [ ]  |


--------------


## **Beliefs**

| Embodied Belief   |      Felt          | Demonstrated |
|:------------------|:------------------:|:------------:|
| I leverage automation to successfully perform a wide variety of system administration tasks | [ ] | [ ] |
| I create reliable systems by appropriately implementating services which results in a reliable system | [ ] | [ ] |
| I review the manual pages (standard software documentation on Unix like systems) to understand how to leverage the various tools available in a Unix system | [ ] | [ ] |
