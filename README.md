## Fall 2022 CS346 Project [(Version 4.4.0)](Sprint-4-Release(LATEST-VERSION))

Tisk: A to-do list application for Windows, MacOS, Linux systems.

![image](/uploads/a77e2e47655842c99f2541fe72c03555/image.png)

Team: Mahan Sharifi, Trevor Sun, Jasmine Xu, Shawn Sun (Team 202)

Tech Stack: <span dir="">Kotlin, Jetpack Compose, AWS Lambda, AWS API Gateway, AWS Incognito</span>

[Website](https://mahansharifi.github.io/346-Tisk/Home)


## Usage Instructions

Here are some basic instructions for using Tisk(thorough tutorial on website, including video tutorials).

* Type the title on top of the app, press enter to add it to today's tasks.
* Click plus sign (+) on right side of "Tisk" bar to modify description, date, tag, priority, etc.
* Create new tag or priority or pick existing tag/priority. Both options are supported.
* Click on sort by Priority button to sort tasks from high to low priority in Tasks column.
* Click on up and down arrow to move tasks up and down in Tasks column.
* Click button to the left of tasks to mark them as done, they can be found in "Archives".
* Click on the tasks in Tasks column to edit name, description, tag, priority and due date.
* Enter year and month in Calendar column to see that month's calendar.
* Days that have tasks due are black, others remain white on the calendar.
* Click on a date on calendar to show tasks that are due on that date.
* Click on "Filters" in Navigation bar on the left of screen to show tasks within a tag.
* In "Filters", filter tasks by tag by choosing a tag on the top right corner.
* In "Priority", filter tasks by priority by choosing a priority on the top right corner.
* In "Archives", click button on the left of the task to delete it permanently.
* In "Archives", click on the task to change task info, restore button restores the task.
* In "Settings", click on icon i to change between light mode and dark mode
* In "Settings", click on Sign up or Sign in to use your personal account.

Video Instructions:

* [Main Features Guide](https://www.youtube.com/watch?v=CswWanrHm1k)
* [SignIn Guide](https://git.uwaterloo.ca/m48shari/cs346-project/-/blob/main/our%20documents/SignIn.mp4)
* [MacOS Installation Guide](https://gitlab.uwaterloo.ca/j366sun/tisk_installers/-/blob/main/Screen_Recording_2022-12-05_at_5.30.52_PM.mov)

Hotkeys/shortcuts:

* Ctrl+s --> sort by priority
* Ctrl+p --> duplicate task
* ctrl + 1 (HomePage)
* ctrl + 2 (filtersPage)
* ctrl + 3 (priorityPage)
* ctrl + 4 (ArchivesPage)
* ctrl + 5 (SettingsPage)
* NOTE: Changing pages using hotkeys sometimes only works from the homepage 
* ctrl + p (duplicateTodays Tasks)
* ctrl + w (sortTomorrows Tasks)

## Installation Instructions

To install **Tisk**, choose one of the versions below.

The latest version is: [Sprint 4 Release](Sprint-4-Release(LATEST-VERSION))

## Dependencies (Third Party Libraries)

JetPack Compose for Desktop

* UI

AWS

* AWS DynamoDB
* AWS Lambda
* AWS Api Gateway
* AWS Cognito
* Used as our cloud DB service

Kotlin Exposed

* Exposed Core
* Exposed DAO
* Used to perform operations to local DB

H2 Database

* Used for our local DB

Multiplatform Settings

* Used to persist login-state, logged-in username

GSON

* Parse JSON strings into Data Objects

Native Parameter Store Access

* Used to detect current desktop mode (Night/light theme)

## Releases

* [Sprint 1 Release](Sprint%201%20Release)
* [Sprint 2 Release](Sprint%202%20Release)
* [Sprint 3 Release 1](Sprint%203%20Release1)
* [Sprint 3 Release 2](Sprint-3-Release2(LATEST-VERSION))
* [Sprint 4 Release(LATEST VERSION)](Sprint-4-Release(LATEST-VERSION))
