# Expense-Tracker

This program is like a digital wallet where you can add expenses, see a list of what you spent, check the total amount spent, and filter expenses by category. It's a straightforward command-line tool with a menu-driven interface. Just type in your choice, and it does the math and organization for you. If you're done, there's an exit option to gracefully leave the digital expense world.

# Detailed Explanation of program:

# Functions:

total_expenses(expenses):

Input: expenses (a list of dictionaries, each representing an expense with 'amount' and 'category' keys)
Output: Total sum of all expenses
This function uses the sum function along with map to sum up the 'amount' values for all expenses.
filter_expenses_by_category(expenses, category):

Input: expenses (list of expenses), category (a string representing the category to filter by)
Output: Filtered list of expenses for the specified category
This function uses the filter function to filter expenses based on the specified category.
main():

This is the main function that handles the user interface and overall flow of the program.

Main Program:
Expense List (expenses):

It starts with an empty list, which will store individual expense entries as dictionaries.
Menu Options:

The program displays a menu with five options:
Add an expense: Allows the user to input an amount and category to add a new expense to the list.
List all expenses: Prints all expenses in the list.
Show total expenses: Displays the total sum of all expenses.
Filter expenses by category: Asks the user to input a category and then displays expenses only for that category.
Exit: Exits the program.

User Input Handling:
The program uses a while True loop to keep the user in the menu until they choose to exit.

Function Calls:
Depending on the user's choice, the program calls the corresponding functions:
Add an expense: Calls add_expense (which seems to be missing in your provided code).
List all expenses: Calls print_expenses.
Show total expenses: Calls total_expenses.
Filter expenses by category: Calls filter_expenses_by_category.
Exiting the Program:

If the user chooses to exit (choice == '5'), the program prints a message and breaks out of the loop, ending the execution.
Improvements Needed:
The add_expense and print_expenses functions are referenced but not provided in the code. These functions need to be implemented for the program to work correctly.

Ensure that the add_expense function appends new expense entries to the expenses list.

The overall structure seems to be designed for a modular approach, but some functions are missing. You may need to implement those functions to make the program fully functional.





