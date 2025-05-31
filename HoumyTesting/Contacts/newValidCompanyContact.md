# TC-HC04: Create New Company Contact with All Information

## Description
This test case describes how a user can create a new company contact with complete information via the address book.

## Test Type
Positive – Low level

## Preconditions
1. The user is logged in to the application.
2. The contact does not yet exist.

## Test Steps
1. Open the address book.
2. Open the create new contact page.
3. Select the option that the contact is a company.
4. Select the option to add more information.
5. Fill in all input fields with valid details (e.g., company name, IČO, DIČ, address, phone number, email, bank details).
6. Save your contact.

## Expected Result
The user is redirected to the contacts page. A success message **"Nový kontakt byl úspěšně vytvořen"** appears (e.g., as a toast notification), and the new company contact is visible in the list of contacts with all provided information correctly displayed.
