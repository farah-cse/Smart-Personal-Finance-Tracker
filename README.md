# 💰 **Smart Personal Finance Tracker (Python CLI App)**

## 📌 **Description**
A command-line based Personal Finance Tracker built with Python that allows users to record, manage, and analyze their daily income and expenses. This project
demonstrates core Python concepts, object-oriented programming, file handling, and asynchronous programming by simulating real-world financial tracking and 
reporting.

## ⚙️ **Features**
* Add and manage transactions (income & expenses)
* View all recorded transactions
* Categorize transactions (e.g., Food, Travel, Bills)
* Generate financial reports:
  - Total spending
  - Category-wise analysis
* Save and load data using JSON
* Export transactions to CSV
* Error handling for invalid inputs
* Logging system for tracking app activity
* Async data sync simulation
* Modular and scalable project structure

## 🧠 **Concepts Used**
* **Core Python**
  - Control flow (if, else, loops)
  - Functions, return values
  - Lambda functions
* **Data Structures**
  - Lists, Tuples, Sets, Dictionaries
  - String manipulation and formatting
* **Pythonic Features**
  - List comprehensions & generators
  - map, filter, zip, enumerate
  - *args and **kwargs
  - Mutability vs immutability
* **Object-Oriented Programming**
  - Classes and objects
  - __init__ constructors
  - Instance vs class variables
  - Inheritance and polymorphism
  - Encapsulation and abstraction
  - @dataclass
* **Error Handling**
  - Exception handling (try, except)
  - Custom exceptions
* **File Handling & Serialization**
  - JSON and CSV handling
  - File read/write operations
* **Standard Library**
  - datetime, os, pathlib
  - logging
* **Advanced Python**
  - Async programming (async / await)
  - Basic multithreading concepts
 
# **▶️ How to Run**
## 1. Clone the repository
```
git clone https://github.com/your-username/finance-tracker.git
cd finance-tracker
```
## 2. Create virtual environment
```
python -m venv venv
```
## 3. Activate it
Windows:
```
venv\Scripts\activate
```
Mac/Linux:
```
source venv/bin/activate
```
## 4. Install dependencies
```
pip install -r requirements.txt
```
## 5. Run the app
```
python main.py
```

## **🖥️ Sample Output**

===== Personal Finance Tracker =====
- 1. Add Transaction
- 2. View Transactions
- 3. Generate Report
- 4. Export to CSV
- 5. Sync Data
- 6. Exit

Enter choice: 1
- Enter amount: 250
- Enter category: Food
- Enter description: Dinner
- ✅ Transaction added successfully!

Enter choice: 3
- 📊 Total Spending: 250
- 📂 Category Breakdown:
Food: 250

