# TC-HR05: Register new user with already registered email

## Description
This test case describes what happens when a user attempts to register using an email address that is already registered in the application.

## Test Type
Negative – High level

## Preconditions
1. The email address is already registered in the application.
2. A valid password is used.

## Test Steps
1. Open a browser and navigate to: https://www.houmy.cz/
2. Navigate to the registration page via email.
3. Enter an already registered email address and a valid password into the registration form.
4. Check all necessary checkboxes.
5. Confirm registration.

## Expected Result
The user is not registered, and an alert window is displayed with the following message:  
**Registrace se nezdařila, zkuste to znovu.**
