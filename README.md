# Bolt-Sports-Shop

**Project Overview**

Bolt Sports Shop is an eCommerce website developed to facilitate online shopping for sports products. It features a user-friendly interface and provides functionalities such as user authentication, product browsing, a shopping cart, and order management.

**Technologies Used**

Front-End: HTML, CSS, Bootstrap, JavaScript
Back-End: PHP
Database: MySQL

**Features**

User Registration and Login: Allows users to create an account and log in to access personalized features.
Product Catalog: Display a list of sports products with options to filter and search.
Shopping Cart: Users can add items to their cart, view the cart, and proceed to checkout.
Order Management: Allows users to view order history and manage ongoing orders.
Responsive Design: Ensures usability across various devices and screen sizes.
Installation Instructions
Clone the repository to your local machine:

git clone <repository-url>
Navigate to the project directory:

cd bolt-sports-shop
Set up the database:

Import the database.sql file in your MySQL setup.
Configure database settings in the config.php file.
Start the development server:

For a local PHP server, you can run:

php -S localhost:8000
Open your browser and go to:

http://localhost:8000
Usage
Home Page: Browse products, use search and filter options.
Register/Login: Access account features like order history and profile management.
Add to Cart: Select products and add them to the cart.
Checkout: Review the cart and complete the purchase.

**Project Structure**

index.php - Main entry point of the website.
/css/ - Contains custom CSS and Bootstrap for styling.
/js/ - JavaScript files for interactivity and AJAX requests.
/php/ - PHP scripts for handling server-side operations.
/config.php - Database configuration file.

**Database Structure**

The MySQL database consists of the following tables:

Users - Stores user details.
Products - Contains product information.
Orders - Records order details and status.
Cart - Manages cart items per user session.
Contributing
Fork the repository.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a pull request.

**License**

This project is licensed under the MIT License. See LICENSE file for details
