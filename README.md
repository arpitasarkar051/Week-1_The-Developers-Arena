## Project overview

This project is a simple Python console application that collects a user’s name, age, and favorite hobby, then displays a friendly personalized welcome message.  
The main goal is to practice basic input and output in Python while organizing a small project with a clear file structure.

## Objectives

- Use `input()` to collect user information from the keyboard.  
- Store user responses in variables for later use in the program.  
- Use `print()` (with formatted strings) to display a clear, friendly message.  
- Structure a small project with `personal_intro.py`, `requirements.txt`, and `README.md`.

## Features

- Prompts the user for:
  - Name  
  - Age  
  - Favorite hobby  
- Displays a short introduction message combining all three pieces of information.  
- Runs entirely in the terminal with no external dependencies.

## Project structure

- `personal_intro.py` – Main Python script that implements the personal introduction program.  
- `requirements.txt` – Lists project dependencies.  
- `README.md` – Project documentation, including overview, setup, and learning notes.  
- `screenshots/` – Folder containing screenshots of the program running.

## Setup and installation

### Prerequisites

To run your `personal_intro.py` program in IDLE, you only need Python installed; there is no extra package installation for this project.

## 1. Install Python 

- Go to the official site: https.//www.python.org/downloads and download the latest Python 3 installer for your system.
- Run the installer and make sure to check:
  - “Add python.exe to PATH”  
  - “Install Now” (recommended for beginners, includes IDLE automatically).

After installation, you will have both Python and IDLE on your computer.

## 2. Open IDLE

- On Windows:  
  - Press the Windows key and type “IDLE”.  
  - Click “IDLE (Python 3.x 64-bit)” when it appears.
- On macOS or Linux, IDLE is usually available from your applications menu once Python is installed.[

This opens the Python shell window (it shows something like `>>>`).

## 3. Create or open your script

- In IDLE, go to `File > New File` to create a new script file.
- Paste or type your `personal_intro.py` code into this new window.  
- Save the file:
  - `File > Save` (or press `Ctrl+S` / `Cmd+S`).  
  - Choose a folder and name it `personal_intro.py`.

If you already created `personal_intro.py` before, instead use `File > Open` and select that file.[7][8]

## 4. Run the program in IDLE

- Make sure the script window with `personal_intro.py` is active (on top).  
- Run it using one of these:  
  - Press `F5` on your keyboard.  
  - Or go to `Run > Run Module` in the menu.

A shell window will appear (or reuse the existing one), and you will see prompts like:

- `Enter your name:`  
- `Enter your age:`  
- `Enter your favorite hobby:`  

After you type each answer and press Enter, the program prints your personalized welcome message.


## Code structure explanation

- The script:
  - Uses `input()` three times to read the user’s name, age, and hobby from the terminal.  
  - Stores each response in a separate variable.  
  - Uses `print()` statements and formatted strings to show:
    - A header line.  
    - A sentence combining the collected information.  
    - An additional friendly message.  
- Comments in the code explain what each section does.

## Screenshots

Adding actual screenshots after i run the program.


## How technical requirements are met

- **Use `input()` to get user information**  
  - The program calls `input()` three times to collect name, age, and hobby.  
- **Use variables to store the answers**  
  - The responses from each `input()` call are stored in variables (for example, `name`, `age`, and `hobby`).  
- **Use `print()` to display the welcome message**  
  - The script uses `print()` to display a header and a personalized sentence that includes all the user information.  
- **Additional requirements (examples)**  
  - Includes comments explaining key parts of the script.  
  - Follows a simple, clear file structure suitable for a GitHub repository.

## What was learned

In this project:

- Learned how to interact with users in Python using `input()` to read data from the terminal.  
- Practiced storing values in variables and reusing them to build output messages with `print()` and formatted strings.  
- Gained experience organizing a small Python project with a main script, dependency file, and documentation suitable for version control platforms.
