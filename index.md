---
layout: default
title: "GISNerd - Geospatial Intelligence, Powered by Code"
---

# Welcome to the GISNerd Portfolio

**Disclaimer: These projects and the data used are strictly for demonstration and coding exercise purposes. They should not be used for any real analysis or decision-making.**

## Projects Overview

- [Historical Hurricane Visualization](#hurricane)
- [Pasco School Safety](#pasco-school-safety)
- [Earthquake Visualization](#earthquake-visualization)
- [Seagrass Change SWFWMD](#seagrass-change-swfwmd)
- [Hillsborough Safety and Services](#hills-safety-and-services)
- [Land Cover Change in SWFWMD (2011 - 2023)](#land-cover-change-in-swfwmd-2011---2023)

## Project Details

<div class="project-card">
{% capture hurricanes %}
### Historical Hurricane Visualization {#hurricane}

This project is an interactive web-based visualization tool that displays historical hurricane data for the Atlantic and Gulf of Mexico. It combines an interactive map with overlaid storm tracks, dynamic statistics, and multiple charts to analyze key aspects of hurricane activity. Users can select a specific year from a dropdown menu, and the visualization updates to show only the hurricane season (June through November) data. The map displays the storm tracks with colors representing different hurricane categories based on maximum wind speeds, while accompanying charts provide insights into the number of storms per month, the average wind speeds, and the total track lengths. Additional features include a toggle to filter and display only major hurricanes and an animation function that progressively draws the hurricane tracks over time. This comprehensive project leverages open data from NOAA and integrates mapping and charting libraries like Leaflet and Chart.js to create a robust analytical tool for understanding historical hurricane patterns and seasonal trends.

[View Project →](https://kevinmgis.github.io/Hurricane_Visualization/map.html)
{% endcapture %}
{{ hurricane | markdownify }}
</div>

<div class="project-card">
{% capture pasco %}
### Pasco School Safety {#pasco-school-safety}

The Pasco School Safety project focuses on analyzing geospatial data related to school safety initiatives in Pasco County. It utilizes industry-standard GIS tools such as ArcGIS and QGIS, along with custom Python scripts and web mapping libraries like Leaflet, to collect and analyze data from multiple sources. The workflow includes data cleaning, geocoding, network analysis for emergency routes, and risk assessment, providing actionable insights for enhancing school safety.

[View Project →](https://kevinmgis.github.io/Pasco_School_Safety/map.html)
{% endcapture %}
{{ pasco | markdownify }}
</div>

<div class="project-card">
{% capture earthquake %}
### Earthquake Visualization {#earthquake-visualization}

The Earthquake Visualization project offers an interactive map that visualizes both historical and real-time earthquake data. By integrating APIs from the USGS with JavaScript libraries such as Leaflet and D3.js, the project processes seismic data through a robust pipeline involving data extraction, transformation, and visualization. This comprehensive approach delivers a dynamic view of seismic activity that enhances understanding and public awareness.

[View Project →](https://kevinmgis.github.io/Earthquake_Visualization/map.html)
{% endcapture %}
{{ earthquake | markdownify }}
</div>

<div class="project-card">
{% capture seagrass %}
### Seagrass Change SWFWMD {#seagrass-change-swfwmd}

This project investigates changes in seagrass distribution within the Southwest Florida Water Management District over recent years. It leverages remote sensing tools, satellite imagery analysis with GIS software like ArcGIS and ENVI, and custom Python scripts for time-series analysis. The process involves detailed image classification, change detection algorithms, and interactive mapping to illustrate environmental trends and impacts.

[View Project →](https://kevinmgis.github.io/Seagrass_Change_SWFWMD/map.html)
{% endcapture %}
{{ seagrass | markdownify }}
</div>

<div class="project-card">
{% capture hills %}
### Hillsborough Safety and Services {#hills-safety-and-services}

The Hills Safety and Services project conducts an in-depth spatial analysis of community safety and accessibility to essential services in Hills County. Combining traditional GIS techniques with modern web mapping solutions such as Mapbox and custom JavaScript frameworks, the project involves comprehensive data collection, network analysis for emergency service coverage, and detailed visualization of infrastructure needs.

[View Project →](https://kevinmgis.github.io/Hills_Safety_and_Services/map.html)
{% endcapture %}
{{ hills | markdownify }}
</div>

<div class="project-card">
{% capture landcover %}
### Land Cover Change in SWFWMD (2011 - 2023) {#land-cover-change-in-swfwmd-2011---2023}

An interactive WebGIS project that examines land cover transitions in the Southwest Florida Water Management District over a 12-year period using NLCD data. The project employs remote sensing methods, spatial analysis in ArcGIS, and web mapping technologies to deliver in-depth insights into regional environmental changes. The workflow encompasses data preprocessing, change detection algorithms, and interactive visualizations that reveal patterns in land cover dynamics.

[View Project →](https://kevinmgis.github.io/LandUse_Change_Web/map.html)
{% endcapture %}
{{ landcover | markdownify }}
</div>

*Other projects coming soon!*

## Explore More

Visit my main site for more insights and projects in GIS: [GISNerd.com](https://gisnerd.com)

---

© 2025 GISNerd. All rights reserved.