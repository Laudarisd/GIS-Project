# Remote Sensing
This file includes concepts of Remote Sensing.

---


## Table of Contents

1. [Introduction](#introduction)







---


## Introduction

- Remote sensing involves collecting data about Earth's surface without physical contact.

- Example: Using a satelite to monitor deforestation in the amozon rainforest.

So in conclusion remote sensing is much much more than just setelite. It is a process to obtain the object iniformation without physical contacting the object. So, the data can be in following format

## Example of Remote sensing technologies 

- Setelite : Get data like 

- Drone: Get data like, useful for small area

- Autonomose car:

- X-ray taken in hospital


Add more example

Data received from such technology can be in 2D, 3D....


## Electomagnetic Spectrum
Based on classification of 
Electromagnetic Spectrum is ... and they are usefule for ..

It's sensor detect electromagnetic radiation(EMR). The spectrum includes:

- Visibile light(What human see)

- Infrared (used for temperature mapping)

- Microwave (used in RADAR)

### More detail in remote sensing methods/technologies

- OPTICAL : Explain with example

- LIDAR : Explain with example

- THERMAL: Explain with example
 
- MICROWAVE:

- Sonar


## Active vs. Passive Remote Sensing

- Passive : Captures natural radiation (e.g. Landsat uses sunlight to image Earth's surface)

- Active: Emits energy and measures the return signal (e.g. RADAR and LiDAR)
Explain  more about this


## Resolution

- Spatial resolution: Level of detail (e.g. Sentinel-2 has 10m resolution, showing features like large roads.)

Here 10 m resolution means ......

Further 30m resolution.


Usualluy data are in ....
give more example

### So what is high resolution

Explaiin more with example


## Applications of Remote Sensing

- Environemntal Monitoring: Mapping land use, detecting forest loss, and monitoring pollutions.
    - Example: Detecting oil spills in oceans using SAR iimagery.

- Urban Planning: Monitoring city growth  and infrastructure.
    - Example: High-resolutoin imagery to detect illegal constructions.


- Agriculture: Crop health monitoring using NDVI(Normalized Difference Vegetation Index)

    - Example: identifying drought-stressed areas in a wheat field.



## Data types

- Shape files - 

- Geodatabase - 

- GIS Mapping - 

- Coordinate System - 

-  3D Models - 

- ARCMAP - 

- Vector & Raster Data



## GIS Spatial DATA Integration

- GIS () combines remote sensing data with spatial data like road networks, elevation, and demographics.

- Example: Combining satelilite imagery with elevation data data to model flood risks



Expain more with GIS core part


## Image Processing and Analysis

- Adjust data to remove errors.

    - Atmospheric Correction: Removes haze caused by atmosphere.

    - Geometric correction: Aligns image to real-world coordinates

    - Example: Correcting an image of a city to align roads accurately with a map


## Classification

- Dividing an image into meaningful calsses(e.g. water, vegetation, urban)

- Supervised classification: 

- unsupervised classification: 

Example: Identifying forest vs. agricultural land using Random Forest


## Change Detection

- Compare images from different tiimes.

    - Examples: Analyzing glacier retreat by comparing 2000 and 2020 images.

## Spectral Indices

- Use combinations of spectral bands to highlight features.

    - NDVI(): (NIR - Red)/(NIR + Red) for vegetation health 

    Explain more 

    - NDWI: Water detection using (Green - NIR)/(Green + NIR)

    Explain more

## Programming and Tools

### Python Libraries

- Rasterio: Read/write raster files

- GDAL : Convert and process geospatial data

Exmaple: Use python to calculate NDVI for satelite image


### Software

- Google Earth(GEE): Coud-based analysis of satellite imagery. Supports file types extension...

- QGIS: Open-source GIS software for spatial analysis.


- ArcGIS: ....


## Mathematical and Statistical Knowledge
- Linear Algebra: Helps in image transformations.
    - Example: Using matrix operations to rotate an image.

- Statistics: For accuracy assessment of classification results.
    - Example: Calculating precision, recall, and overall accuracy for land cover maps.



## Current Trends
- AI/ML in Remote Sensing: Detecting buildings automatically using Convolutional Neural Networks (CNNs).

- SAR and High-Resolution Data: Extracting objects like roads or buildings using SAR backscatter data.


- Fusion of Data: Combining optical and SAR data to improve accuracy.

---

# Advanced Topics


## Expert Knowledge of Spectral Signature Extraction
- Spectral Signature: Unique reflectance pattern of objects in different wavelengths.

    Example: Healthy vegetation has a high NIR reflectance and low red reflectance.

- Application: Classifying land use types or identifying minerals.

    Example: Differentiating wheat from rice using spectral bands.

- Tools: ENVI, Google Earth Engine



## High-Resolution and SAR Object Extraction

- High-Resolution Imagery: Detect finer details like cars or small buildings.

- SAR (Synthetic Aperture Radar):
    - Active sensor useful in cloudy or nighttime conditions.

    - Measures backscatter to identify surface roughness.

    - Example: Detecting oil rigs in oceans.

- Object Extraction Techniques:
    - Edge detection algorithms.
    - ML models like YOLO for object detection.



## Spatial Data Integration/Fusion

- Data Fusion: Combining multiple datasets for comprehensive analysis.
    
    Example: Integrating LiDAR elevation data with Sentinel-2 imagery to map urban heat islands.

- Spatio-Temporal Modeling:
    
    Tracking changes over time and space.
    
    Example: Analyzing deforestation trends over decades.