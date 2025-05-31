# TC-HC01: Create New Contact

## Description
This test case describes how a user can create a new contact via the address book.

## Test Type
Positive – High level

## Preconditions
1. The user is logged in to the application.
2. The contact does not yet exist.

## Test Steps
1. In the navigation menu, click the **Adresář** button.
2. In the top right corner, click the **+ Vytvořit nový kontakt** button.
3. Fill the first name input field with a valid first name.
4. Fill the last name input field with a valid last name.
5. Fill the email address input field with a valid email address.
6. Fill the phone number input field with a valid phone number.
7. Once all input fields are filled, click the **Uložit** button.

## Expected Result
The user is redirected to the contacts page. A success message **Nový kontakt byl úspěšně vytvořen** appears (e.g., as a toast notification), and the new contact is visible in the list of contacts.
