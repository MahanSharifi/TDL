## TISK - TO-DO List Multiplatform Desktop Application

## CODE HERE!!!!! ****: https://drive.google.com/file/d/12XFLTZpjgYsL2m2OKyXqDShWo8IJNOF_/view?usp=sharing
# Due to having it uploaded on another version controller, it would not let me upload to github, but the ZIP is available here.

Tisk: A to-do list application for Windows, MacOS, Linux systems.

* [Main Features Youtube Guide](https://www.youtube.com/watch?v=CswWanrHm1k)
* [SignIN Youtube Guide](https://youtu.be/2VhXFM-Ffdc)

Tech Stack: <span dir="">Kotlin, Jetpack Compose, AWS Lambda, AWS API Gateway, AWS Incognito</span>


## Releases
Sprint 1:
Windows: * [Windows installer](https://git.uwaterloo.ca/j366sun/tisk_installers/-/raw/main/Tisk-1.0-1.0.0.exe?inline=false)

MAC: * [macOS installer](https://git.uwaterloo.ca/j366sun/tisk_installers/-/raw/main/CS346-Tisk-1.0.0.dmg?inline=false)


Sprint 2:
Windows:* [Windows installer](https://git.uwaterloo.ca/j366sun/tisk_installers/-/raw/main/Tisk-2.1-2.1.0.exe?inline=false)

MAC:* [macOS installer](https://git.uwaterloo.ca/j366sun/tisk_installers/-/raw/main/Tisk-2.1-2.1.0.dmg?inline=false)

Sprint 3 Release 1:
Windows:* [Windows installer](https://git.uwaterloo.ca/j366sun/tisk_installers/-/raw/main/Tisk-3.0-3.0.0.exe?inline=false)
MAC:* [macOS installer](https://git.uwaterloo.ca/j366sun/tisk_installers/-/raw/main/Tisk-3.0-3.0.0.dmg?inline=false)


Sprint 3 Release 2:
Windows:* [Windows installer](https://gitlab.uwaterloo.ca/j366sun/tisk_installers/-/raw/main/Tisk-3.2-3.2.0.exe?inline=false)
MAC:* [macOS installer](https://gitlab.uwaterloo.ca/j366sun/tisk_installers/-/raw/main/Tisk-3.2-3.2.0.dmg?inline=false)


Sprint 4: FINAL VERSION
Windows:* [Windows installer](https://gitlab.uwaterloo.ca/j366sun/tisk_installers/-/raw/main/Tisk-4.4-4.4.0.exe?inline=false)
MAC:* [macOS installer](https://gitlab.uwaterloo.ca/j366sun/tisk_installers/-/raw/main/Tisk-4.4-4.4.0.dmg?inline=false)
Linux: * [Linux installer](https://gitlab.uwaterloo.ca/j366sun/tisk_installers/-/raw/main/Tisk-4.4-macos-arm64-4.4.0.jar?inline=false)

MacOS installation guide:

If you have Ventura:

* <span dir="">xattr -d </span><span dir="">com.apple</span><span dir="">.quarantine</span> {your.file.path}

(you can drag the app from finder to terminal for the file.path)

If you have previous versions of MacOS, consider updating to the latest System.

Or, follow the link for detailed information : https://iboysoft.com/news/app-is-damaged-and-cannot-be-opened.html

p.s. Since Apple requires all 3-rd party apps to be signed and notarized and this process costs 120 CAD, we will not be signing the app this term and thus the only way to open the app is to use the resources linked above


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
* [SignIN Youtube Guide](https://youtu.be/2VhXFM-Ffdc)

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


