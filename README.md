# Project Management CLI

A Command-Line Interface (CLI) application for managing users, projects, and tasks. This CLI tool allows you to perform CRUD (Create, Read, Update, Delete) operations on users, projects, and tasks efficiently. It is built using Python, SQLAlchemy, and Click.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)

## Installation

1. Clone the repository to your local machine:
   git clone git@github.com:BettLawi/project-management-cli.git
2. Navigate to the project directory:
    cd project-management-cli
3. Create a virtual environment and install dependencies using Pipenv:    
    pipenv install
4. Activate the virtual environment:
    pipenv shell
5. Run the application
    python main.py  

 ## Usage   
 1. To list available commands:
    python main.py --help
 2. To get help for a specific command, for example, user-related commands:
    python main.py user --help

## Commands
# User Management
1. Create User: Create a new user.
    python main.py user create
2. List Users: List all users.
    python main.py user list
3. Update User: Update user information.
    python main.py user update
4.  Delete User: Delete a user.
    python main.py user delete      

# Project Management
1. Create Project: Create a new project.
    python main.py project create
2. List projects: List all projects.
    python main.py project list
3. Update Project: Update project information.
    python main.py project update
4.  Delete Project: Delete a project.
    python main.py project delete       

# Task Management
1. Create Task: Create a new task.
    python main.py task create
2. List Tasks: List all users.
    python main.py task list
3. Update Task: Update task information.
    python main.py task update
4.  Delete Task: Delete a task.
    python main.py task delete        

# Contributions
Authored by LAWI BETT



