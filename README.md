# HTML-Popup-data
Given chance to do a HTML Popup project for a point data 

# GIS Custom ArcMap HTML Popups

In enterprise GIS, presenting data clearly to end-users is just as important as the spatial analysis itself. This repository demonstrates how I replaced the default, cluttered ArcMap identify windows with a clean, branded HTML popup.

## Before and After
*(Insert a screenshot here of the ugly default ArcMap popup)*
**Before:** The default popup showed irrelevant system fields (like `OBJECTID` and `Shape.len`) and lacked visual hierarchy.

*(Insert a screenshot here of your clean, custom popup)*
**After:** Using inline HTML and CSS, I created a custom popup that emphasizes the Project Name, formats the budget financially, and provides a clickable call-to-action button for stakeholders.

## Technical Details
* **Language:** HTML / Inline CSS
* **Environment:** ArcMap / ArcGIS Online 
* **Dynamic Fields:** Utilizes bracket notation (e.g., `{Project_Name}`) to pull dynamic database attributes directly into the HTML structure.
