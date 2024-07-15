# Database Management System for E-Commerce Platform

This project is an eCommerce platform built using MySQL for the database and Streamlit for the frontend. The platform allows users to browse products, add items to their cart, and make purchases. The backend is designed to handle various eCommerce functionalities, including product management, user management, and order processing.

## Features
- **User authentication**: Users can create an account and log in to access the site's features
- **Admin functionalities**: Admins can create an account and log in to access the site's admin features
- **Product browsing**: Users can browse products by category or search for specific items using keywords
- **Cart management**: Users can add items to their shopping cart, view their cart, and remove items from their cart
- **Checkout**: Users can complete their purchase by entering their shipping and billing information
- **Order history**: Users can view their past orders and track their current order status

## ER model
<img src="ER diagram.svg" alt="ER diagram" width=""/>

## Relational Model
<img src="Relational model.svg" alt="ER diagram" width=""/>

## Instructions
1. Clone the repository:

    ```bash
    git clone https://github.com/notkartikye/mysql-ecommerce-platform.git
    cd mysql-ecommerce-platform
    ```
    
2. Install MySQL for Python by running:

    ```bash
    pip install mysql-connector-python
    ```

3. Import the database using the SQL scripts in the root directory.
4. Install Streamlit, for frontend functionality by running:    
    ``` 
    pip install streamlit
    ```
5. Enter queries using a GUI by running:
    ```bash
    cd UI
    streamlit run main.py
    ```
6. Navigate to http://localhost:8501 on your web browser (or whatever is mentioned in the terminal).
