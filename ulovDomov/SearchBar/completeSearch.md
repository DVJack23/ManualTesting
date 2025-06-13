# TC-UDSB02: Search with all parameters set

## Description
This test case verifies the functionality of the search bar on the homepage when the user customizes all available search parameters (offer type, property type, and location).

## Test Type
Positive – Low level

## Preconditions
1. The application is accessible and running.
2. The tester knows valid search parameter options (e.g., property types, offer types, cities within the Czech Republic).

## Test Steps
1. Open a web browser and navigate to: [https://www.ulovdomov.cz/](https://www.ulovdomov.cz/)
2. In the offer type dropdown menu, select **Prodej** (Sale).
3. Click the **Dům** (House) button to select the property type.
4. In the address input field, type a valid Czech city name (e.g., *Brno*, *Praha*, *Ostrava*).
5. Click the **Zobrazit inzeráty** (Show listings) button to perform the search.

## Expected Result
The user is redirected to the property listings page. A list of property offers is displayed that matches all selected search parameters (offer type = *Prodej*, property type = *Dům*, and specified city).
