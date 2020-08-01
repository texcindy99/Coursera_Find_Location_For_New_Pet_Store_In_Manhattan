### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3. However the notebook contains code to acquire venue data from [Foursqucare](https://foursquare.com/), for which you need to sign up an account and input your credentials in the notebook. 

Note that if you can't see the folium map shown properly when you run the notebook in online environment like IBM Cognitive Class, you may want to switch your web browser to google chrome.

## Project Motivation <a name="motivation"></a>

This is Coursera data science capstone project: find the best neighborhood to open a new pet store in Manhattan. I was interested in using venue information of Manhattan neighborhoods together with neighborhood retail and apartment rental price data to better understand:

1. Which venue information in Manhattan neighborhoods are related to pet stores?
2. What are the relationship between venue information and pet store?
3. How to predict the number of potential new pet store in each neighborhood?
4. If Manhattan neighborhoods are grouped into clusters using k-means based on pet store related features, does it
   validate the prediction results?

## File Descriptions <a name="files"></a>

There is one notebook available here to showcase work related to the above questions. The notebook is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

There are two data files used in the notebook. "Manhattan_Retail_Rental_Price.csv" is the wrangled data file for Manhattan neighborhood retail rental price. The raw data can be found [here](https://www.rebny.com/content/dam/rebny/Documents/PDF/News/Research/Retail%20Reports/2019_Spring_ManhattanRetailReport.pdf). "Manhattan_Apartment_Rental_Price.csv" is the wrangled data file for Manhattan neighborhood apartment rental price. The raw data can be found  [here](https://www.rentcafe.com/average-rent-market-trends/us/ny/manhattan/).

The Manhattan venue data can be aquired from [Foursquare](https://foursquare.com/) with valid user account.

## Results <a name="results"></a>

The code used ridge regression model to predict pet store number in each Manhattan neighborhood with R2-score at 0.68.  Morningside Heights is the final selection for openging the new pet store. K-means clustering results also validated the result. For more details, please check the report in this repo.

## Licensing, Authors, Acknowledgements <a name="licensing"></a>

Must give credit to Coursera, Foursquare, Rebny and Rentcafe for the data.  You can find the Licensing for the data and other descriptive information at [Coursera](https://www.coursera.org/professional-certificates/ibm-data-science), [Foursquare](https://foursquare.com/), [Rebny](https://www.rebny.com/content/dam/rebny/Documents/PDF/News/Research/Retail%20Reports/2019_Spring_ManhattanRetailReport.pdf) and [Rentcafe](https://www.rentcafe.com/average-rent-market-trends/us/ny/manhattan/). Otherwise, feel free to use the code here as you would like! 
