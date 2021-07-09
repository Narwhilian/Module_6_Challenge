# Real_Estate_App

This application uses data aggregation, vizualization and geospatial analysis to find properties in San Francisco that are viable investments to use as rental properties.

---

## Technologies

This project uses the Python Programming language in a Jupyter Notebook as well as the following libraries
    
    - os
    - pandas
    - plotly
    - hvplot
    - pathlib
    - dotenv


---

## Installation Guide

To install you will want to pull the entire Real_Estate_App folder from github including its subfolder
    
    * Subfolder
        * Images (data folder)
        * Resources (data folder containing the data we import)
        * san_francisco_housing.ipynb (the jupyter notebook itseld)
        * ReadMe (This file)


---

## How it works

1) First the user will open the san_francisco_housing.ipynb notebook in the Real_Estate_App folder
2) The user will have to also ensure that they have a .env file containing an mapbox api key labled as MAPBOX_API_ACCESS_TOKEN
3) Then the user will simply run each cell in the notebook in order to get its output

    i) The app will load in the API access token form our environment file and then read the data from the CSV file into a dataframe
    
    ii) Then it will group the data by year and create a graph showing the number of housing units in San Francisco
    
      ![image](https://user-images.githubusercontent.com/84096312/125141713-a8816500-e0ca-11eb-9c1f-431c54b0dc89.png)

    
    iii) Then it will calculate and plot the average sale prices per square foot for all of San Francisco as well as for each neighborhood
    
      ![image](https://user-images.githubusercontent.com/84096312/125141772-d1a1f580-e0ca-11eb-928d-4b87d1e8ed6b.png)
      ![image](https://user-images.githubusercontent.com/84096312/125141784-d9619a00-e0ca-11eb-80e7-5fa01d2a0e62.png)

    
    iv) Then it will generate an interactive map of San Francisco neighborhoods to allow us to further analyze the rent in each neighborhood
    
      ![image](https://user-images.githubusercontent.com/84096312/125141852-00b86700-e0cb-11eb-87a3-6811bd1fc0d3.png)

    
    v) Finally it will summarize our findings for the San Francisco housing market in our data story


---

## Usage

Overall it should be a very simple application to use, all you need to do is open the financial_planning_tools.ipynb app in the Financial_Plan folder and run each cell in order

**It is crucial that the user has a .env file containing a mapbox api key (Your Key here)**

    MAPBOX_API_ACCESS_TOKEN = "<Your Key here>"


---

## Contributors

Colin Benjamin

Linkedin: [Colin Benjamin](https://www.linkedin.com/in/colinbenjamin/)
    
email: cbenjamin33@gmail.com

---

## License

MIT
