# Row Level Security 

## Project Overview 

This project demonstrates how Row-Level Security (RLS) can be implemented in Microsoft Power BI to control access to business data based on a user’s assigned state or managerial responsibility.

The project was built around a sales reporting scenario in which different managers should not have unrestricted access to the entire company’s sales data. Instead, each manager should only be able to view the records relevant to the state they are responsible for.

The main objective was to create a Power BI model that allows management to analyze sales performance while ensuring that sensitive sales information is only visible to authorized users.

The project includes sales data, a state mapping structure, a users table, and multiple security roles. Both static and dynamic RLS concepts were explored to demonstrate different approaches to restricting data access.

## Business Problem

In a business with sales operations across multiple states, giving every manager access to the complete sales dataset can create unnecessary exposure to information that is outside their responsibility.

For example, a manager responsible for Abuja should be able to analyze Abuja sales without automatically having access to sales information belonging to Lagos, Rivers, or Anambra.

Without an appropriate security layer, a Power BI report could provide useful business insights while still exposing information to users who should not have access to it.

### The project therefore addresses the following business need:

* How can a business provide managers with useful sales reports while ensuring that each manager can only access the sales data they are authorized to see?
* Explain the difference between static RLS and dynamic RLS
* Explain why USERPRINCIPLE() is useful for dynamic RLS
* What would happen if a user's email is missing from the User's table?
* Challenge: Modify the Users table so one manager can access two States. Build the appropriate model and RLS rule.
* How can sales data be restricted according to a manager’s assigned state?
* How can Power BI prevent users from viewing sales records outside their area of responsibility?
* How can different managers be assigned different levels of data access?
* How can user information be connected to the appropriate state?
* How can Row-Level Security be tested to confirm that users only see authorized records?
* How can a business maintain a single Power BI report while providing different users with different views of the underlying data?

  ## Tools and Technology
* Excel
* Microsoft Power BI
* Access Control validation
* Power BI View as
* DAX
* Role creation
* Role testing
* Role testing

## Dataset
* Sales
* Users
* State Map
  

  
