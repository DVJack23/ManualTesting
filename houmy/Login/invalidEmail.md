# TC-HL02: Login user with invalid email

## Description
This test case describes what happens when a user enters an invalid (unregistered) email during login.

## Test Type
Negative – Low level

## Preconditions
1. The entered email is not registered in the application.

## Test Steps
1. Open a browser and navigate to: https://www.houmy.cz/
2. Click the **Přihlásit se** button.
3. Click the **Pokračujte pomocí e-mailu** button.
4. Enter any unregistered email into the email input field.
5. Enter any password into the password input field.
6. When both input fields are filled, click the **Přihlásit se** button.

## Expected Result
The user is not logged in, and a warning message appears stating:  
**Přihlášení se nezdařilo, zkuste to znovu.**
