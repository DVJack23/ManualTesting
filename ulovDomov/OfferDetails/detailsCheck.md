# TC-UDOD02: Offer details page contains all required elements

## Description
This test case verifies that the offer details page contains all necessary user interface components relevant to viewing a rental property offer.

## Test Type
Positive – Low level

## Preconditions
1. A valid search for flat rentals has been performed from the main page (including valid address, property type, and offer type).
2. The database contains listings that match the entered search criteria.

## Test Steps
1. Open a web browser and navigate to: [https://www.ulovdomov.cz/](https://www.ulovdomov.cz/)
2. Use the search bar to enter valid parameters (e.g., city = *Praha*, offer type = *Pronájem*, property type = *Byt*) and perform the search.
3. Click the **Zobrazit inzerát** (Show listing) button for the first offer in the list.
4. Verify that the **Photo gallery** section is visible and contains photos of the property.
5. Verify that the **Title** section is visible and displays valid data.
6. Verify that the **Price** section is visible and displays valid data.
7. Verify that the **Contact section** is visible and contains:
    - Name of the contact person
    - Image/avatar of the contact
    - A button to contact the advertiser
8. Verify that the **Watchdog panel** is visible and includes a button to create a watchdog alert.
9. Verify that the **Report** button is visible.
10. Verify that the **Share** button is visible.
11. Verify that the **Description** section is visible and contains descriptive text about the property.
12. Verify that the **Info details** section is visible and displays valid data (e.g., layout, area, floor, equipment).
13. Verify that the **Map** section is visible and shows the location of the property with a marker.

## Expected Result
The offer details page is displayed. All required UI components are present and populated with valid data: photo gallery, title, price, contact section, watchdog panel, report and share buttons, description, additional info details, and map.
