## Geospatial analysis of Thomas Fire Burn Area (2017)

![Image of wildfire on coast captured by USGS.](https://images.unsplash.com/photo-1722083854858-79fb7ea85380?q=80&w=2680&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)


**About**: 

This purpose of this repository is to analyze the air quality index (AQI) of the Thomas Fire burn area over time and to demonstrate how to use remote sensing data to identify burn areas. We'll use the Thomas Fire that occurred in Santa Barbara County, California in 2017 as a case study.

**Highlights**:
This repository demonstrates the following:

**Repository Structure:**

This repository contains 3 notebooks: 

`thomas-fire-aqi.ipynb` - Time series analysis of AQI around Thomas Fire burn area

`thomas-fire-perimeter.ipynb` - Used to obtain Thomas Fire Polygon 

`thomas-fire-false-color-image.ipynb` - Used to generate true and false color images to compare to vector data

The repository has the following structure:

```
eds220-hwk4
│   README.md
└───blog-post_files
│   blog-post.ipynb
│   blog-post.html
│   blog-post.pdf
└───notebooks
    │   thomas-fire-aqi.ipynb 
    │   thomas-fire-perimeter.ipynb 
    │   thomas-fire-false-color-image.ipynb
|   .gitignore
└───data
    │   landsat8-2018-01-26-sb-simplified.nc
    │   California_Fire_Perimeters
```

**Data**

This repository utilizes the following datasets:

1) **Air Quality Index (AQI)**: This data was retrieved from the [US Environmental Protection Agency](https://www.epa.gov). It contains air quality data through the US, and we subset this dataset for Santa Barbara County.

2) **Thomas Fire Perimeter Data**: This data was retrieved from US governement's data catalogue. Original Source:[California Fire Perimeter Data](https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436) It contains spatial data regarding fire perimeters and associated metadata. We subset this data for the 2017 Thomas Fire.

3) **Landsat Data**: This data was retrieved from the Microsoft Planetary Computer Data Catalogue, pre-processed by Dr. Carmen Galaz-Garcia, and stored on the MEDS computational server.  Original Source: [Microsoft Planetary Computer Data Catalogue](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2)


**References**

Microsoft Planetary Computer. (Access Date: November 2024). Landsat Collection 2, Level-2 [Dataset]. U.S. Geological Survey (USGS). https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

Riebeek, H. (2014, March 4). Why is that forest red and that cloud blue? NASA Earth Observatory. https://earthobservatory.nasa.gov/features/FalseColor

U.S. Geological Survey. (2021, November 12). Common Landsat band combinations [Image]. U.S. Department of the Interior. https://www.usgs.gov/media/images/common-landsat-band-combinations

U.S. Geological Survey. (Access Date: November 2024). California fire perimeters (all) [Dataset]. Data.gov. https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436


**Acnknowledgements**

This repository was created as an assignment for [EDS 220: Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/) at the [UCSB Bren School of Environmental Science & Management](https://bren.ucsb.edu/). This course is led by Dr. Carmen Galaz-Garcia and Annie Adams. 
