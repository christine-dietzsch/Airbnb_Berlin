# Airbnb_Berlin
A data analysis portrait using Python and Tableau Public on open source data: Inside Airbnb for the city Berlin. Data is from June 2023.

# OBJECTIVES
Berlin faces a severe housing shortage. According to a 2020 report by the Berlin Senate, approximately 20,000 apartments were permanently removed from the rental market in favor of tourist rentals. This has driven up rental prices and deprived locals of much-needed housing. This is a portrait of Airbnb in Berlin: How many listings are up for rental? What are the prices? Who are the hosts and are they all locals, setting up 1 or 2 properties for rent?

# DATA
The data consists of csv files and a geoJOSN shapefile. For the time series analysis, the data is an xlsx-file.
## Source: The data is from http://insideairbnb.com/get-the-data/ . 
I downloaded the airbnb Berlin data sets. The data is from June 2023 and originally consists of 7 data files. It gives several information, like listings in geographic areas of a city, pricings, reviews, and others.
## Authors: ‘Inside Airbnb’ is an activist investigatory/watchdog website, launched by Murray Cox in 2016. 
It reports and visualizes scraped data on the property rental marketplace company Airbnb, focusing on highlighting illegal renting on the site and gentrification caused by landlords buying properties to rent on Airbnb. (source: https://en.wikipedia.org/wiki/Inside_Airbnb)
## Collection method: the data is web-scraped. 
## Additional data:
For the time series analysis, I connected with the platform quandl with consumer price data. Find it here: https://data.nasdaq.com/data/RATEINF/CPI_DEU-consumer-price-index-germany

# TOOLS
Language: Python
Libraries: pandas, numpy, os, matplotlib, seaborn, scipy, quandl, statsmodels, sklearn, pylab, folium, 
Software: Jupyter Notebooks, Excel

#  SKILLS DEMONSTRATED
Cleaning and aggregating data: Data checks for any inconsictencies, arious statistics and aggregations.  
Deriving new variables: such as region of hosts, price categories.  
correlation analysis using heatmaps, scatterplots.  
Geospatial analysis with Chorpleth map on prices over Berlin districts.  
regression analysis with training and testing models to analyze price correlations.  
cluster analysis: preparing the data, standardizing with the z-score, finding number of clusters comparing ellbow-technique and silhouette method, clustering with k-means, visualising and interpreting the clusters.  
Visualizations Using bar charts, line-charts, histograms, scatterplots and pie charts to simplify data and present findings.  
Presenting insights and recommendations via a Tableau Storyboard on Tableau Public: https://public.tableau.com/app/profile/christine.dietzsch/viz/InsideAirbnbBerlin/Story1  
