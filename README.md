# taskManagerCSC131
**Markdown for java TM**

Main Method
===========

Calls four different methods

* start command
* stop command
* describe command
* summary command

Start
--------
   ***Receive & pass two args***

Start method formats the Date of the task

Marks the start of the timer

Stop 
-------
***has one argument***

Stamps time and date at end of the task


Task Timer method
------
***2 args***

This takes the start and stop time marks

  & Calculates the total time for task
  
T-shirt Size Void
----------
***this command adds tshirt sizes to the summary***
Three args are passed to the void

S, M, L, XL
  
Description Command
----------
***three arguments***

Passes the task name and task description

Logs the description 

Delete Command
-------------
***this cmd takes in one args and removes the task information from txt file***

The file input is rewritten to remove the specific task in args


Rename Command
----------------
***the command passes the old task name and the new task name***

the renameTask function open data file and searches for the old task name
the new task name replaces the old, in the data file and log file


minForTaskSize
------------------

***finds the task with the specified size name and arranges the minimum time spent on task***
this is done by opening the task data file and matching the size names

then the tasks are compared to find the minimum spent time


minForTaskSize
-------------------
***find the max time for the size specified***
finding the max time on task based on the unique shirt size
search is done through the data task txt file and compared from task to task


Log class
-------
***3 args***

* Collects the date and time of task
* Shows name of task & commands entered
