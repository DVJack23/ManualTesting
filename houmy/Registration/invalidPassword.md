# TC-HR03: Register new user with invalid password

## Description
This test case describes what happens when a user enters an invalid password during the registration process.

## Test Type
Negative – Low level

## Preconditions
1. The user is not yet registered in the application.
2. A valid email address is used.
3. An invalid password is used (e.g., too short, missing special characters, or no uppercase letters).

## Test Steps
1. Open a browser and navigate to: https://www.houmy.cz/
2. Click the **Získat zdarma** button.
3. Click the **Pokračujte pomocí e-mailu** button.
4. Enter a **valid email address** into the email input field.
5. Enter an **invalid password** into the password input field (e.g., `abc123`).
6. Check the **Souhlasím s podmínkami použití a zásadami ochrany osobních údajů** checkbox.
7. Once both input fields are filled in and the checkbox is checked, click the **Registrovat se** button.

## Expected Result
The password input field is highlighted, and a warning message is displayed.
