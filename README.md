# Personal Finance Management

This project is a personal finance management application built using Python and MongoDB. It allows users to track their expenses by adding, deleting, and filtering expenses based on dates and categories, with enhanced scalability for larger datasets.

## Features
- *Add, delete, and view expenses*: Manage your expenses easily by adding or deleting entries.
- *Search expenses by date range*: Filter expenses based on a specific date range.
- *Filter expenses by category*: View expenses grouped by categories such as Food, Transport, etc.
- *Calculate total expenses*: Quickly calculate the total expenses within a specified date range.

## Dependencies
The following dependencies are required to run the application:
- Python 3.x
- MongoDB
- PyQt5
- bson
- pymongo

## Installation

1. Clone the repository to your local machine:
    bash
    git clone https://github.com/VishrutiGurav/Python-World.git
    

2. Install the required dependencies:
    bash
    pip install PyQt5 pymongo bson
    

3. Ensure that MongoDB is running locally on:
    
    mongodb://127.0.0.1:27017/
    

## Usage

To launch the application, run the gui.py file:
bash
python gui.py


### Application Functionality:
- *Add Expense*: Enter the expense name, amount, and category, then click "Add Expense" to save it.
- *Delete Expense*: Select an expense from the list and click "Delete Expense" to remove it.
- *Search by Dates*: Click "Search by Dates" to select a date range and view filtered expenses.
- *View All Expenses*: Click "Show All Expenses" to display all recorded expenses.

## Database Structure

The application uses MongoDB to store expense data in a scalable way. Each document in the collection includes the following fields:
- expense: Name of the expense
- amount: Amount in Rs
- category: Category of the expense (e.g., Food, Transport, etc.)
- date: Date when the expense was made (stored as a date object)

## Issues
- The file background.jpg is present in the repository but is not utilized in the application.
