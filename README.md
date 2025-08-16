# 🍞 Bakery Management System

A simple **command-line based Bakery Management System** implemented in Python.  
This program allows users to manage bakery items, display inventory, and place customer orders.  

---

## 🚀 Features

- **Add Items**: Add new bakery items with name, price, and quantity.  
- **Display Inventory**: View all available bakery items in a neatly formatted list.  
- **Place Orders**: Select an item and purchase a specific quantity.  
  - Updates inventory automatically.  
  - Shows total cost of the order.  
- **Exit**: Quit the system when done.  

---

## 🛠️ Code Structure

### `BakeryItem` class
Represents a bakery item.  
- `name`: Name of the item  
- `price`: Price per unit  
- `quantity`: Available quantity  
- `__str__`: Returns a formatted string for displaying the item.  

### `BakeryManagement` class
Handles the bakery operations.  
- `add_item(name, price, quantity)`: Adds a new item to inventory.  
- `display_inventory()`: Shows the current inventory.  
- `place_order(item_index, order_quantity)`: Places an order and updates inventory.  

### `main()` function
Provides the **menu-driven interface** for users.  

---

## 📖 How to Run

1. Clone or download this repository.  
2. Save the code as `bakery.py`.  
3. Run the program:  

```bash
python bakery.py
