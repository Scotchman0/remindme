# task

A work in progress repository to hold a reminder CLI toolkit - version 0.2

# RECENT PATCH:
- removed '-a', tasks now print with 'task' command by default
- added '-d' (wip) - to delete line entries with SED, should have the syntax figured out shortly
- moved ~/.remindme_reminders, replaced with variable $TASKPATH at default value= ~/.task_list

# NEXT UPDATE GOALS:
- fully implement '-d' removal by line
- add reminders with 'at' + system notification/alerts

# Overview:
A simple CLI task manager that lets you print strings to a file for CLI recall/management. Echos contents to `~/.*shrc` on new shell startup and can be called manually with 'task'
Work in progress
