# ProfitPro User Manual

## Table of Contents
1. Introduction
2. System Requirements
3. Using the Application
4. Troubleshooting
5. Frequently Asked Questions (FAQ)


## 1. Introduction

Welcome to the accounting website ProfitPro! This web application allows you to create a Chart of Accounts, journalize transactions, generate financial statements, and view ratio analysis. The system consists of a databse backend to store and retreive information and an interactive frontend to view and input data.

## 2. System Requirements

- A computer or tablet with a web browser (IE, Firefox, Chrome, Safari, etc.)

## 3. Using the Application

1. In order to access ProfitPro's accounting features, you must first log in/sign up.
    - Click "Sign In" or "Get Started" on the home page to log in
    - To give you full access to the entire site, we created an admin account specifically for you.
      - Email: X
      - Password: X
   
2. The Bookkeeping page allows the user to create or modify accounts.

   Create Account
     - Enter information into the required input fields
     - For additional help, please use the provided tooltips
     - Click on "Add Account" to finish
     - Confirm creation of account by checking the "Modify Accounts" tab
  
    Modify Accounts
     - Click on an account in the table to view more information
         - Click "Back" to view all accounts again
         - Click "Modify" to modify account information or modify account ledger
           - Click "Modify Account Information"
             - Enter input fields to change account information
             - Click "Add Account" to finish
           - Click "Modify Account Ledger"
             - Enter input fields to add a new record to ledger
             - Click "Add Record" to finish
         - Click "Deactivate Account" to deactivate account
           - Confirm deactivation by either selecting "Yes" or "No"
            
3. The Reports page allows the user to view the Chart of Accounts, send emails, and create reports

     Accounts
       - Use the search feature to find specific accounts by inputting any keywords found in account number, name, description, normal side, category, or                 subcategory
       - Select an account to view account information, ledger, journal entries, and event log
         - Click "Back" to view all accounts again
         - Create a journal entry for the account by clicking "Create Journal Entry"
           - Enter date, description, add credits/debits, and attach a reference document
           - Click "Submit" to finish
         - Approve or deny any pending journal entries in the "Actions" column

     Email
       - Send emails by entering email address, subject, and message
       - Click "Send Email" to finish

     Create Reports
       - Create a report by inputting statement type and start/end dates
       - Click "Generate Statement" to create statement
       - Click "Save and Print" to save and print generated statement

5. The Administrator page allows an administrator to manage users, create users, send emails, and view expired passwords

     Manage Users
       - Click on users to view a dropdown of user information
       - Click on "Update Information" to change user information
         - Enter the input fields and click "Submit" to save changes
       - Click on "Change User Role" to change account type
         - Use the dropdown to select role and click "Submit" to save changes
       - Click on "Activate/Deactivate User" to activate or deactivate account
         - Use the dropdown to activate or deactivate account and click "Submit" to save changes
       - Click on "Suspend User" to suspend a user throughout a certain period
         - Input the start date and end date and click "Submit" to save changes

     Create User
       - Enter user information into the input fields
       - Click "Submit" to create user

     Email
       - Send emails by entering email address, subject, and message
       - Click "Send Email" to finish

     Expired Passwords
       - Click on a user to view a dropdown of their expired password and date

6. The Home page allows the user to view financial ratios and pending journal entries waiting for approval
     - Click "See Data" to view ratio calculations
     - Click "To Accounts" view Chart of Accounts 
     

## 4. Troubleshooting

- If the map doesn't load, check your internet connection and ensure you have a valid Mapbox API key.
- If bus positions aren't updating, verify that the WebSocket connection is established (check browser console for messages).
- For database connection issues, double-check your MySQL connection string in `main.py`.

## 5. Frequently Asked Questions (FAQ)

Q: How often do bus positions update?
A: Bus positions update in real-time as events are received from the Kafka stream.

Q: Can I track multiple buses simultaneously?
A: Yes, the system is designed to handle multiple assets (buses) concurrently.

Q: Is historical data available?
A: The current version focuses on real-time data. Historical data features may be added in future updates.

## 8. Contact Support

Email: appdomain-profitpro@gmail.com
Phone Number: +01 1234567890

