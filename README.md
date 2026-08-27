# GEOG5990Mresit
Analysis of the relationship between Airbnb listings and Access to Healthy Assets and Hazards (AHAH) in Bristol.
## Project Background
This project investigates the relationship between the number of Airbnb listings in different areas of Bristol and the local environmental characteristics. The study utilizes the Airbnb listings data of Bristol and the AHAH (Access to Healthy Assets and Hazards) data. It analyzes the relationship between the number of Airbnb listings and various environmental indicators in AHAH. The study employs Spearman correlation analysis and presents the main results through a map and a non-spatial chart.
## Data
airbnb_data_bristol.csv: Airbnb listings data in Bristol (GEOG5990M Final Project Resit).

bristol_ahah_index.geojson: AHAH data for Bristol LSOAs (GeoDS) https://data.geods.ac.uk/dataset/access-to-healthy-assets-hazards-ahah

GEOG5990M_Final_Project_Resit.PDF:Main Notebook.

GEOG5990M_Final_Project_Resit.ipynb:PDF version of the notebook.

README :this

## how to run
Operating environment: Jupyter Notebook or Google Colab.
Required libraries: pandas, geopandas, seaborn, matplotlib
Download all files into the same floder
Open GEOG5990M_Final_Project_Resit.ipynb
Run all cells
## Code Explanation
1. Import the required Python libraries for the analysis.

2. Conduct a preliminary exploration of the two datasets and count the number of Airbnb listings in each LSOA.

3. Connect the Airbnb listings count with the AHAH data using LSOA11CD. LSOAs without Airbnb listings will have their property count set to 0.

4.Spearman rank correlation 

 Use Spearman rank correlation to analyze the relationship between the number of Airbnb listings and the comprehensive indicators of AHAH.

 Use Spearman rank correlation to analyze the relationship between the number of Airbnb listings and the four AHAH domains.

 Use Spearman rank correlation to analyze the relationship between the number of Airbnb listings and the four indicators in the Retail Environment.

5. Finally, create two visual graphs. The spatial graph uses a hierarchical color map to display the number of Airbnb listings in each LSOA of Bristol. The non-spatial graph uses a horizontal bar chart to show the Spearman correlation coefficient between the number of Airbnblistings and the four Retail Environment indicators.
## Acknowledgements
Thank you to the teaching team of GEOG5990M
