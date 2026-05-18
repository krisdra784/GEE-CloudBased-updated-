# GEE-CloudBased-updated-

# Google Earth Engine Land Surface Temperature Web Application
This repository contains the complete Google Earth Engine (GEE) JavaScript codebase developed for processing and visualizing spatial thermal dynamics across user-defined Areas of Interest (AOIs).

## Project Overview
Use `##` for section headings to divide major project criteria components. 
This application automates the generation of Land Surface Temperature (LST) profiles utilizing thermal bands from Landsat 8 missions, presenting an interactive user environment.

### Author Information
Use `###` for smaller sub-headings.
* **Student Name:** [Kris Dragovic]
* **Student ID:** [s4003055]

---

## App Functionality

### Core Application Components:
- **Header Panel:** Displays student verification metadata along with an application workflow summary overview.
- **Interactive Button Elements:** Houses dropdown interactive selection menus and triggering action components.
- **Map Panel:** Renders background geographical frameworks and updates spatial layers conditionally based on runtime state queries.

### Project Steps:
1. Initialize Earth Engine Client instance environment interface.
2. Formulate regional boundary bounding criteria masks.
3. Compute Top of Atmosphere (TOA) thermal values to Celsius metric layers.

---

## Technical Formatting Summary
Text highlights utilize markdown variations such as **Bold text** adjustments for key labels, *Italic text* transformations for metadata properties, and ~~Strikethrough~~ parameters for legacy routines.

You can also combine **bold and _italic_** formatting styles inside evaluation metric paragraphs where necessary.

---

## Access Links & Assets
[This is a link to the Live GEE Web Application](https://code.earthengine.google.com/6c07b3af77c934cbc35313440d70aad8)

![This is an image placeholder showing example architecture](https://via.placeholder.com/150)

---

## Code Blocks
Inline syntax references like `ui.Panel()` define element spatial alignment parameters.

Block of code sample context:
```javascript
// GEE Code initialization verification step
var greeting = 'Google Earth Engine UI Application Initialized';
print(greeting);
