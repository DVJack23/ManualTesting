# TC-HC03: Add Bank Account Information to Contact

## Description
This test case describes how a user can add bank account information to an existing contact that does not yet have this information.

## Test Type
Positive – High level

## Preconditions
1. The user is logged in to the application.
2. The contact already exists in the address book but has no bank account information.

## Test Steps
1. In the navigation menu, click the **Adresář** button.
2. Click on the box representing the desired contact.
3. In the **Bankovní spojení** section, click the **Přidat informaci** button.
4. Fill the prefix input field with a valid numeric value (if applicable).
5. Fill the account number input field with a valid Czech bank account number.
6. Fill the bank code input field with a valid 4-digit bank code (e.g., 0600).
7. Once all input fields are filled, click the **Uložit** button.

## Expected Result
The user is redirected to the contact detail page. A success message **"Kontakt byl úspěšně upraven"** appears (e.g., as a toast notification), and the new bank account information is visible in the **Bankovní spojení** section.
