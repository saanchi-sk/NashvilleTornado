# Nashville Tornado Analysis
This notebook explores and analyzes tornado-related data in the Nashville area using Python. It includes data cleaning, exploratory visualizations, and insights on patterns of tornado occurrences and damage.

## How to Run
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run `Nash_Tornado.ipynb`

**Data**

The tornado data was gathered from the NOAA website, the damage data was from a previous site visit from the fulcrum app and the county and census shape files were taken from fata.gov.in.

The damage data was obtained by a webscapper, since i did not have access to it directly. I saved the csv from the webscaper and have implemented that directly in this notebook.


**Libraries used**

The libraries used to run this code are:
1. [GeoPandas](https://geopandas.org/en/stable/)  
2. [OpenStreetMap](https://osmnx.readthedocs.io/en/stable/)
3. [Contextily](https://contextily.readthedocs.io/en/latest/)
4. [Census Data](https://pypi.org/project/cenpy/0.9.1/)
5. [HDBSCAN](https://hdbscan.readthedocs.io/en/latest/how_hdbscan_works.html)
6. [Matplotlit](https://matplotlib.org/)
7. [NumPy](https://numpy.org/)
8. [OSMnx](https://osmnx.readthedocs.io/en/stable/osmnx.html)
9. [Xarray](https://docs.xarray.dev/en/stable/)
10. [Pandas](https://pandas.pydata.org/)

