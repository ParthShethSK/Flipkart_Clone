# Flipkart Clone

Welcome to the Flipkart Clone project repository! This is a web application that replicates the functionality of the popular e-commerce platform Flipkart.
![image](https://github.com/ParthShethSK/Flipkart_Clone/assets/75533289/17eea4b2-5a17-48c4-aa41-1813aed67c7d)


## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This project is a web-based e-commerce platform, similar to Flipkart, where users can browse and purchase products online. It includes essential features such as user authentication, product listings, categories, a shopping cart, and more.

## Features

- User registration and authentication.
- Product listings with detailed descriptions.
- Product categories for easy navigation.
- Shopping cart to add and manage products.
- Order placement and tracking.
- User profile management.
- Wishlist to save desired products.
- Search functionality to find products quickly.

## Prerequisites

Before you get started, make sure you have the following requirements:

- Web server (e.g., Apache).
- PHP installed.
- MySQL database.
- A code editor for development.

## Getting Started

1. Clone the repository to your web server's directory.
   ```bash
   git clone https://github.com/ParthShethSK/Flipkart_Clone.git

2. Import the provided SQL database (flipkart_clone.sql) into your MySQL database.
3. Update the database connection details in DBController.php:
   ```bash
   protected $host = 'localhost';
   protected $user = 'your_db_user';
   protected $password = 'your_db_password';
   protected $database = 'your_db_name';
4. Start your web server and ensure it's running.
5. Open the project in your web browser (e.g., http://localhost/Flipkart_Clone/index.php).

## Usage

1. Register or log in with your credentials.
2. Browse through categories, add products to your cart, and manage your cart.
3. Place orders and view your order history.
4. Explore your profile and update personal information.
5. Save products to your wishlist for later.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository to your own GitHub account.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add feature'`.
4. Push to your branch: `git push origin feature-name`.
5. Create a new Pull Request on GitHub.

You can also report issues or request new features through the issue tracker.

## License

This project is licensed under the Apache License 2.0. See the LICENSE file for details.

**Note:** This project is intended for demonstration and educational purposes, showcasing frontend and backend development for a work management application. For production use, further security and functionality considerations are required.

