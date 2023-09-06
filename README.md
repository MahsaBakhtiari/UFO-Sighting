![header](https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/95c8bd29562445.57a703ebb8224.png)
# UFO Insight: Interactive Dashboard App and Pattern Analysis for Extraordinary Sighting Dates
11111111111111111111

Welcome to the **UFO Sightings Analysis and Visualization** project! In this repository, we explore and analyze key factors that contribute to the credibility of UFO sightings. By querying a comprehensive UFO sightings database and utilizing various visualization techniques, we aim to uncover insights about the reported sightings and their characteristics. Here is the 👽🛸[dashboard](https://mahsabakhtiari.github.io/UFO-Sighting/).

## Introduction
In this project, we delve into the fascinating world of UFO sightings, focusing on factors that make these sightings more credible. We started by analyzing a database of over 80,000 UFO reports spanning from 1910 to 2013. Our 👽 was to identify dates with significant sightings that met specific criteria, such as multiple sightings in close proximity reported from different countries.

## Key Features

* **Data Cleaning** I cleaned the database to 

* **Database Cleaning and Query**: Prior to analysis, I performed cleaning of the UFO sightings database. This involved removing inconsistencies, duplicates, and irrelevant entries to ensure the accuracy of our results. Once the database was cleaned, we conducted a detailed query to identify dates with more than ten sighting reports reported from more than two countries, leading us to discover five specific dates with substantial sightings.

* **Interactive Interface**: Using HTML, CSS, JavaScript, and libraries such as D3, Date, Leaflet, and Plotly, we developed an easy-to-use interface. The interface features a dropdown menu that lists the five identified dates.

* **Interactive Map**: When a date is selected from the dropdown menu, an interactive map displays the geographical locations of each sighting. Clicking on a marker reveals essential details about the sighting, including the date, time, shape, and comments.

* **Shape Categorization**: To better understand reported shapes, we categorized them into four distinct groups: round, pointy, light, and other. We acknowledged that geometric shapes can appear differently based on viewpoints. To illustrate this, we integrated a rotating cube in the dashboard, allowing users to explore how perspective changes affect the observed silhouette.

* **3D Visualization**: We created a 3D plot to visualize the distribution of sightings in both time and location. By manipulating the plot along the X-Y axis, users can assess the distances between reports on the selected date. Rotating the plot along the Z-axis reveals the time intervals between the sightings.

## Model Training
To predict UFO shapes based on time and location, we trained a random forest model using data from four dates. While the model performed slightly better than random guessing, it exhibited signs of overfitting. This suggests that clear patterns between time, space, and reported shapes might not be evident for the selected dates.

## Conclusion
In summary, the UFO Sightings Analysis and Visualization project delves into credible UFO sightings through data analysis, interactive visuals, and predictive modeling. Notably, our findings reveal non-homogeneity in the reports regarding the relationship between spacetime and the reported shapes. This intriguing insight adds complexity to the UFO phenomenon, leaving us with more questions than answers. Explore the interface, maps, and plots to dive into the captivating world of UFO phenomena.

## Resources 

* https://www.kaggle.com/datasets/NUFORC/ufo-sightings?resource=download
* https://lospec.com/palette-list/ufo-50
* https://www.cdnfonts.com/



[![jhc github](https://img.shields.io/badge/GitHub-MahsaBakhtiari-181717.svg?style=flat&logo=github)](https://github.com/jhrcook)
[![python](https://img.shields.io/badge/Python-3.9-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![jupyter](https://img.shields.io/badge/Jupyter-Lab-F37626.svg?style=flat&logo=Jupyter)](https://jupyterlab.readthedocs.io/en/stable)
