# TC-HC02: Creating Contact That Already Exists

## Description
This test case describes what happens when a user tries to create a new contact using contact information that already exists.

## Test Type
Negative – Low level

## Preconditions
1. The user is logged in to the application.
2. The contact already exists in the address book.

## Test Steps
1. Open the address book.
2. Click the **+ Vytvořit nový kontakt** button.
3. Fill the form with the same contact information as an existing contact (e.g., same name, email, and phone number).
4. Click the **Uložit** button.

## Expected Result
The contact is not created. An error message appears saying: **"Kontakt nebylo možné vytvořit"** (e.g., as a toast notification or error banner).
