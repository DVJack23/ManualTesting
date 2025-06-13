# TC-UDR01: Register new user with valid user details

## Description
This test case verifies the ability to register a new user in the application using a valid and unique email address along with a valid password.

## Test Type
Positive – Low level

## Preconditions
1. The user is not yet registered in the application.
2. A valid and unique email address is available for testing (i.e., it has not been used in the system).

## Test Steps
1. Open a web browser and navigate to: [https://www.ulovdomov.cz/](https://www.ulovdomov.cz/)
2. Click on the **burger menu** in the top right corner of the homepage.
3. Click the **Registrujte se** (Register) button.
4. Enter a **valid and unique email address** into the email input field.
5. Click the **Pokračovat** (Continue) button to confirm the email address.
6. Enter a **valid password** into the password input field (e.g., minimum 8 characters, meets password policy).
7. In the role selection section, choose the option **Zájemce (hledám bydlení)**.
8. Click the **Vytvořit účet a pokračovat** (Create account and continue) button.

## Expected Result
The user account is successfully created. The user is automatically logged in.
