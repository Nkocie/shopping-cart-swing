# Shopping Cart Java GUI Application

## Overview

This is a Java Swing-based Shopping Cart application that simulates a small e-commerce store. The application provides a product catalog, shopping cart functionality, checkout summary, and features such as VAT calculation, discounts, and shipping options.

The GUI is built with Java Swing and demonstrates event handling, layout management, and state persistence.

---

## Features

* **Product Catalog**: View and select products to add to the cart.
* **Shopping Cart**: Add, remove, and update item quantities.
* **Discounts & VAT**: Automatic calculation of discounts (if applicable) and VAT.
* **Shipping Options**: Choose between different shipping methods.
* **Save/Load Cart**: Persist cart state between sessions.
* **Checkout Summary**: Displays total price, taxes, and discounts.

---

## Requirements

* Java **JDK 8** or higher
* Any standard IDE (IntelliJ IDEA, Eclipse, NetBeans) or command line tools

---

## Installation & Running

1. **Clone or Download** this repository.
2. Save the source file as `ShoppingCartApp.java`.
3. Open a terminal in the project directory.
4. Compile the program:

   ```bash
   javac ShoppingCartApp.java
   ```
5. Run the program:

   ```bash
   java ShoppingCartApp
   ```

---

## Usage

1. **Browse Products**: Select products from the catalog.
2. **Add to Cart**: Click "Add to Cart" for selected items.
3. **View Cart**: Check cart contents in the cart panel.
4. **Update/Remove Items**: Modify quantities or remove products.
5. **Apply Discounts/Shipping**: Choose discounts or shipping preferences.
6. **Checkout**: Review final summary and complete the purchase.

---

## File Structure

```
ShoppingCartApp.java   # Main application with GUI and logic
README.md             # This documentation file
```

---

## Future Enhancements

* Integration with a **database** (e.g., MySQL, PostgreSQL) for persistent products and orders.
* Add **user authentication** (login/register).
* Implement **search and filter** options in the catalog.
* Support for **multiple currencies**.

---

## License

This project is provided as-is for educational purposes. You are free to use and modify it.
