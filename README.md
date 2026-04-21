# Sentinel-2 Data Processing using openEO

## Overview
This project demonstrates how to download, process, and visualize Sentinel-2 satellite imagery using Python and the openEO API.

## Workflow
1. Connect to the Copernicus openEO backend  
2. Authenticate using Copernicus account  
3. Define spatial and temporal extent  
4. Load Sentinel-2 L2A dataset  
5. Apply cloud masking using SCL band  
6. Perform temporal reduction (median composite)  
7. Convert to reflectance values  
8. Save output as GeoTIFF  
9. Visualize RGB image in Python  

## Technologies Used
- Python  
- openEO  
- rioxarray  
- matplotlib  

## Author
Nazish Pervaiz
