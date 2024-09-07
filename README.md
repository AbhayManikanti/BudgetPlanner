# Budget and Expense Tracker

## Overview

The Budget and Expense Tracker is a desktop application developed using PyQt5 for managing and visualizing budget and expense data. It allows users to input budget and expense details, view them in tables, and generate visualizations such as pie charts and bar graphs to compare budgeted versus actual expenses.

## Features

- **Two Tabs Interface**: 
  - **Budget**: Manage budget categories and amounts.
  - **Expenses**: Track expenses by category and amount.

- **Data Visualization**:
  - **Pie Chart**: Shows the distribution of budget categories.
  - **Bar Chart**: Compares budgeted amounts to actual expenses.

## Requirements

- **Python**: Ensure you have Python installed on your system.
- **Libraries**: Install the required libraries using the commands below.

## Setup

1. **Create and Activate a Virtual Environment**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
2. **Install Required Libraries:**
  ```
    pip install pyqt5 matplotlib pandas
  ```
3. **Run the Application:
    ```
    python your_script_name.py
    ```
The Application opens a GUI window with two tabs, one for budget and another for expenses. Fill in the values and you will get graphs as seen below:

![image](https://github.com/user-attachments/assets/a98069fc-57a6-4fc6-9d4b-631043725ac7)

![image](https://github.com/user-attachments/assets/3d2148cb-f7b7-41af-9997-303b4d69ffcd)

## Acknowledgments:
- PyQt5 for the GUI framework.
- Matplotlib for data visualization.
- Pandas for data manipulation.

Feel free to modify and use this application as needed. Enjoy tracking your budget and expenses!

