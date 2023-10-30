# Basic Banking Website

This is a simple banking website project that utilizes PHP, CSS, Bootstrap, SQL, and XAMPP to demonstrate basic functionalities of a banking system. Users can create accounts, view account details, perform transactions, and view transaction history.

## Features

- **Homepage** - Provides information about the website and an "About Me" section.

- **Account Management** - Users can view their account details, including the account balance.

- **Fund Transfer** - Users can transfer money between their accounts or to other users.

- **Transaction History** - Users can view a history of their transactions.

## Technologies Used

- **Frontend:**
  - PHP
  - CSS
  - Bootstrap

- **Backend:**
  - PHP for server-side scripting
  - XAMPP for the web server and database (MySQL)

## Getting Started

1. Clone this repository to your local machine or set up your own XAMPP environment.

2. Import the database schema (provided in `database.sql`) into your MySQL database.

3. Configure the database connection in your PHP files (`config.php`) to match your local setup.

4. Place the project files in your XAMPP htdocs directory.

5. Start your XAMPP Apache and MySQL services.

6. Open the website in your browser by navigating to `http://localhost/swiss_bank/index.php`.

## Usage

1. Navigate to the homepage to learn more about the website and its purpose.

2. Create an account, and log in with your credentials.

3. Explore your account details, including the account balance.

4. Visit the "Transaction" page to transfer money to other accounts.

5. Check the "Transaction History" page to view your recent transactions.

## Database Schema

The project includes a MySQL database with the following tables:

- `users` - Stores user information, including usernames and passwords.

- `accounts` - Stores account information, including account balances.

- `transactions` - Records all money transactions between accounts.

## HomePage
![swissbank](https://github.com/ankit-akash/bankingwebsite/assets/75488501/c23f9117-7f33-474c-ae22-8228690e54ec)
