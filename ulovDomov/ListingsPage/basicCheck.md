# TC-UDLP01: Listing page contains all required elements

## Description
This test case verifies that the listings page displays all expected UI components after a successful property search is performed.

## Test Type
Positive – Low level

## Preconditions
1. A valid search has been performed from the main page (including valid address, property type, and offer type).
2. The user is using a device with a screen width larger than 990px (to ensure the map is displayed).

## Test Steps
1. Open a web browser and navigate to: [https://www.ulovdomov.cz/](https://www.ulovdomov.cz/)
2. Use the search bar to enter valid parameters (e.g., city, offer type, property type), and perform a search.
3. Verify that a **scrollable results panel** is displayed and contains one or more property listings.
4. Verify that a **Upravit hledání** section or button is visible.
5. Verify that the **first listing** in the results contains a **"Vytvořit hlídače"** (Create watchdog) button.
6. Verify that the **number of results found** is displayed in the top part of the scrollable listings panel.
7. Verify that the **sorting options** are available (e.g., by date, price, relevance) and can be interacted with.
8. For first listing preview and check that the following elements are visible:
    - Property image and header
    - Price
    - **Contact** button
    - **Show details** button
    - **Save offer** button (e.g., with heart icon)
9. Verify that the **map panel** is visible on the right side and displays the locations of the listed properties.
10. Verify that the map contains functional buttons:
    - **Hledat v této oblasti** button
    - **Zoom in** and **zoom out** buttons
    - **reset map position** button

## Expected Result
The user is shown a list of matching offers based on the search parameters. The listings page contains all required UI components: scrollable results, filters, controls, offer previews with details, and an interactive map with controls.
