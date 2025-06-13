# TC-HR02: Register new user with invalid email

## Description
This test case describes what happens when a user enters an invalid email address during the registration process.

## Test Type
Negative – Low level

## Preconditions
1. The user is not yet registered in the application.
2. An invalid email address is used (e.g., missing "@" or domain).

## Test Steps
1. Open a browser and navigate to: https://www.houmy.cz/
2. Click the **Získat zdarma** button.
3. Click the **Pokračujte pomocí e-mailu** button.
4. Enter an invalid email address into the email input field (e.g., `userexample.com`).
5. Enter a valid password into the password input field.
6. Check the **Souhlasím s podmínkami použití a zásadami ochrany osobních údajů** checkbox.
7. Once both input fields are filled in and the checkbox is checked, click the **Registrovat se** button.

## Expected Result
The email input field is highlighted, and a warning message is displayed:  
**E-mail není ve správném formátu**
