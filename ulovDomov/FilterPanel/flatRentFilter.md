# TC-UDFP01: Check that basic filter options on the listings page work when searching for flat rentals

## Description
This test case verifies that the filter panel can be opened from the listings page and that the user can modify basic search parameters such as apartment layout, minimum and maximum price, minimum and maximum size.

## Test Type
Positive – Low level

## Preconditions
1. A valid search for flat rentals has been performed from the main page (including valid address, property type, and offer type).
2. The database contains listings that match the filtered search criteria.

## Test Steps
1. Open a web browser and navigate to: [https://www.ulovdomov.cz/](https://www.ulovdomov.cz/)
2. Use the search bar to enter valid parameters (e.g., city = *Praha*, offer type = *Pronájem*, property type = *Byt*) and perform the search.
3. On the listings page, click the **Upravit hledání** (Edit Search) button to open the filter panel.
4. In the layout section, select the option **1+kk**.
5. In the "Minimum price" input field, enter **15000**.
6. In the "Maximum price" input field, enter **25000**.
7. In the "Minimum size" input field, enter **50** (square meters).
8. In the "Maximum size" input field, enter **100** (square meters).
9. Click the **Zobrazit X odpovídajících pronájmů** (Show X matching rentals) button to apply filters.
10. Verify that the selected filters (layout, price, size) are visible in the filter summary bar above the results.
11. Verify that the displayed listings reflect the applied filters (e.g., all flats shown have layout **1+kk**, price ≥ 15000 CZK, size ≥ 50 m²).

## Expected Result
The user is shown a list of property listings that match all the specified filter criteria. The applied filters are clearly visible and correctly influence the results.
