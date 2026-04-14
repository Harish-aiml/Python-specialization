# BudgetTracker 💰

A Python-based budget management system that allows users to track deposits, withdrawals, transfers, and visualize spending across categories.

---

## 📌 Overview

**BudgetTracker** is a simple yet powerful application for managing personal finances. It uses object-oriented programming to organize expenses into categories and provides a visual spending chart.

This project demonstrates:

* Object-Oriented Programming (OOP)
* Data modeling using classes
* String formatting and reporting
* Algorithmic thinking for data visualization

---

## ⚙️ Features

* ➕ Deposit funds into categories
* ➖ Withdraw funds with validation
* 🔄 Transfer money between categories
* 💰 Track category-wise balances
* 📊 Generate a percentage-based spending chart
* 🧾 Clean transaction ledger formatting

---

## 🧠 Tech Stack

* **Language:** Python
* **Concepts:** OOP, Data Structures, String Formatting

---

## 📂 Project Structure

```id="w6z2v1"
budget-tracker-python/
│
├── budget_tracker.py   # Main logic
└── README.md           # Documentation
```

---

## 🚀 Usage

### Example:

```python id="4o9p7a"
food = Category("Food")
entertainment = Category("Entertainment")
business = Category("Business")

food.deposit(1000, "Initial deposit")
food.withdraw(200, "Groceries")

entertainment.deposit(500, "Initial deposit")
entertainment.withdraw(150, "Movies")

business.deposit(1000, "Initial deposit")
business.withdraw(300, "Office supplies")

food.transfer(100, entertainment)

print(food)
print(entertainment)
print(create_spend_chart([food, entertainment, business]))
```

---

## 📝 Sample Output

```id="4x3p6k"
*************Food*************
Initial deposit        1000.00
Groceries              -200.00
Transfer to Entertai   -100.00
Total: 700.00

Percentage spent by category
100|          
 90|          
 80|          
 70|    o     
 60|    o     
 50|    o     
 40| o  o     
 30| o  o  o  
 20| o  o  o  
 10| o  o  o  
  0| o  o  o  
    ----------
     F  E  B  
     o  n  u  
     o  t  s  
     d  e  i  
        r  n  
        t  e  
           s  
           s  
```

---

## 💡 Future Improvements

* Add CLI interface for user interaction
* Store transactions using JSON or database
* Build a web API using FastAPI
* Add data visualization using matplotlib
* Create a GUI version

---

## 🧑‍💻 Author

**Harish**
B.E CSE (AI & ML)
Aspiring AI Engineer & Backend Developer

---

## 📜 License

This project is open-source and available under the MIT License.
