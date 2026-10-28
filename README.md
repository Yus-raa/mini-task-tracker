# Mini Task Tracker

## Goal
This project is a simple menu-based Python program for managing tasks. It saves tasks in a JSON file and loads them again when the program starts.

## Features
- Add a task with Pending status
- View numbered tasks and their status
- Mark a task as Done
- Delete a task
- Save and load tasks using JSON
- Handle blank titles, invalid menu choices, invalid task numbers, and a missing JSON file

## Requirements
- Python 3
- Python's built-in `json` module

## How to Run
1. Download or clone this repository.
2. Open a terminal in the project folder.
3. Run `python mini_task_tracker.py`.
4. Follow the menu instructions.

The program creates `tasks.json` to store tasks in the same folder.

## Task Data Format
Each task is stored as a dictionary with a title and a Boolean `done` value. For example:

```json
{
    "title": "Read notes",
    "done": false
}
```
