# Stock Market Management System

Stock Market Management System is a Python application that allows users to manage their stock portfolios, buy and sell shares of different companies, and track their wallet balances. This project is built using the CustomTkinter library for the graphical user interface and interacts with a MySQL database for user registration and data storage.

## About Me
> **Name:** Abhijeet kumar
>> **Affiliated with:** srm institute of science and Technology 
>>> **Educational Background:** Bachelor of technology(b-tech)
>>>> **Honors:** computer science and engineering 

## Table of Contents

> [About Me](#about-me)

> [Features](#features)

> [Installation](#installation)

>[Usage](#usage)

> [Database Setup](#database-setup)

> [ER Diagram](#erd)

> [Screenshots](#screenshots)

> [Process Flow Diagram](#process-flow-diagram)

> [Future Scope](#future-scope)

## Features

- User registration with details like full name, PAN card, Aadhar number, phone number, and initial balance.
- User login with phone number and password authentication.
- Display of the user's wallet balance.
- Buying and selling shares of different companies, with stock prices fetched from a database.
- Managing the user's portfolio, displaying the number of shares owned for each company.
- Option to add money to the wallet.
- User-friendly graphical user interface with a dark and light theme.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Abhijeetkumar05/Stock_Market_Management_App.git
   ```

2. Install the required Python libraries:

   ```bash
   pip install -r ./requirements.txt
   ```

3. Database Setup:
   - Create a MySQL database.
   - Import the SQL script `stock_market_db.sql` provided in the repository to set up the database schema.
   - Update the database credentials in the `database_credentials.txt` file with the appropriate information, including the host, user, and password.

4. Run the application:

   ```bash
   python app.py
   ```

## Usage

- Upon launching the application, you can choose to either log in or sign up.
- If you are a new user, click on "Sign-Up" to register with your personal details and an initial balance.
- If you are an existing user, click on "Login" and enter your phone number and password to access your account.
- After logging in, you can view your wallet balance and your stock portfolio.
- You can also buy and sell shares of different companies from the available list.

## Database Setup

To set up the database, follow these steps:

1. Create a MySQL database.

2. Run the SQL script `Create.sql` provided in the repository on your MySQL workbench. This script will create the necessary tables and schema for the application.

3. Update the `database_credentials.txt` file with the correct database credentials, including the host, user, and password. This file is used by the application to connect to the database.

## ERD

<img width="571" alt="erd" src="https://github.com/user-attachments/assets/3800321c-037c-474f-8817-d2718102fc96" />


## Screenshots

### Home Page
#### Dark Theme
<img width="372" alt="Homepage" src="https://github.com/user-attachments/assets/d03b8be3-a27c-4b11-955b-092cff9cdf11" />

#### Light Theme
<img width="375" alt="Homepage_l" src="https://github.com/user-attachments/assets/6b57fa56-1683-44f4-8afb-7a5f81e1b7c7" />


### Login Page
#### Dark Theme
<img width="375" alt="login" src="https://github.com/user-attachments/assets/da4e756b-52a1-4409-9c0a-1474525db8b3" />

#### Light Theme
<img width="376" alt="login_l" src="https://github.com/user-attachments/assets/6e3297e1-7d88-4820-841c-63d135902a08" />


### Sign-Up Page
#### Dark Theme
<img width="368" alt="sign_up" src="https://github.com/user-attachments/assets/03f4ed82-12ae-4b94-a545-5b9dd50f9e39" />

#### Light Theme
<img width="371" alt="sign_up_l" src="https://github.com/user-attachments/assets/66a963f1-f49a-4f82-be6a-8cbfc5ec57ea" />


### Dashboard
#### Dark Theme
<img width="369" alt="dashboard" src="https://github.com/user-attachments/assets/0cb38f0a-c02d-488d-844a-2c9e6693230b" />

#### Light Theme
<img width="370" alt="dashboard_l" src="https://github.com/user-attachments/assets/5defb69e-a9d4-408f-b057-56111dbfb9a6" />


### Orders
#### Dark Theme <br>
<img width="221" alt="order" src="https://github.com/user-attachments/assets/5f2c49d7-f2f7-44df-90ec-c8918084ed2c" />

#### Light Theme <br>
<img width="220" alt="order_l" src="https://github.com/user-attachments/assets/5d50378b-59bb-4907-979e-ba05b3eabb2c" />


## Process Flow Diagram

### Login/Sign-up Workflow
![lswork](https://github.com/user-attachments/assets/39c5b0ef-ee3e-4386-b6fd-2a8453be6c9e)


### Order Workflow
![orderflow](https://github.com/user-attachments/assets/672a3d65-802b-4b69-8c51-da7e4f218113)


## Future Scope

The `StockUp` project provides a foundation for a stock trading and portfolio
management application. While the current version fulfills the initial requirements, there
is significant potential for further development and enhancements. Here are some future
scope possibilities for the project:
>1. **Enhanced User Profiles**:
 - Implement more comprehensive user profiles, including personal information,
investment preferences, and risk tolerance.
 - Provide options for users to link their real brokerage accounts for live trading.
>2. **Real-Time Data Integration**:
 - Integrate with real-time stock market data providers to offer users actual market data.
 - Implement features like live stock quotes, real-time charts, and news feeds.
>3. **Advanced Trading Features**:
 - Add advanced trading options, such as limit orders, stop-loss orders, and trailing stop
orders.
 - Implement technical analysis tools for users to make informed trading decisions.
>4. **Security Enhancements**:
 - Enhance security measures to protect user data and financial information.
 - Implement two-factor authentication and encryption for sensitive data.
>5. **Educational Resources**:
 - Create a section for educational resources, including articles, tutorials, and webinars
on stock trading and investment strategies.
>6. **Gamification and Rewards**:
 - Implement gamification elements to make the app more engaging.
 - Reward users for reaching trading milestones or achieving certain goals.


