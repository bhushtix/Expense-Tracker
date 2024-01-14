# Expense-Tracker

This program is like a digital wallet where you can add expenses, see a list of what you spent, check the total amount spent, and filter expenses by category. It's a straightforward command-line tool with a menu-driven interface. Just type in your choice, and it does the math and organization for you. If you're done, there's an exit option to gracefully leave the digital expense world.

# Detailed Explanation of program:

No worries! If copying the formatted text is challenging, I can provide you with a simplified version without bullet points and numbers. Here it is:

**Functions:**

- *total_expenses(expenses):*
  - Input: `expenses` (list of dictionaries with 'amount' and 'category' keys)
  - Output: Total sum of all expenses
  - Uses `sum` and `map` functions to calculate the total expense amount.

- *filter_expenses_by_category(expenses, category):*
  - Input: `expenses` (list of expenses), `category` (string to filter by)
  - Output: Filtered list of expenses for the specified category
  - Uses the `filter` function to filter expenses based on the category.

- *main():*
  - The main function handling the user interface and program flow.

**Main Program:**

- *Expense List (`expenses`):*
  - An empty list to store individual expense entries as dictionaries.

- *Menu Options:*
  - Add an expense: Input amount and category to add a new expense.
  - List all expenses: Display all expenses in the list.
  - Show total expenses: Display the total sum of all expenses.
  - Filter expenses by category: Input a category to display expenses only for that category.
  - Exit: Terminate the program.

- *User Input Handling:*
  - Uses a `while True` loop to keep the user in the menu until they choose to exit.

- *Function Calls:*
  - Depending on the user's choice, calls corresponding functions:
    - Add an expense: Calls `add_expense` (missing in your provided code).
    - List all expenses: Calls `print_expenses`.
    - Show total expenses: Calls `total_expenses`.
    - Filter expenses by category: Calls `filter_expenses_by_category`.

- *Exiting the Program:*
  - If the user chooses to exit (`choice == '5'`), prints a message and ends the program.

- *Improvements Needed:*
  - `add_expense` and `print_expenses` functions are referenced but not provided in the code. Implement these functions for the program to work.
  - Ensure `add_expense` appends new expenses to the `expenses` list.
  - Some functions are missing. Implement them for the program to be fully functional.





