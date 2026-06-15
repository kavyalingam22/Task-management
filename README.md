# Task Management App

## Overview
The Task Management App is a Python-based console application that helps users organize and manage their daily tasks. Users can add, remove, view, and prioritize tasks. The application also provides task recommendations based on task priority.

## Features
- Add new tasks with priority levels
- Remove existing tasks
- View all tasks
- Recommend high-priority tasks
- Store tasks in a CSV file for persistence
- Input validation for task priorities
- Error handling for non-existent task removal

## Technologies Used
- Python
- Pandas
- Scikit-learn
- CSV File Storage

## Project Structure

```
Task Management/
│
├── main.py
├── tasks.csv
├── instructions.txt
└── README.md
```

## Installation

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project folder:

```bash
cd Task-Management
```

3. Install required packages:

```bash
pip install pandas scikit-learn
```

## Running the Application

Run the following command:

```bash
python main.py
```

## Menu Options

1. Add Task
2. Remove Task
3. List Tasks
4. Recommend Task
5. Exit

## Testing and Debugging

The following tests were performed:

- Verified task addition functionality
- Verified task removal functionality
- Tested removal of non-existent tasks
- Tested task listing functionality
- Tested task recommendation feature
- Tested invalid menu inputs
- Added validation for task priority values (Low, Medium, High)
- Tested application behavior with an empty task list

## Improvements Made

- Fixed task removal logic to display an appropriate message when a task does not exist.
- Added input validation to allow only Low, Medium, and High priority values.
- Improved overall user experience through better error handling.

## Future Enhancements

- Graphical User Interface (GUI)
- Task deadlines and reminders
- Advanced machine learning recommendations
- Task completion tracking
- User authentication

## Author

Developed as part of a Task Management Application project using Python and basic Machine Learning concepts.
