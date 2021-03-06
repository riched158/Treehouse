
## Project 3

## How  to use
To use run **python worklog.py** and follow the menu options.  Data entries are stored in **worklog.csv**

## Work Log
In order to prepare better timesheets for your company, you've been asked to develop a terminal application for logging what work someone did on a certain day. The script should ask for a task name, how much time was spent on the task, and any general notes about the task. Record each of these items into a row of a CSV file along with a date.

Provide a way for a user to find all of the tasks that were done on a certain date or that match a search string (either as a regular expression or a plain text search). Print a report of this information to the screen, including the date, title of task, time spent, and general notes.

As a user of the script, I should be able to choose whether to add a new entry or lookup previous entries.

As a user of the script, if I choose to enter a new work log, I should be able to provide a task name, a number of minutes spent working on it, and any additional notes I want to record.

As a user of the script, if I choose to find a previous entry, I should be presented with four options: find by date, time spent, find by exact search, find by pattern.

As a user of the script, if finding by date, I should be presented with a list of dates with entries and be able to choose one to see entries from.

As a user of the script, if finding by an exact string, I should be allowed to enter a string and then be presented with entries containing that string in the task name or notes.

As a user of the script, if finding by a pattern, I should be allowed to enter a regular expression and then be presented with entries matching that pattern in their task name or notes.

## Extra Credit 
Menu has a “quit” option to exit the program.

Records can be deleted and edited, letting user change the date, task name, time spent, and/or notes.

Can find entries based on a ranges of dates. For example between 01/01/2016 and 12/31/2016.

Records are displayed one at a time with the ability to page through records (previous/next/back).

