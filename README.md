# Expense Tracker

Expense Tracker is a simple Python command-line application that allows you to keep track of your expenses. You can enter your budget, record your expenses, and see a summary of your spending by category and remaining budget. This README will guide you on how to use the `expense_tracker.py` and `expense.py` files in your project.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Getting Started](#getting-started)

## Prerequisites

Before using the Expense Tracker, make sure you have the following installed:

- Python 3

## Usage

1. Clone the project repository to your local machine:

   ```bash
   git clone https://github.com/your-username/expense-tracker.git
   ```

2. Change into the project directory:

   ```bash
   cd expense-tracker
   ```

3. Run the `expense_tracker.py` script to start tracking your expenses:

   ```bash
   python expense_tracker.py
   ```

4. Follow the on-screen prompts to enter your budget and record your expenses.

## Getting Started

The `expense_tracker.py` script is the main application that interacts with the user and manages expenses. It imports the `Expense` class from `expense.py`, which represents individual expenses.

Here is a brief overview of the key functions and their responsibilities in `expense_tracker.py`:

- `main()`: The main entry point of the application. It initializes the budget, records expenses, and summarizes them.

- `get_user_budget()`: Prompts the user to input their budget and validates it.

- `get_user_expense()`: Prompts the user to input expense details, including name, amount, and category.

- `save_expense_to_file()`: Writes the user's expense to a CSV file for record-keeping.

- `summarize_expenses()`: Reads the expense data from the file, calculates and displays a summary of expenses, and provides information on the remaining budget.

- `green()` and `red()`: Helper functions to format text in green and red for better visibility.

Make sure to create an `expense.csv` file in the project directory to store the recorded expenses.

The `expense.py` file defines the `Expense` class, which stores information about individual expenses, including the name, category, and amount.
