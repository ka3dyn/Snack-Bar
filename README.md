SnackBar Vending Machine
A Java-based graphical simulation of a vending machine system. This project demonstrates GUI components using Swing, object-oriented programming with classes like SnackBar, VendingMachine, and Vendor, and basic authentication for service operations.

Project Structure
SnackBar.java: The main application window. It creates and manages multiple vending machines and handles service login.

VendingMachine.java: Represents an individual vending machine with interactive buttons to insert coins and make purchases.

Vendor.java: Handles the core logic of item sales, stock management, change calculation, and sales tracking.

Features
Three different vending machines: Coffee, Quiz Answers, and Python.

Each machine has its own branding color, price, and stock.

Users can insert coins (5¢, 10¢, 25¢) and press "Buy" to attempt a purchase.

Successful transactions display a confirmation and dispense the item.

Failed transactions return the inserted coins.

A password-protected service panel allows authorized personnel to reload machines and view total sales.

Service Login
To access the service functionality:

Enter the password: password

Upon successful login:

All vending machines are restocked.

Total sales revenue is displayed in a message dialog.

How to Run
Ensure you have Java installed (Java 8 or higher).

Sample UI Behavior
Insert coins using buttons on the vending machines.

Click "Buy" to purchase.

If insufficient funds are inserted or the machine is out of stock, an appropriate message will appear.

Use the password field at the bottom to access service features.
