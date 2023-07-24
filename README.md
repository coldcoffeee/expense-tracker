# Expense Tracker Web Application

Welcome to Expense Tracker, a web application that helps you keep track of your expenses in a convenient and user-friendly way. This project is built using ExpressJS for handling requests and Mongoose for data storage and retrieval on the backend. The frontend is designed with simple pre-written HTML files that are dynamically modified using JavaScript.

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Modules](#modules)
  - [Signup Page](#signup-page)
  - [Login Page](#login-page)
  - [Expenses Page](#expenses-page)
  - [Forgot Password](#forgot-password)
- [Installation and Usage](#installation-and-usage)
- [Support and Feedback](#support-and-feedback)

## Introduction

Expense Tracker is a powerful tool that allows you to manage your expenses efficiently. Whether you want to track your daily spending or monitor your budget, our application has got you covered. It provides a seamless user experience with a user-friendly interface and essential features to help you stay on top of your finances.

## Technologies Used

The following technologies were used in building the Expense Tracker web application:

- ExpressJS: A fast and minimalist web framework for Node.js, used for handling server-side requests and routing.
- Mongoose: An elegant MongoDB object modeling tool, used for data modeling and interactions with the MongoDB database.
- HTML: The standard markup language for creating web pages and user interfaces.
- JavaScript: The programming language used to add interactivity and dynamic elements to the frontend.
- Razorpay: A payment gateway integration used for implementing premium features and payments.
- Brevo API (formerly Sendinblue): An email service used for the forgot password feature and email communication.

## Features

- User-friendly interface for easy navigation and use.
- Secure authentication with email and password for login and signup.
- Persistent data storage using MongoDB to ensure your data is always accessible.
- Responsive design that adapts to various screen sizes for a seamless experience across devices.
- Leaderboards dashboard showcasing the top 10 users based on total expenses.
- Integration with Razorpay to enable premium features and unlock additional functionalities.
- Export your expenses in JSON format with the click of a button for easy record-keeping.
- Forgot password feature using the Brevo API (formerly Sendinblue) for a smooth password recovery process.

## Modules

### Signup Page

The Signup page allows new users to create an account by providing their name, email, and password. After successful signup, users are redirected to the Login page to access their Expense Tracker account.

![Signup Page](/path/to/signup-screenshot.png) <!-- Insert screenshot of the signup page -->

### Login Page

The Login page requests users to enter their registered email and password for authentication. Upon successful login, users gain access to their personalized Expenses Dashboard.

![Login Page](/path/to/login-screenshot.png) <!-- Insert screenshot of the login page -->

### Expenses Page

The Expenses page is the heart of the Expense Tracker application. It is divided into two main sections:

#### Expense Entry Form

On the left side, there is a form where users can add new expenses by providing relevant details such as the expense name, amount, and date.

#### Expenses Table

On the right side, a table displays the added expenses in a paginated manner, with five records per page. Users can navigate through the pages using buttons. Additionally, users can delete individual expenses from the table.

Header:
- Buy Premium Button: Allows users to unlock premium features using the Razorpay integration.
- Download Button: Appears atop the table, enabling users to download all their expenses in JSON format for easy export and analysis.

![Expenses Page](/path/to/expenses-screenshot.png) <!-- Insert screenshot of the expenses page -->

### Forgot Password

The application provides a Forgot Password feature to assist users in recovering their accounts. This functionality is implemented using the Brevo API (formerly Sendinblue) to send password recovery instructions to the user's registered email address.

## Installation and Usage

To run Expense Tracker locally, follow these steps:

1. Clone this repository: `git clone https://github.com/coldcoffeee/expense-tracker.git`
2. Install the necessary dependencies: `npm install`
3. Set up MongoDB and configure the database connection in `config.js`.
4. Run the application: `npm start`
5. Access the application in your web browser at `http://localhost:3000`

## Support and Feedback

If you encounter any issues while using Expense Tracker or have suggestions for improvement, please feel free to open an issue on the GitHub repository. We appreciate your feedback and are here to assist you.

Happy expense tracking!
