# Bash To-Do List Manager

A simple, command-line to-do list manager written in Bash. This script allows users to add, view, and remove tasks saved in a local todo.txt file. It’s lightweight, easy to use, and great for learning and practicing Bash scripting skills.

---

# Features

Add Task: Append a new task to the to-do list.
List Tasks: Display all tasks with numbering for easy reference.
Remove Task: Delete a specific task by entering its number.
Clear All Tasks: Erase all tasks from the list with a single command.
Persistent Storage: Tasks are stored in todo.txt, ensuring they persist between sessions.
Getting Started

---

# Prerequisites
No additional dependencies are required beyond a Unix-like environment with Bash (usually pre-installed on Linux and macOS). This script is compatible with Bash 4.0+.

## Installation
Clone the repository and navigate to the project folder:

`git clone https://github.com/godriele/todo-list.git`

`cd todo-list`

### Make the script executable:
`chmod +x todo.sh`

### Usage
Run the script and follow the prompts to add, view, remove, or clear tasks.
./todo.sh
You’ll see a menu similar to this:
--- To-Do List Manager ---
1. Add Task
2. List Tasks
3. Remove Task
4. Clear All Tasks
5. Exit
Choose an option:
Example Workflow
After selecting option 1 to add tasks, you can then use option 2 to list them:
Your To-Do List:
1. Finish project report
2. Buy groceries
3. Call the dentist
Choosing option 3 allows you to delete a task by its number, making it easy to keep your list up-to-date.

---

# Error Handling

The script includes basic error handling:
Ensures valid input (e.g., integer values for task numbers).
Handles edge cases, such as attempting to remove a task from an empty list or entering an invalid task number.

--- 

# Future Improvements

Planned enhancements for future versions include:
Mark Task as Complete: Option to mark tasks as completed.
Priority Tags: Support for tagging tasks by priority level.
Search and Filter: Ability to search or filter tasks by keyword.
Color-Coded Output: Distinguish between pending and completed tasks visually.
Contributing

Contributions are welcome! Feel free to fork the repository, submit a pull request, or open an issue to discuss potential improvements.
License

This project is licensed under the MIT License.
