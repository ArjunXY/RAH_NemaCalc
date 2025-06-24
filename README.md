# RAH NemaCalc

RAH NemaCalc is a user-friendly desktop application built with Python for precise measurement and analysis of nematodes from microscope images. It provides a suite of tools for researchers and students to perform length, diameter, volume, and biomass calculations efficiently.

---

## Key Features

*   **Interactive Image Measurement:**
    *   Load single images or entire galleries.
    *   Intuitive zoom and pan controls (mouse wheel and right-click drag).
    *   Set a custom scale based on a known reference in the image.
*   **Versatile Measurement Tools:**
    *   **Straight Line:** Click and drag for simple distance measurements.
    *   **Freehand:** Draw along curved paths for accurate length of non-linear subjects.
    *   **Merge Lines:** Combine multiple segments into a single, continuous measurement.
    *   **Customizable Line Color:** Change the color of measurement lines for better visibility.
*   **Advanced Nematode Analysis:**
    *   **Andrassy's Formula:** Automatically calculate nematode volume and biomass by saving 'length' and 'diameter' variables.
    *   **Frustum Method:** For more accurate volume and surface area, divide the nematode's body into segments and measure the diameter at each point.
*   **Comprehensive Data Export:**
    *   Export measurements and calculations to **CSV**, **Excel**, and **PDF** report formats.
    *   Save the image with all measurement annotations drawn on it.
    *   Export to all formats with a single click.
*   **User-Friendly Interface:**
    *   Built-in user guide, quick tips, and about section.
    *   Handy keyboard shortcuts for common actions (`Ctrl+O` to Open, `Ctrl+Z` to Undo, etc.).
    *   Robust undo functionality to revert actions.

---

## How to Use

1.  **Load an Image:**
    *   Click `Load Image` to open a single image file or `Load Gallery` to import all images from a folder.
    *   Use the `←` and `→` buttons to navigate through the gallery.

2.  **Set the Scale:**
    *   This is a crucial first step for accurate measurements.
    *   Click `Set Scale`.
    *   Find a scale bar or an object of known length in your image.
    *   Click and drag to draw a line along the reference object.
    *   Enter the known length in the dialog box (the default unit is micrometers, μm).

3.  **Make Measurements:**
    *   **Straight Line:** Simply click and drag from a start point to an end point.
    *   **Freehand:** Click the `Freehand` button (it will turn green). Click and drag to trace a curved path. Toggle it off to return to straight-line mode.
    *   **Merge Lines:** To measure a long, curved object, draw multiple straight lines along its path. Then, click `Merge Lines`, select the measurements you want to combine, and they will be summed into a single measurement.

4.  **Perform Calculations:**
    *   After making a measurement, click `Save as Variable`. Give it a name like `length` or `diameter`.
    *   Once you have saved `length` and `diameter`, click the `Next →` button to go to the **Calculations** page. Here you will see the calculated Volume and Biomass.
    *   For more detailed analysis, use the `Frustum Calculations` button. This will guide you to divide a length measurement into segments and measure the diameter at each point, yielding a more accurate volume and surface area.

5.  **Export Your Results:**
    *   Use the `Export` buttons in the top toolbar to save your data.
    *   You can export to **CSV**, **Excel**, **PDF** (a full report with the annotated image), or as a standalone **Image**.
    *   Click `All Formats` to export to all available formats at once.

---

## License

This project is licensed under the **RAH NemaCalc License Agreement**.

The software is free to use and share in its original, unmodified form for **non-commercial purposes only**. You must provide attribution to the creator, Arjunveer Singh, in all copies and distributions. Modifying, reverse-engineering, or using the software for commercial gain without a separate written agreement is strictly prohibited. Please see the `LICENSE` file for full details.

---

## Feedback, Suggestions and other Communication

For any feedback, suggestions for the software (bugs, improvements etc.) and any other communication, you can mail me at [arjunveers94@gmail.com](mailto:arjunveers94@gmail.com)
