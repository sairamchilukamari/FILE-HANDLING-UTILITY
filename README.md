# FILE-HANDLING-UTILITY

COMPANY: CODETECH IT SOLUTIONS

NAME:   CHILUKAMARI SAIRAM

INTERN ID: CT04DA853

DOMAIN: JAVA PROGRAMMING

BATCH DURATION: April15th, 2025 to May 15th, 2025.  

MENTOR NAME: NEELA SANTHOSH KUMAR

This project is a console-based Java application designed to demonstrate the fundamentals of file handling operations, including reading from, writing to, and modifying text files. It provides an interactive interface where users can choose between multiple file operations, making it an excellent starting point for beginners who are learning how to work with files in Java.

The application supports three key functionalities:

Reading a File – Users can input the name of a file they want to read. The program then opens the file and displays its contents in the console. This feature is particularly useful for inspecting existing files without needing an external text editor.

Writing to a File – This function allows users to enter new content, which the program writes to a specified file. If the file doesn’t already exist, it will be created automatically. If the file exists, its previous content will be overwritten. This demonstrates how file output streams work in Java.

Modifying (Appending to) a File – Unlike the write operation, the modify feature appends new content to the end of the existing file without deleting its current content. Each new input is added on a new line, maintaining readability and preserving the file's history.

Tools and Technologies Used
The project utilizes several of Java’s core file handling classes:

BufferedReader and FileReader are used for reading file content efficiently.

BufferedWriter and FileWriter are employed for writing or appending content to files.

Scanner is used to capture user input, allowing the program to operate interactively via the console.

These classes are part of Java’s java.io package, which provides robust support for reading and writing character data, handling exceptions, and managing file streams effectively.

Program Workflow
Upon execution, the user is prompted to enter the name of the file they wish to interact with (including the file extension, e.g., notes.txt). The program then asks the user to select an operation: Read, Write, or Modify. Based on the user's input, the corresponding file operation is performed.

For example, if the user chooses to read a file, the program attempts to locate the file and display its content. If the file does not exist, the user receives an appropriate error message. Similarly, during writing or modifying operations, the user is prompted to enter the content they want to write or append. After the operation, confirmation is displayed to notify the user of the successful action or any issues encountered.

Error Handling
The project includes basic yet effective error handling to manage exceptions such as:

FileNotFoundException: Triggered when attempting to read a non-existent file.

IOException: Covers a range of I/O errors, such as problems during reading or writing processes.

SecurityException: Alerts the user if the program lacks permission to access or modify a file.

This focus on error management not only improves the program’s robustness but also helps beginners understand the importance of handling exceptions when working with external resources like files.

Educational Value
One of the most important aspects of this project is its educational value. By working through this application, new Java programmers gain hands-on experience with essential concepts such as file streams, buffered reading and writing, user input handling, and exception management. These are foundational skills for more advanced topics such as file parsing, data processing, and application development.

Overall, the application is a practical and educational tool for those beginning their journey in Java programming, laying a strong foundation for more advanced file handling techniques or integration into larger projects.

output:

![Image](https://github.com/user-attachments/assets/240ee9c6-ce93-4e8a-98db-23cf308a3a26)
