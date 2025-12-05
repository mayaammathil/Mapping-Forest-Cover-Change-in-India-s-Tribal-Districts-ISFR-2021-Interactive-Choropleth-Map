# Mapping-Forest-Cover-Change-in-India-s-Tribal-Districts-ISFR-2021-Interactive-Choropleth-Map
This repository contains a Python-based workflow for generating an interactive choropleth map of India that visualizes state-wise net change in forest cover using data from the India State of Forest Report (ISFR) 2021.
This project explores how forest cover has changed across Indian states based on the India State of Forest Report (ISFR 2021). I combined the state-level forest statistics with GADM spatial boundaries to create an interactive map that highlights the net gain or loss in forest cover.

The workflow includes cleaning the ISFR dataset, merging it with the state shapefile, and generating a color-coded map using Folium. Each state polygon is shaded from red (forest loss) to green (forest gain), making it easy to see where forest cover has improved and where it has declined.

A special focus of the project is on Tribal Districts, and how forest cover inside and outside RFA/GW (Recorded Forest Area / Green Wash) has shifted over time. The interactive map was created to visually summarise these patterns and offer an intuitive way to explore the ISFR numbers.

The repository contains:

- The cleaned forest cover dataset

- The GADM India state shapefile

- The Python notebook with the full analysis

- Output of the map as a video

This work is part of my ongoing interest in combining spatial analysis, ecology, and data visualisation to communicate environmental change more effectively.
