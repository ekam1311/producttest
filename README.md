# 🛒 Product Management System (Python)

A simple command-line based product management system built using Python.
This program helps you keep track of products, their prices, profits, and payment status using CSV files.

---

## 🚀 Features

* ✅ Add new products with price and profit
* 📋 View all unpaid products
* 💰 View paid products separately
* 🔄 Mark products as paid (moves them to another file)
* 📊 Automatically calculates total price and profit

---

## 🗂️ Files Used

* `products.csv` → Stores unpaid products
* `paid_products.csv` → Stores paid products
* `product management.py` → Main Python program

---

## ⚙️ How It Works

When you run the program, you’ll see a menu:

```
=== Product Manager ===
1. Add Product
2. View Products
3. View Paid Products
4. Mark Paid Products
5. Exit
```

### 🔹 Options Explained

* **Add Product**
  Enter product name, price, and margin (profit = margin)

* **View Products**
  Displays all unpaid products with total price & profit

* **View Paid Products**
  Displays products that have been marked as paid

* **Mark Paid Products**
  You will be asked:

  ```
  Is 'Product Name' paid? (y/n)
  ```

  * `y` → Moves to paid file
  * `n` → Stays in unpaid file

* **Exit**
  Closes the program

---

## 🧠 Concepts Used

* File Handling (`csv`, `os`)
* Functions
* Lists & Dictionaries
* User Input Handling
* Basic Data Management

---

## ▶️ How to Run

1. Make sure Python is installed
2. Download or clone this repository
3. Open terminal in project folder
4. Run:

```
python "product management.py"
```

---

## 💡 Future Improvements

* Add a GUI (Tkinter or PyQt)
* Edit/Delete products
* Search functionality
* Better error handling
* Data visualization (graphs)

---

## 👨‍💻 Author

Made by **Ekam
