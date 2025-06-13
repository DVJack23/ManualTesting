# TC-HL03: Login user with invalid password

## Description
This test case describes what happens when a user attempts to log in with a valid email address but an incorrect password.

## Test Type
Negative – High level

## Preconditions
1. The user is already registered in the application.
2. The correct email address is known.
3. An incorrect password is used intentionally.

## Test Steps
1. Open a browser and navigate to: https://www.houmy.cz/
2. Navigate to login via email page
3. Fill the login form with correct email address and incorrect password 
4. Confirm login

## Expected Result
The user is not logged in, and a warning message appears stating:  
**Přihlášení se nezdařilo, zkuste to znovu.**
