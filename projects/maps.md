# Visitors map with QGIS

## Local Heritage & Community Maps (QGIS Practice)
 * Local Discovery Map: A printed, pocket-sized neighbourhood map highlighting points of interest, quiet walking routes, and local history notes.
 * Themed Walking Tours: Specialty maps—such as a "Wivi Lönn" tour—designed to guide visitors through specific local learning spots or historical touchpoints.
 * Tool Focus: Built via QGIS as a low-friction, practical pilot project for learning open-source mapping software.

**Tools**

[https://www.qgis.org](https://www.qgis.org)

A custom tourist map in QGIS is straight forward once you know the step-by-step workflow. Here is the standard process to turn raw spatial data into a styled print or digital map:
 * Gather Map Data: Install the QuickOSM plugin in QGIS to directly download data from OpenStreetMap. Query and pull layers for your area of interest, such as roads, buildings, parks, waterways, and points of interest like historic sites, restaurants, or transit stops.
 * Filter and Clean Layers: Open the attribute table or query builder for each layer to hide unnecessary elements. For instance, filter roads to show only major avenues and pedestrian paths while hiding alleyways, keeping the map visual uncluttered.
 * Style the Features: Go to the layer Properties and select Symbology. Choose custom color palettes for land and water, set vector line weights for roads, and assign custom vector icons or colored markers to your points of interest.
 * Add Labels: Enable Labels on key layers like streets and landmarks. Customize the font, text size, and add a subtle text buffer (halo) so labels remain legible over background colors.
 * Set Up the Print Layout: Create a new Print Layout (Project > New Print Layout). Add your map canvas to the page, set your preferred page size, and dial in the exact scale.
 * Add Map Elements: Insert essential tourist map items like a title, a legend for your points of interest, a scale bar, a north arrow, and proper attribution text (e.g., Data © OpenStreetMap contributors, Made with QGIS).
 * Export Final Output: Export your finished map as a high-resolution image (PNG/TIFF) or a print-ready PDF via Layout > Export as PDF.
To check if your setup is working smoothly at step 1, verify that your downloaded OpenStreetMap vector features align correctly over a standard base map background (like QuickMapServices OpenStreetMap).
