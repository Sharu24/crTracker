# Project Description

1.

# CR Tracker

## Error Logger:

1. Have a UTC Timestamp
2. IP Address of the request
3. What Time the Error Occurred
4. What exactly is the error
5. Send the Errors to the Admin
6. Create a Logging tracker in Cloud

## Event Logger

Admin, User and Manager

1. Create a new Log File every hour with timestamp
2. Capturing every event in the log files in a standard format
3. EOD, (At 12 AM midnight) ZIP all the files in the folder
4. Communicate Zipped files location to the to the Admin
5. Statistics
   1. Number of users logged in by region etc.

## Email Template

1. Admin should decide what content needs to be sent
2. At what time this needs to be sent
3. Successful email verification template

## Email Verification

1. Verification Email should be valid for a certain period
2. Preferably 2 hours post which user needs to re-verify
3. Clean up the token in the backend DB

## Resend Email verification link

1. User would still be able to login even if the user is not verified
2. Since the email is not verified, user is barred of services
3. A pop up to re-verify the email when the user logs in

## Forgot Password functionality (low Priority)

1. Implement using OTP
2. Verify the Mobile Number
3. 4 or 6 digit random OTP code (valid for few minutes)
   1. Have a Count Down timer on the screen

## Double Email verification checks

1. If the user clicks the Email Verification link again
2. It should display that email is already registered

## Welcome Email Page

1. Once the user clicks on Verify Email Link
2. A Welcome Page should be displayed

## Payment gateway integration

1. Integrate a Third Party Micro Service
2. Enable the user to pay to a verified merchant

## Handle Developer console / Inspect for any page

1. Display A Custom message for users with respective CV's

## Donation link

1. Have a features for users to donation generously

## Chatbot

1. Have a chatbot for Customers and First Time users to interract with

## Features - V2

1. Make a Server Montioring Module for NPM
   1. Versioned
   2. configurable
   3. command line interraction
2. Server Desktop Task Manager
   1. Web UI to display Acive, Inactive sessions for a Server
3. Build a Robust Dashboard
   1. Times per day/week/month the Check has hasn't responded
   2. Display by check, response code, protocols
4. Monitor heterogenous servers
   1. handle wide range of Http statuses
   2. Protocols ( ftp, smtp, tcp etc )
5. Send a Broadcast to all Customers
   1. SMS and Email - When the Services are down for maintenance
   2. Email - For new Offerings and Updates
6. Email Server health Reports daily/weekly/monthly
   1. Create a Email Template for reports
   2. Attached a PDF version for the reports as well
7. Generate Synthetic Trasactions to simulate a Customer Interraction
   1. Hit Certain Synthetic Endpoints (API's)
   2. Check if the response is as expected
