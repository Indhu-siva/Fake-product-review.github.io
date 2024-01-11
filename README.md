# Fake Product Review Monitoring System

This project is a simple fake product review monitoring system created for educational purposes. It allows users to submit reviews for products and view existing reviews.

## Features

- Display existing product reviews.
- Allow users to submit new reviews.
- Basic form validation (front-end).

## Database Structure

Assuming you have a MySQL database named `fake_review_system`, create a table named `reviews` with the following structure:

sql:
CREATE TABLE reviews (
    id INT AUTO_INCREMENT PRIMARY KEY,
    product_name VARCHAR(255) NOT NULL,
    reviewer_name VARCHAR(100) NOT NULL,
    review_text TEXT NOT NULL,
    rating INT NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

## Getting Started:
## Prerequisites:
PHP installed on your server.
MySQL server running.
Replace "username" and "password" in the database connection strings with your MySQL username and password.


## Installation:
Clone the repository:
git clone https://github.com/Indhu-siva/Fake-product-review-.github.io


## Change into the project directory:
cd Fake-product-review-github.io
Configure your database connection in index.php and submit_review.php.

## Usage:
Open index.php in your browser.
View existing reviews.
Submit a new review using the form.
