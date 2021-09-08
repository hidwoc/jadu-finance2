# Jadu Finance

# Project Description

V2 of jadu-finances. **Jadu Finance** is a fullstack application that tracks the finances of my small business *Jadu Banchan*. 

The login page will be the landing page of the application. Once logged in, users will be able to READ all information. Only admin users will have access to ADD, EDIT, and DELETE functions.

The summary page will display a summary of *Jadu Banchan's* sales, expenses and net profit for the selected batch, as well as total sales/expenses over time in the form of a combo (bar and line) chart. 

The sales page will display the current batch's sales divided into categories and an admin user is able to ADD, EDIT, and DELETE sales entries. The expenses page will display the selected batch's expenses divided into categories and an admin user is able to ADD, EDIT, and DELETE expenses.

# Techstack

MongoDB, Express, React.js, Node.js (MERN)

# MVP

## Backend

## Frontend

- Render sales and expense entries by selected batch
- Display entries as a:
  - Table
  - Donut Chart


# Component Architecture

```structure

src
|__ assets/
|__ components/
    |__ Nav/
    |__ Table/
    |__ Calculation/
    |__ BatchMenu/
|__ Layout/
|__ screens/
    |__ Login/
    |__ Summary/
    |__ Expenses/
    |__ Sales/
    |__ AddExpense/
    |__ AddSale/
    |__ EditExpense/
    |__ EditSale/
|__ services/
|__ App.css
|__ App.jsx

```

