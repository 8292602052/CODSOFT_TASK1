# To-Do List CLI Application

A command-line To-Do List application developed as part of the CodSoft Python Programming Internship. This tool helps users manage their tasks efficiently through an intuitive terminal interface.

## Features

- **Task Management**:
  - Add new tasks with descriptions
  - View all tasks with completion status
  - Mark tasks as completed
  - Delete individual tasks
  - Clear entire task list

- **User-Friendly Interface**:
  - Clean, menu-driven navigation
  - Visual indicators for task status (✓ for completed)
  - Input validation for error prevention

- **Data Persistence**:
  - Tasks maintained during session
  - Simple, in-memory storage implementation

## Installation

1. Ensure you have Python 3.8+ installed
2. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/todo-cli.git
   ```
3. Navigate to the project directory:
   ```bash
   cd todo-cli
   ```

## Usage

Run the application with:
```bash
python todo.py
```

### Menu Options:
1. **Add Task**: Enter a new task to your list
2. **View Tasks**: See all tasks with their completion status
3. **Mark Completed**: Update a task's status to completed
4. **Delete Task**: Remove a specific task
5. **Clear All**: Remove all tasks (with confirmation)
6. **Exit**: Close the application

## Technical Details

- **Data Structure**: Uses list of dictionaries to store tasks
- **Input Validation**: Handles invalid user inputs gracefully
- **Modular Design**: Organized into clean, reusable functions

## Future Enhancements

- [ ] Add task categories/priority levels
- [ ] Implement due dates for tasks
- [ ] Add data persistence (file storage)
- [ ] Create a GUI version

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- CodSoft for providing this internship opportunity
- Python community for excellent documentation and resources

---

Developed as part of the CodSoft Python Programming Internship Program.
