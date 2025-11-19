# Net Banking Application

## Overview
A secure web-based Net Banking application developed using **ASP.NET Core MVC**, enabling users to perform essential banking operations such as transactions, bill payments, account viewing, and opening FD/RD accounts.

## Features

### User Authentication
- Implemented using **JWT (JSON Web Tokens)**
- Secure login/logout functionality
- User validation using records stored in **SQL Server**

### Banking Operations
- Money transfer and bill payment functionality
- View account balance and recent transactions
- Filter transactions by custom date ranges
- Open **Fixed Deposit (FD)** and **Recurring Deposit (RD)** accounts
- Built-in FD/RD calculator based on:
  - Principal amount
  - Duration (time period)

### Application Interface
- Developed using **HTML, CSS, JavaScript, Bootstrap**
- Includes:
  - Login/Logout pages
  - Home dashboard
  - User profile and transaction views

### Backend & APIs
- REST APIs to fetch:
  - User details
  - Transaction records
- Database operations implemented using **SQL Server**

### Code Quality & Architecture
- Designed using:
  - **Object-Oriented Programming (OOP)**
  - **SOLID principles**
  - Efficient data structures
- Optimized API and backend performance

### Deployment
- Deployed on **Azure DevOps** using a **CI/CD pipeline**
- Automated build and deployment workflow

## Tech Stack
- **ASP.NET Core MVC**
- **SQL Server**
- **JWT Authentication**
- **HTML, CSS, JavaScript, Bootstrap**
- **Azure DevOps (CI/CD)**
