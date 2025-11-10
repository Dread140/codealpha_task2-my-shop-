MyShop – Flask Laptop Store

A simple online laptop store built with Flask and SQLite. Users can browse products, view details, add items to a cart, and place orders.

Features
User signup, login, and logout
Browse laptops and accessories
Add products to a cart and checkout
Amazon-style product layout using Bootstrap
SQLite database automatically created and seeded

Technologies
Python 3
Flask
SQLite
Jinja2 templates
HTML, CSS, Bootstrap

How to Run
Open terminal and go to project folder:
cd codealpha_task_01-main/codealpha_task_01-main
Install Flask (if not installed):
pip install flask
Run the app:
python app.py

Adding Products
Open app.py
Go to init_db()
Add new products in the list with:
("Product Name", price, "Description")
Restart the app
Notes
Product images are in static/images/
Cart and login info are saved in session
Database is database.db
