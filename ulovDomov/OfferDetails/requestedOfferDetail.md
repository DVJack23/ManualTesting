# TC-UDOD01: Offer details page opens and displays selected offer

## Description
This test case verifies that when a user opens the details of a listing from the listings page, the offer detail page displays the correct information for the selected offer.

## Test Type
Positive – Low level

## Preconditions
1. A valid search for flat rentals has been performed from the main page (including valid address, property type, and offer type).
2. The database contains listings that match the entered search criteria.

## Test Steps
1. Open a web browser and navigate to: [https://www.ulovdomov.cz/](https://www.ulovdomov.cz/)
2. Use the search bar to enter valid parameters (e.g., city = *Praha*, offer type = *Pronájem*, property type = *Byt*) and perform the search.
3. On the listings page, locate the **first offer** in the results and remember the following attributes:
    - Title
    - Price
    - ID (if available in a data attribute or preview element)
4. Click the **Zobrazit inzerát** (Show listing) button for the first offer.
5. Verify that the offer details page is opened in the browser.
6. Verify that the title on the offer details page matches the remembered title.
7. Verify that the price on the offer details page matches the remembered price.
8. Verify that the URL of the offer details page contains the offer ID.

## Expected Result
The user is redirected to the correct offer details page. The page displays the selected offer with a matching title, price, and a URL containing the correct offer ID.
