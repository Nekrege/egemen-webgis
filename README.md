# Egemen Erken — Web GIS Portfolio

Personal website developed for the GMT458 Web GIS course
at Hacettepe University.

## Pages

- index.html: About me
- projects.html: Academic projects and tables with images
- maps.html: Interactive Leaflet and OpenLayers maps of Ankara

## Technologies

- HTML
- CSS
- Git
- JavaScript
- Leaflet 
- OpenLayers 
- OpenStreetMap

## Current Features

- Navigation between pages
- CSS heading animation
- Responsive layout
- Project descriptions and a table containing an image
- Leaflet and OpenLayers maps with three Ankara landmarks
- Markers visible only at zoom level 12 or higher
- Clickable markers displaying location information
- World repetition disabled
- Independent reset buttons for both maps

## AI Assistance

I used ChatGPT to learn how to structure HTML pages, connect a
shared CSS file, create a CSS animation, and place an image inside
a table. I also learned how to adjust image size using CSS.

Estimated AI-assisted work time so far: approximately 15 minutes.
This estimate will be updated as the project progresses.

## Leaflet Development

With AI assistance, I learned to group markers and show them
only at zoom level 12 or higher, and to disable world tile
repetition using noWrap.

I resolved an OpenStreetMap tile access error by serving the
page through VS Code Live Server instead of opening it as a file.

## OpenLayers Development

With AI assistance, I learned to convert longitude and latitude
coordinates to EPSG:3857, create vector markers, control their
visibility by zoom level, and display information on marker clicks.

World repetition is disabled using wrapX and view constraints.

## Run Locally

Open the project folder in VS Code and start Live Server.
Navigate to index.html and use the menu to explore the pages.

## Live Website

https://nekrege.github.io/egemen-webgis/

## Additional AI Learning

I learned to handle button click events and reset each map
to its initial centre and zoom level.