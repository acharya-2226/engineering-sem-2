# 🍽️ Restaurant Billing System (C++ Project)

This is a **menu-driven Restaurant Billing System** developed in **C++** using Object-Oriented Programming concepts. It helps restaurant staff manage **orders**, generate **bills**, and store data in a file. Built using classes like `MenuItem`, `Order`, and `Restaurant`, the system demonstrates core OOP principles like encapsulation and modularity.

> 🎓 **Second Semester OOP Project** — Computer Engineering

---

## 🛠️ Features

* ➕ Add new customer orders (multiple items allowed)
* 📝 Edit existing orders
* ❌ Delete an order
* 📋 View all current orders
* 🧾 Generate itemized bill for a specific order
* 📂 Orders saved to `orders.txt` for basic persistence

---

## 🧠 Concepts Used

* **Classes and Objects**
* **Encapsulation**
* **Modular design**
* **File handling** (`ofstream`, file writing)
* **Arrays and Strings**
* **Switch-case and Loops**

---

## 🍔 Menu Items Included

The menu includes 20 different items ranging from momos, burgers, pizzas, beverages, desserts, etc., with corresponding prices.

Example:

```
1. Chicken Momo - Rs.220
2. Veg Momo - Rs.180
...
20. Brownie - Rs.280
```

---

## ▶️ How to Run

### 🫮 Compile

```bash
g++ restaurant_billing.cpp -o restaurant_billing
```

### 🚀 Run

```bash
./restaurant_billing
```

---

## 📂 File Output Format

All orders are stored in `orders.txt` in the following format:

```
CustomerName,TableNo,Item1,Qty1,Item2,Qty2,...,TotalPrice
```

---

## 📋 Sample Menu

```
1. Add Order
2. Edit Order
3. Delete Order
4. View Orders
5. Generate Bill
6. Exit
Enter your choice:
```

---

## 📚 Educational Purpose

This project helps students:

* Apply object-oriented design in real-life systems
* Understand how to model entities (like `Order`, `Item`) using classes
* Practice file handling and user interaction in console apps

---

## 👨‍💻 Author

**Project by:** Siddharth
**Semester:** Second
**Program:** B.E. Computer Engineering

---

## 📜 License

This project is intended for academic and learning purposes. Feel free to use, modify, and enhance it for your coursework or personal projects.
