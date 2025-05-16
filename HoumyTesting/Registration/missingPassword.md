# TC-HR04: Register new user without entering a password

## Description
This test case describes what happens when a user attempts to register without entering a password.

## Test Type
Negative – Low level

## Preconditions
1. The user is not yet registered in the application.
2. A valid email address is used.

## Test Steps
1. Open a browser and navigate to: https://www.houmy.cz/
2. Click the **Získat zdarma** button.
3. Click the **Pokračujte pomocí e-mailu** button.
4. Enter a **valid email address** into the email input field.
5. Check the **Souhlasím s podmínkami použití a zásadami ochrany osobních údajů** checkbox.
6. Without entering a password, click the **Registrovat se** button.

## Expected Result
The password input field is highlighted, and a warning message is displayed:  
**Heslo musí obsahovat alespoň 8 znaků**.
