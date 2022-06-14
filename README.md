# Tell-Me-What-To-Do

This is a TODO list project that will be written in Python3, potentially developed into a web application with django. The goal of this project is to create a task list program that organizes things that need to be done by importance, deadline, and other metrics, and when prompted, the program should return the most important thing to do at the moment.

---
## Features
- Store a list of tasks with MySQL. (Not Implemented)
  - Tasks have parameters:
    - Name
    - Deadline (YYYY/MM/DD/hh/mm)
    - Estimated complete time (minutes)
    - Importance
    - Custom weight (for adjustments)
- The list should be sorted. (Not Implemented)
  - List is sorted based on deadline alone by default.
  - The sorting parameter should be able to change.
- Graphic User Interface (Not Implemented)
  - Edit list
  - Print out the entire list.
  - Query for most important task.
- Track task statistics with a timer. (Not Implemented)
  - Old tasks could be archived for data analysis.
---
