# Global-deaths-other-than-diseases
## Objectives
To build an interactive dashboard that will visually showcase well-curated results of an
advanced exploratory analysis conducted in Python.
## Project and Data sources 
This project involves four datasets that are merged to study global deaths due 
to causes other than diseases. The secondary datasets are merged with the primary dataset 
to analyze the deaths for each country across various years based on the GDP value
and income group of each country. The fourth supplementary dataset groups each country 
into a region and sub-region and is added for analysis purposes by region.
### I.	Primary Dataset:  Global cause of deaths other than diseases
Data source: This dataset was part of the Global Burden of Disease Study 2017 project (https://ghdx.healthdata.org/gbd-2017) coordinated by the Institute of Health Metrics and Evaluation(IHME), University of Washington, Seattle.  The dataset contains the number of deaths within a country each year, along with the causes of deaths such as conflict and terrorism, famine, pandemics, natural disasters, and other injuries for various countries. The data for the different causes of death have been assimilated from IHME individual files into a single table and are available on Kaggle (https://www.kaggle.com/datasets/tahminashoaib86/global-cause-of-the-deaths-other-than-diseases).  This dataset also includes the GDP (Gross Domestic Product) data for each country and by year. These are global causes of death other than diseases.
### II.	Secondary Dataset 1: GDP (Gross Domestic Product) Data 
Data source: This dataset was retrieved from the World Bank Group's Open Data and is available on Kaggle at https://www.kaggle.com/datasets/sazidthe1/world-gdp-data.  The World Bank Group is a renowned institution for global economic data. This secondary dataset provides the GDP value for each country by year. 
### III.	Secondary Dataset 2: World Data Bank data by Country, Year and Income Group
Data source: This dataset is sourced from The World Bank Data: https://datacatalogfiles.worldbank.org/ddh-published/0037712/DR0090754/OGHIST.xlsx. The World Bank Group is a renowned institution for global economic data. This secondary dataset provides the income group for each country by year. The dataset contains data in a crosstab format and for analysis purposes, it has been changed to a table format using Excel Power Query editor.
### IV.	Supplementary Dataset: United Nations Statistics Division (UNSD) Data for each country with regions, and sub-regions.
Data source: This dataset is sourced from the UNSD data: https://unstats.un.org/unsd/methodology/m49/overview. 
The UNSD data has regional, sub-regional, and intermediate region listed for each country. For analysis purposes, the derived dataset here has only the regions and sub-regions listed for each country. 
## Tools
##### Language: Python
##### Libraries: Pandas, Numpy, Seaborn, Matplotlib, Scipy, Quandl, Folium, json, geopy, sklearn, statsmodels.api
##### Software: Jupiter Notebook, Excel, Tableau
## Skills Demonstrated
### Cleaning data
Removed duplicates, resolved missing values, and addressed mixed or incorrect data types.
### Merging data
Selected and prepared data for merging, and confirmed successful merge from four different datasets. 
### Exploratory analysis using PYTHON
#### Performed initial exploratory analysis by using Matplotlib and Seaborn to create scatterplots, correlation heatmaps, pair plots, categorical plots, and strip plots.  
#### Defined research questions and two different hypotheses.
### Addressing the defined questions/hypotheses using advanced analytical techniques. 
#### Geospatial analysis using Folium with a shapefile
##### Data cleaning, resolved missing values using interpolation and extrapolation.
##### Used shapefile (world_countries.json) to generate spatial maps with Folium.
#### Regression analysis
##### Data preparation for regression analysis, Performed linear regression to analyze both hypotheses but learned that the model does not fit the data in both cases. Need to analyze the data with other models.
#### Cluster analysis 
##### Used k-means clustering, and found inconsistencies within clusters. Other anomaly detection techniques could be used to understand the characteristics of each cluster.
#### Time-series analysis 
##### Time series decomposition to analyze the trend, seasonality, cycle, and noise in the data, Testing for Stationarity(using the Dickey-Fuller test) and Autocorrelation.
##### Tried forecasting using the ARIMA model but received errors. Need to try another model like Prophet for a successful forecast.
### Visualizations
#### Visualizations were created in Tableau. The link to the storyboard can be found here: [Global deaths other than diseases](https://public.tableau.com/app/profile/rangamani.varadachary/viz/Exercise6_7GlobalDeathsotherthandiseasesStoryboard/GlobaldeathsStoryboard?publish=yes)

