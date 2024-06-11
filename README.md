# Task Management Application Guide

## Introduction

### Requirements
- Make sure Python 3.x is installed on your system.

### Environment Setup
- (Optional but advised) Create a virtual environment for dependency management:
  ```sh
  python -m venv task_env
  source task_env/bin/activate  # On Windows: task_env\Scripts\activate
  ```

### Dependency Installation
- Use `pip` to install the necessary libraries:
  ```sh
  pip install pandas scikit-learn
  ```

### Launching the Application
- Navigate to the directory containing `main.py`.
- Start the application by running:
  ```sh
  python main.py
  ```

## Application Features

### Core Functionalities
- **Add Tasks:** Enter task details to include them in your task list.
- **Delete Tasks:** Select tasks to remove from your list.
- **View Tasks:** Display all current tasks.
- **Set Task Priorities:** Organize tasks by setting their priorities.
- **Task Recommendations:** Receive recommendations based on your input.

### Data Handling
- All tasks are saved in a file named `tasks.csv`.

### Closing the Application
- Select option '5' from the menu to exit the application.

Enjoy managing your tasks with this Task Management Application!
