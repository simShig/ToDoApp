# To-Do List App

This Python project is a To-Do List application that provides a command-line interface (CLI), graphical user interface (GUI), and can be exported as a desktop app and web app.
The application uses a text file as a database to store tasks and their status.

## Features

- **Command-Line Interface (CLI):**
  - Run the application from the command line to manage tasks using text commands.
  - Example commands: `add`, `complete`, `edit`, `show`, etc.

- **Graphical User Interface (GUI):**
  - Launch the GUI version of the application for a user-friendly experience.
  - Easily add, complete, and edit tasks with the click of a button.

- **Export as Desktop App:**
  - The application can be exported as a standalone desktop application for different operating systems.
  - Provides a convenient way to use the To-Do List without the need for a terminal or console.

- **Export as Web App:**
  - Convert the application into a web-based version that can be accessed through a web browser.
  - Users can manage their tasks from any device with internet access.

- **Text File Database:**
  - Tasks are stored in a simple text file acting as a database.
  - Easy to back up and transfer data between different instances of the application.

## Getting Started

### Prerequisites

- Python 3.10
- Additional dependencies listed in `requirements.txt`

### Installation

1. Clone the repository:

        git clone https://github.com/simShig/ToDoApp.git

2. Navigate to the project directory:

        cd ToDoApp
3. Install dependencies:

        pip install -r requirements.txt
4. Run the application:

For CLI:

    python cli.py
For GUI:

    python gui.py
## Usage
CLI Commands:

Use various commands to manage your to-do list.
Example: 
    
    python cli.py 
    add Wash Dishes

GUI:

Launch the GUI application to interact with your to-do list using a graphical interface.
Add, complete, and edit tasks with ease.

## Contributing
Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and submit a pull request.


## Acknowledgments
Thanks to PySimpleGUI for providing a simple and powerful GUI library for Python.
