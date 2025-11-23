                                                                    Personal Expense Tracker
Overview:

-This is a basic, command-line interface application for tracking personal expenses. It allows users to add, view, remove, and calculate the total of their recorded expenses.  


Features:

-Add Expense: Record a new expense with a date, description, and amount.

-View Expenses: Display a numbered list of all recorded expenses.

-Remove Expense: Delete an expense by its index number.

-Total Expenses: Calculate and display the sum of all expenses.


Technologies used:

-Python

-VS Code

-Github

Steps to run:

-Clone the repository.

-Navigate to the project folder.

-Run the program.

Instructions for testing:
-Follow these steps to test the Expense Tracker program manually:
A-)Run the Program
B-)Test Each Feature

Test: Add Expense
-Select option 1
-Enter:
Date (e.g., 01-12-2025)
Description (e.g., Groceries)
Amount (e.g., 450)
-Confirm that the program displays "Expense added successfully"

Test: View Expenses
-Select option 3
-Check that the expense you added appears in the list with:
Correct index number
Accurate date, description, and aMOUNT

Test: Remove Expense
-Select option 2
-Enter the index number shown in the expense list (e.g., 1)
-Ensure the program prints "Expense removed successfully."
-View expenses again to confirm it was removed.

Test: Total Expenses
-Add multiple expenses again
-Select option 4
-Verify the printed total equals the sum of all added amounts

C-) Test Invalid Inputs
-To ensure the program handles errors properly: Invalid Choice
-Enter a non-number or a number outside 1–5
Expect: "Invalid choice. Please try again."


Invalid Expense Index
-Choose option 2 (Remove Expense)
-Enter an index that doesn’t exist (e.g., 10)
Expect: "Invalid expense index."

D-) Exit the Program
1. Select option 5
2. Ensure the program prints "END" and terminates cleanly.


Screenshot of output:




![WhatsApp Image 2025-11-23 at 20 20 47_0b075b7a](https://github.com/user-attachments/assets/1679bf5d-550f-4b81-9db7-7c354002d5e6)

