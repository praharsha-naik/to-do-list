Python To-Do List

A beginner-friendly command-line to-do list app written in Python. Add tasks, view them, mark them complete, and delete them. Tasks are saved in `tasks.json` so they are still there the next time you run the program.

## Features

- View all tasks
- Add tasks
- Mark tasks complete
- Delete tasks
- Save tasks between runs with a JSON file
- Handle empty input and invalid task numbers
- No extra packages required

## Requirements

Python 3.8 or newer.

## Run it

1. Download or clone this repository.
2. Open a terminal in the project folder (the folder containing `todo.py`).
3. Run:

   ```bash
   python todo.py
   ```

   If your computer uses the `python3` command, run `python3 todo.py` instead.

## Use the app

Choose a menu number and press Enter:

1. View tasks
2. Add a task
3. Mark a task complete
4. Delete a task
5. Quit

When prompted to select a task, enter its number from the displayed list. Completed tasks appear with a check mark.

## Run it in Programiz

Programiz's online compiler may not keep a local `tasks.json` file between runs. For a simple version there, replace the `load_tasks` and `save_tasks` functions with these in-memory versions:

```python
def load_tasks():
    return []


def save_tasks(tasks):
    pass
```

The app will work while it is running, but its tasks will not be saved after you close or restart it. Use the full version on your computer to keep tasks between runs.

## Project files

```text
python-todo-list/
├── todo.py      # To-do list program
├── tasks.json   # Created automatically when you add or change a task
├── README.md    # Project instructions
└── LICENSE      # MIT license
```

## Ideas for improvements

- Add due dates
- Add task categories or priorities
- Edit an existing task
- Search tasks by keyword
- Add a graphical interface

## License

This project is available under the MIT License. See [LICENSE](LICENSE).
