# Proyecto_Final_Riesgo_Vial_Relativo
# Geospatial Analysis of Relative Road Risk in Spanish Road Corridors

## Overview

This project presents a geospatial analysis of relative road risk across the main road corridors connecting Madrid with coastal areas in Spain. The study focuses on comparing different corridors using traffic accident data, road length, traffic exposure, and traffic control devices.

The main goal is to identify which corridors present the highest relative road risk and to detect specific road segments where accidents are spatially concentrated.

## Project Objective

The objective of this project is to analyse and compare road safety risk across several major Spanish corridors, considering:

* Traffic accidents with victims
* Average daily traffic intensity
* Road length
* Speed cameras, traffic cameras and information panels
* Spatial distribution of high-risk segments

Instead of relying only on the total number of accidents, the project uses normalized indicators to obtain a fairer comparison between corridors with different traffic volumes and lengths.

## Methodology

The analysis combines geospatial data processing, statistical indicators and spatial autocorrelation techniques.

The main indicators calculated include:

* Accidents per 100 km
* Victims per 100 km
* Accidents per million vehicle-kilometres
* Victims per million vehicle-kilometres
* Traffic control devices per 100 km

A segment-level analysis is also carried out to identify local concentrations of road risk. Global Moran’s I and Local Moran’s I are applied to evaluate spatial autocorrelation and detect high-risk clusters.

## Main Results

The results show that the Madrid–Northeast corridor presents the highest relative road risk when considering both road length and traffic exposure.

The analysis also identifies specific high-risk segments, especially in the Madrid–Levante and Madrid–Northeast corridors. The spatial autocorrelation analysis shows a positive Moran’s I value, indicating that some high-risk road segments tend to be located near other high-risk segments.

## Tools and Technologies

* R
* sf
* dplyr
* ggplot2
* spdep
* rgeoda
* GeoDa
* Geospatial data analysis
* Spatial autocorrelation

## Report

The full project report is available here:

[View PDF report](Proyecto_final_Iván_Sánchez_Huesca.pdf)

## Academic Result

This project received a final grade of 9.5/10.

## Author

Iván Sánchez Huesca


