# SP 2024 Crime Data Analysis

---
This project consists of two notebooks: ```ETL.ipynb``` and ```Data_Analysis.ipynb```. The former is in Portuguese, and the latter 
is in English. The ETL notebook, as the name suggests, is where I imported the data, performed a series of 
transformations, cleaned the data, and finally, loaded it into a Parquet file. In the Data_Analysis notebook, I 
conducted data analysis and modeling on the data in ```DCSP.parquet```.

There are two folders in this repository: one containing the data files (excluding shapefiles) and another folder named 
shapefiles with the shapefiles. The shapefile ```SP_Municipios_2022.zip``` contains data from all the municipalities of 
the brazilian state of São Paulo whereas ```DISTRITO_MUNICIPAL_SP_SMDU.zip``` contains the geographic information about
the districts of São Paulo City.

## Objective 

The main objective of this project was to work with a large dataset using sql and get familiar que duckdb, geopandas, 
and perform data analysis.