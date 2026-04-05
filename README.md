# TAMU WebGIS Lab 6 - Advanced Javascript Mapping with Leaflet JS

This folder contains three HTML web mapping files created for TAMU WebGIS Lab 6.

## Files Included:

1. **Tutorial1_GeoJSON.html** - Tutorial 1: Using GeoJSON with Leaflet
   - Demonstrates GeoJSON points, lines, and polygons
   - Shows styling and popup interactivity
   - Content based on official Leaflet tutorial

2. **Tutorial2_Choropleth.html** - Tutorial 2: Interactive Choropleth Map
   - Interactive US state density map with hover effects
   - Includes info control and legend
   - Demonstrates dynamic styling based on properties
   - Content based on official Leaflet tutorial

3. **Custom_Map.html** - Custom TAMU Campus Map
   - Focused on Texas A&M University campus (coordinates: 30.6188, -96.3365)
   - Displays TAMU building footprints
   - Buildings colored in maroon (Texas A&M colors)
   - Hover effects highlight buildings and display building information
   - Click on buildings to zoom to that building
   - Interactive info control showing building name and abbreviation

## How to Use:

1. **Download tamubuildings.js**
   - The Custom_Map.html references this external file
   - Download from: https://raw.githubusercontent.com/tamu-edu-students/2025-TAMU-GEOG-678-WebGIS-MGsc/main/labs/tamubuildings.js
   - Save it in the same directory as the HTML files

2. **Open in Browser**
   - Simply open any HTML file in a web browser
   - All required libraries (Leaflet) load from CDN
   - No server required - works locally

3. **Features in Custom Map**
   - Zoom with mouse wheel or map controls
   - Pan by dragging
   - Hover over buildings to see details
   - Click buildings to zoom in
   - Use info box to see building names and abbreviations

## Lab Requirements Met:

✅ Tutorial 1: Using GeoJSON with Leaflet - Complete working example
✅ Tutorial 2: Interactive Choropleth Map - Complete working example
✅ Custom TAMU Map:
  - Title with student name
  - Zoomed to TAMU Campus with appropriate zoom level
  - TAMU Building GeoJSON data integrated
  - Buildings colored in maroon
  - Visual highlighting on hover
  - Click listener to zoom to buildings
  - Info control showing building name and abbreviation

## Technologies Used:

- Leaflet.js v1.3.1
- OpenStreetMap tiles
- GeoJSON format for building data
- Vanilla JavaScript (no frameworks)

## Notes:

- All map functionality works offline once files are downloaded
- External resources (map tiles) require internet connection
- Compatible with all modern browsers
- Responsive design for different screen sizes

## Author:

[Student Name]
TAMU WebGIS Course - Lab 6
Date: [Current Date]
