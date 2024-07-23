# Project Title: Directory-Based File Encryption and Decryption Utility

## Project Description:

This project is a directory-based file encryption and decryption utility written in C++. The utility scans a specified directory and processes all regular files within it, either encrypting or decrypting them based on user input. The project leverages modern C++ features, including the filesystem library for directory traversal and a task-based approach for managing file operations. It incorporates robust error handling to ensure smooth operation even in the presence of filesystem errors.

## Key Features:

- Directory Traversal: Utilizes the C++ filesystem library to recursively traverse directories and identify - - - - regular files.
- Task Management: Implements a task management system to queue and execute encryption or decryption tasks.
- User Input: Prompts the user for a directory path and the desired action (encrypt or decrypt).
- Error Handling: Provides error messages for invalid directory paths and file access issues.
- Modular Design: Separates functionality into distinct classes for process management and task handling, promoting code reusability and maintainability.

## How to Run:

Clone the Repository:
bash
git clone <repo_url>
cd <repo_name>

### Build the Program:

You can use CMake to build the program. Simply run the makefile and then execute the output it generates.

## Project Structure

- main.cpp: The main entry point of the program.
- src/app/processes/ProcessManagement.hpp: Header file for process management.
- src/app/processes/ProcessManagement.cpp: Implementation file for process management.
- src/app/processes/Task.hpp: Header file for task handling.
- src/app/processes/Task.cpp: Implementation file for task handling.
