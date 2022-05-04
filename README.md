# Drone Data in Agricultural Research

In agricultural research, new forms of data are becoming available through Digital Data Capture (DDC). The technology starts with a drone equipped with high-resolution cameras and multispectral sensors. The drones scan crop fields to create ultra-high-definition images yielding incredible data insights. The most common role of drones in agriculture is as a remote sensing platform to assess and monitor crops, but emerging agricultural applications include precision distribution of agricultural chemicals and biological control agents, livestock health monitoring, and remote sampling.

This projects aims at extracting NDRE index and GRVI index from drone data for further analyses. 

## NDRE index
NDRE index is the Normalized Difference Red Edge, an approximation to chlorophyll content against soil background effects, which is calculated as: 
(NIR-Red Edge)/(NIR+Red Edge).

## GRVI index
GRVI index is the Green Red Vegetation Index, one of the spectral vegetation indices calculated from visible green and red reflectance. Therefore it's an indicator of  vegetation phenology, especially for leaf autumn coloring, but it has also been tested for measuring disturbance and ecosystem types (Motohka et al., 2010). It is calculated as: (ρgreen − ρred)/(ρgreen + ρred).

## Project information
For this project I imported and visualized drone based multispectral data in QGIS and extracted data values for areas of interest in both a manual, low throughput method and a more automated, high throughput method in conjunction with R scripts.

## Original data
The data I work with was not captured by me, nor do I own any credits for it. For more information on the original data please refer to:
Nelsen, T., & Lundy, M. (2021). Drone Data in Agricultural Research [GitHub repository]. 
https://github.com/Grain-Cropping-Systems-Lab/
