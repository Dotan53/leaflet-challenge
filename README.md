# leaflet-challenge

#### Dotan Barak | March 2025

## Summary

This repository contains the files too complete a Leaflet mapping assignment.

USGS API data in JSON form is rendered to an interactive map depicting recent earthquake data, including location, depth and magnitude.

The Leaflet folder holds the necessary files (CSS, HTML and JS) to render the index.html page.

* README
* Leaflet-Part-1
* Images

## Resources
- Initial starter code
- Class instruction and activities
- GEOJSON API endpoint for monthly significant earthquake activity: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/significant_month.geojson
- Leaflet documentation: https://leafletjs.com/reference.html
- Additional tutoring
- Rounding function for coordinates in marker popup: https://stackoverflow.com/questions/11832914/how-to-round-to-at-most-2-decimal-places-if-necessary

## Background
![alt-text](https://github.com/andrewjmack/leaflet-challenge/blob/main/Starter_Code/Images/2-BasicMap.png "Earthquake Data Visualization with Leaflet")
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## Requirements
These requirements apply only to "Part 1: Create the Earthquake Visualization" as "Part 2" is optional with no extra points earned.

### Map
- TileLayer loads without error
- Connects to geojson API using D3 without error
- Markers with size corresponding to earthquake magnitude
- A legend showing the depth and their corresponding color

### Data Points
- Data points scale with magnitude level
- Data points colors change with depth level
- Each point has a tooltip with the Magnitude, the location and depth
- All data points load in the correct locations

<img src="https://capsule-render.vercel.app/api?type=waving&color=BDBDC8&height=150&section=footer" />
