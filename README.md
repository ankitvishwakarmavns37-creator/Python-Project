# Store Management System 

This is a console-based Store Management System developed in Python.  
It uses file handling with the `pickle` module to manage customers, products, and orders without using any database.

---

## Project Overview

The system allows users to:
- Manage customer records  
- Manage product details  
- Place and track orders  

All data is stored in binary (.bin) files.

---

##  Features

###  Customer Module
- Add Customer  
- View All Customers  
- Delete Customer  

###  Product Module
- Add Product  
- View All Products  
- Update Product Price  

### Order Module
- Place Order  
- View All Orders  
- View Orders by Customer ID  

---

## Data Storage

- `customer.bin` → Customer data (ID, Name, Address, Mobile)  
- `product.bin` → Product data (ID, Name, Price)  
- `order.bin` → Order data (Customer ID, Product ID, Quantity)  

Data is stored using Python's `pickle` module.

---

##  Technologies Used

- Python  
- File Handling  
- Pickle Module  

---

##  How to Run

1. Install Python  
2. Download or clone this repository  
3. Run the file:

```bash
python store.py
```

---

##  Menu Options

1. Add Customer  
2. View All Customers  
3. Delete a Customer  
4. Add Product  
5. View All Products  
6. Update Product  
7. Place an Order  
8. View All Orders  
9. View Orders by Customer ID  
0. Exit  


