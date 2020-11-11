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

## Email Template

1. Admin should decide what content needs to be sent
2. At what time this needs to be sent

## Email Verification

1. Verification Email should be valid for a certain period
2. Preferably 2 hours post which user needs to re-verify
3. Clean up the token in the backend DB

## Resend Email verification link

1. User would still be able to login
2. Since the email is not verified, user is barred of services
3. enable an option to re-verify the email

## Double Email verification checks

1. If the user clicks the Email Verification link again
2. It should display that email is already registered

## Welcome Email Page

1. Once the user clicks on Verify Email Link
2. A Welcome Page should be displayed

## Capture Console logs

1. Capture logs to a log file instead of console
2. All the logs should append to a log file on a daily basis
3. Periodically append it
4. Create a new file on a daily basis

## Payment gateway integration

1. Integrate a Third Party Micro Service
2. Enable the user to pay to a verified merchant
