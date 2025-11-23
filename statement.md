Problem Statement

Managing daily expenses manually can be time-consuming and error-prone. Many individuals struggle to keep track of how much they spend, leading to poor budgeting and financial planning. A simple, lightweight tool is needed to record expenses quickly and calculate totals without requiring complex software or spreadsheets.




Scope of the Project

The scope of this project includes:

Building a command-line based application that allows users to track expenses in a straightforward manner.

Implementing core expense management functionality, such as adding, removing, viewing, and summarizing expenses.

Providing a clean and intuitive menu-driven interface suitable for beginners.

The project focuses solely on local storage in memory (no file or database integration).

No graphical user interface or advanced reporting features are included in this version.


This project is intended as a learning exercise in Python programming and OOP principles.


Target Users

-This application is designed for:

-Students or beginners learning Python, especially those practicing OOP and CLI applications.

-Individuals who want a simple tool to track expenses during a session without installing additional software.

-Developers looking for a starting point to build more advanced personal finance systems.

-Instructors or educators who want a clear example of class-based design and menu-driven programs.


 High-Level Features

✔ Add Expense

-Users can input the date, description, and amount for each expense.

-Each expense is stored as an object for better data structure.


✔ View Expenses

-Displays all recorded expenses with formatted details.

-Uses indexing for easy identification and management.


✔ Remove Expense

-Deletes an expense by entering its index number.

-Provides validation to prevent invalid deletions.


✔ Total Expenses Calculation

-Computes and displays the sum of all added expenses.

-Useful for quick budget summaries.


✔ Menu-Driven CLI Interface

-Clear text-based navigation system.

-Repeats until the user chooses to exit.



