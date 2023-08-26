![header](https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/95c8bd29562445.57a703ebb8224.png)
# UFO Insight: Interactive Dashboard App and Pattern Analysis for Extraordinary Sighting Dates

Welcome to the **UFO Sightings Analysis and Visualization** project! In this repository, we explore and analyze key factors that contribute to the credibility of UFO sightings. By querying a comprehensive UFO sightings database and utilizing various visualization techniques, we aim to uncover insights about the reported sightings and their characteristics.

## Table of Contents
* Introduction
* Key Features
* Technologies Used
* Usage
* Results
* Model Training
* Conclusion

## Introduction
In this project, we delve into the fascinating world of UFO sightings, focusing on factors that make these sightings more credible. We started by analyzing a database of over 80,000 UFO reports spanning from 1910 to 2013. Our objective was to identify dates with significant sightings that met specific criteria, such as multiple sightings in close proximity reported from different countries.

## Key Features

* **Data Cleanning** I cleaned the database to 

* **Database Query**: I conducted a detailed query on the UFO sightings database to identify dates with more than ten sighting reports reported from more than two countries. This helped us pinpoint five specific dates with substantial sightings.

* **Interactive Interface**: Using HTML, CSS, JavaScript, and libraries such as D3, Date, Leaflet, and Plotly, we developed an easy-to-use interface. The interface features a dropdown menu that lists the five identified dates.

* **Interactive Map**: When a date is selected from the dropdown menu, an interactive map displays the geographical locations of each sighting. Clicking on a marker reveals essential details about the sighting, including the date, time, shape, and comments.

* **Shape Categorization**: To better understand reported shapes, we categorized them into four distinct groups: round, pointy, light, and other. We acknowledged that geometric shapes can appear differently based on viewpoints. To illustrate this, we integrated a rotating cube in the dashboard, allowing users to explore how perspective changes affect the observed silhouette.

* **3D Visualization**: We created a 3D plot to visualize the distribution of sightings in both time and location. By manipulating the plot along the X-Y axis, users can assess the distances between reports on the selected date. Rotating the plot along the Z-axis reveals the time intervals between the sightings.
