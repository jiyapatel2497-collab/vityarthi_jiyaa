# Python Expense Tracker

## Overview
The Python Expense Tracker is a simple command-line application designed to help users manage their personal finances by tracking expenses. Users can add, view, and delete expense records with details such as date, amount, category, and description. The data is saved persistently in a CSV file to allow ongoing tracking over time.

## Features
- Add new expense entries with date, amount, category, and description.
- View all recorded expenses in a clear tabular format.
- Delete expenses by selecting the record number.
- Persistent storage of expense data in a CSV file.
- Simple and intuitive menu-driven interface.

## Technologies Used
- Python 3
- CSV module for data storage and management
- OS module for file handling

## Installation and Running
1. Ensure Python 3 is installed on your system.
2. Download or clone the project repository.
3. Navigate to the project directory.
4. Run the application:
5. Follow the on-screen menu to manage your expenses.

## How to Use
- Choose from the menu options: Add, View, Delete, or Exit.
- When adding, enter the requested expense details.
- View your expense list at any time to see current records.
- Delete expenses by specifying the corresponding entry number.

## Project Structure
- `expense_tracker.py` — Main application script containing all code.
- `expenses.csv` — Data file storing the expense records.

## Future Enhancements
- Add user authentication for multi-user support.
- Provide monthly and category-wise summary reports.
- Integrate graphical UI using Tkinter or web interface.
- Implement data visualization with charts.
- Add export options for reports (PDF, Excel).
