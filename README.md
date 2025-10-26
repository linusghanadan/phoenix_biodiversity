## Geospatial Analysis of Biodiversity Loss

### Context
This project was completed for my Geospatial Analysis & Remote Sensing class, taken as part of my Master's program at UC Santa Barbara. Provided with data and questions, I carried out this analysis using appropriate geospatial analysis techniques.

### Summary of Analysis
Fetched grid-cell data on Biodiversity Intactness Index (BII) scores from Microsoft data catalog. Clipped rasters of 2017 and 2020 BII scores with polygon shapefile of Phoenix subdivision. Created heatmap of 2020 BII scores in Phoenix, highlighting areas that had decreased below 0.75 threshold since 2017 study.

### Highlights of Analysis
- Add basemap with Contextily
- Fetch items from Microsoft Planetary Computer (MPC) catalog using search criteria
- Clip biodiversity raster based on polygon from shapefile of Arizona subdivisions
- Calculate percent of area with BII>0.75 in 2017 and 2020
- Visualize 2020 biodiversity and changes from 2017

### Dataset Descriptions
1. The primary dataset used in this analysis estimates terrestrial Biodiversity Intactness as a 100-meter gridded maps for years 2017 to 2020. The data contained in the dataset comes from Impact Observatory and Vizzuality, and they generated the data using a database of spatially referenced observations of biodiversity across 32,000 sites and over 750 studies. The data was accessed from the Microsoft Planetary Computer (MPC) catalog
2. A dataset from the U.S. Census Bureau was used to clip biodiversity raster.

### Data References
1. Impact Observatory & Vizzuality. 2022. “Biodiversity Intactness.” Accessed via Microsoft Planetary Computer (MPC) Catalog. https://planetarycomputer.microsoft.com/dataset/io-biodiversity#overview.
2. U.S. Census Bureau. 2022. "2022 TIGER/Line Shapefiles: County Subdivision". https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions
