# 📘 Assignment: Functions and Modular Design

## 🎯 Objective

Build a small, organized Python program using reusable functions and modules. By the end of this assignment, you will practice writing clear function interfaces, splitting code into multiple files, and using imports to keep your code maintainable.

## 📝 Tasks

### 🛠️	Build Reusable Functions

#### Description
Create a module named `task_manager.py` with focused functions that each do one job. Your functions should make it easy to add and summarize tasks for a student planner.

#### Requirements
Completed program should:

- Create a function `add_task(tasks, title, category, completed=False)` that adds a task dictionary to a list and returns the updated list.
- Create a function `count_by_category(tasks)` that returns a dictionary with category counts.
- Create a function `completion_rate(tasks)` that returns the completion percentage as a float between `0` and `100`.


### 🛠️	Create a Main Program with Imports

#### Description
Create a separate file named `main.py` that imports your functions and demonstrates them with sample data. Keep your program readable by using a `main()` function and the standard Python entry point pattern.

#### Requirements
Completed program should:

- Import functions from `task_manager.py` into `main.py`.
- Use your functions with at least 5 sample tasks across at least 2 categories.
- Print a clear summary that includes total tasks, category counts, and completion rate.
