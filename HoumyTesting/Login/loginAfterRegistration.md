# TC-HL04: Newly registered user can log in to the app immediately

## Description
This test case verifies that a newly registered user can log in to the application immediately after completing the registration process.

## Test Type
Positive – Low level

## Preconditions
1. The user is not yet registered in the application.

## Test Steps
1. Open a browser and navigate to: https://www.houmy.cz/
2. Click the **Získat zdarma** button.
3. Click the **Pokračujte pomocí e-mailu** button.
4. Enter a **new email address** into the email input field.
5. Enter a **valid password** into the password input field.
6. Check the **Souhlasím s podmínkami použití a zásadami ochrany osobních údajů** checkbox.
7. Click the **Registrovat se** button.
8. On the confirmation screen, click the **Zpět na přihlášení** button.
9. Click the **Přihlásit se** button.
10. Click the **Pokračujte pomocí e-mailu** button.
11. Enter the **newly registered email** into the email input field.
12. Enter the **same password** used during registration into the password input field.
13. Click the **Přihlásit se** button.
14. Enter your **first name** into the first name input field.
15. Enter your **last name** into the last name input field.
16. From the dropdown menu, select the **number of owned properties**.
17. Click the **Uložit a pokračovat** button.

## Expected Result
The user is successfully logged in and the main dashboard is displayed.
