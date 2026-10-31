# 🍽️ Smart Canteen Billing and Order Analyzer

A Python-based command-line canteen billing system that allows users to select food items, enter quantities, calculate bills, apply discounts, and generate a final receipt.

## 📌 Project Overview

This project simulates a simple canteen ordering and billing system. Users can view a numbered menu, select food items, enter quantities, and add multiple items to their order. The program automatically calculates the subtotal, applies discounts based on the order amount, and displays a final receipt.

## ✨ Features

- Displays a numbered food menu with prices.
- Allows users to select items and quantities.
- Validates item numbers and quantities.
- Supports multiple items in a single order.
- Calculates individual item costs and subtotal.
- Automatically applies discounts based on the order amount.
- Generates a final receipt.
- Handles empty orders.

## 🍔 Menu and Prices

| Item No. | Item | Price |
|---|---|---:|
| 1 | Veg Sandwich | ₹60 |
| 2 | Masala Dosa | ₹80 |
| 3 | Chole Rice | ₹90 |
| 4 | Paneer Roll | ₹100 |
| 5 | Tea | ₹20 |

## 💰 Discount Rules

| Order Subtotal | Discount |
|---|---:|
| ₹500 or above | 10% |
| ₹250 – ₹499.99 | 5% |
| Below ₹250 | No discount |

## 🧾 Sample Receipt

```text
========== RECEIPT ==========

Paneer Roll x 2: ₹200.00
Tea x 2:         ₹40.00

Subtotal:        ₹240.00
Discount:        ₹0.00
Final Total:     ₹240.00

Thank you!
```

## 🛠️ Technologies Used

- Python 3
- Command Line Interface (CLI)

## 📚 Python Concepts Used

- Variables and Data Types
- User Input and Output
- Type Conversion
- Conditional Statements (`if`, `elif`, `else`)
- Nested `if` Statements
- `for` and `while` Loops
- `range()`
- `break` and `continue`
- Nested Loops
- Arithmetic and Comparison Operators

## 📂 Project Structure

```text
Smart-Canteen-Billing/
│
├── main.py
└── README.md
```

## ▶️ How to Run

1. Clone this repository:

```bash
git clone YOUR_REPOSITORY_URL
```

2. Open the project folder:

```bash
cd Smart-Canteen-Billing
```

3. Run the Python file:

```bash
python main.py
```

## 📦 Requirements

- Python 3 installed.
- No external libraries or packages required.

## 🎯 Learning Objective

The main objective of this project is to practise Python control flow concepts by building a practical canteen billing system using conditional statements, loops, input validation, and basic calculations.

## 👨‍💻 Author

**Adeeb Hami**

B.Tech CSE (AI/ML) Student

