
# Iflexpay-website


## Overview

This web application is designed to streamline the process of offering iPhones on lease to customers. It provides a user-friendly interface for customers to register, view their status, calculate installment plans, and ultimately purchase an iPhone on lease.

## Project Tasks

### Task 1: Customer Table

A Customer table has been constructed to store essential details:

**Customer Table Structure:**

| Field           | Data Type        |
|-----------------|------------------|
| Name            | Varchar (50)     |
| Id [primary key]| Integer          |
| Password        | Varchar (50)     |
| Gender          | Varchar (100)    |
| City            | Varchar (100)    |
| Email           | Varchar (100)    |
| Salary          | Integer          |
| Contact number  | Integer          |

### Task 2: iPhone Information and iPhone Lease Tables

Two tables, iPhone Information and iPhone Lease, are created to store iPhone details and installment plans:

**iPhone Information Table Structure:**

| Field               | Data Type        |
|---------------------|------------------|
| iPhone Name         | Varchar (50)     |
| iPhone Model Number | Integer [primary key]|
| Total Amount        | Integer          |
| Down Payment        | Integer          |

**iPhone Lease Table Structure:**

| Field       | Data Type        |
|-------------|------------------|
| LeaseId     | Integer [primary key]|
| ModelNumber | Integer          |
| Months6     | Integer          |
| Months12    | Integer          |
| Months18    | Integer          |

### Task 3: iPhone Installment Calculation

Customers can calculate iPhone installment plans using a separate interface. The formula is as follows:

- For 6 months: 25% amount to be leased
- For 12 months: 45% amount to be leased
- For 18 months: 65% amount to be leased

### Task 4: Purchase Form

A user-friendly form is provided for customers to input their details and preferences:

- Name
- iPhone Name
- iPhone Model Number
- Address
- Selected Installment Plan (6, 12, or 18 months)
- Payment Option (Cash on Delivery)

## How to Run the Application

1. Clone the repository to your local machine.
2. Set up a relational database and execute the SQL scripts in the `database_scripts` folder to create the necessary tables.
3. Configure the database connection in the application.
4. Deploy the application on a web server.

## Contributors

-Nadia Urooj



Feel free to contact us for any inquiries or support.

nidiaurooj789@gmail.com
