# SpaceX Falcon 9 First Stage Landing Prediction

## Introduction

With the advent of the commercial space age, companies like SpaceX have revolutionized space travel by making it more cost-effective and accessible. One of SpaceX's key innovations is the ability to reuse the first stage of their Falcon 9 rockets, significantly reducing the cost of launches. This project aims to develop a predictive model to determine the likelihood of the Falcon 9 first stage successfully landing. By accurately predicting these outcomes, we can estimate launch costs more effectively and provide competitive insights for new entrants in the space industry.

## Objective

The primary objective of this project is to employ data science and machine learning techniques to predict the successful landing of SpaceX Falcon 9's first stage. By analyzing historical launch data and developing a robust predictive model, we aim to assist Space Y, a new potential competitor in the space industry, in estimating launch costs and enhancing their competitive strategies against SpaceX.

### Example of Launch Outcomes

- **Unsuccessful Launch**: ![Unsuccessful launch](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/lab_v2/images/crash.gif)



- **Successful Launch**: ![Successful launch gif](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/lab_v2/images/landing_1.gif)
  
- **Unsuccessful Launch**: <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/lab_v2/images/crash.gif" width="300" alt="Unsuccessful launch">


## Project Overview

This project involves several key steps:

1. **Data Collection**:
   - Gathering data from an API.
2. **Web Scraping**:
   - Extracting additional data using Beautiful Soup.
3. **Data Wrangling**:
   - Cleaning and preparing data with Pandas.
4. **Data Analysis**:
   - Utilizing SQLite for data analysis.
5. **Exploratory Data Analysis (EDA)**:
   - Visualizing data patterns with Matplotlib and Seaborn.
6. **SpaceX Launch Records Dashboard**:
   - Analyzing launch records interactively using Plotly Dash.
7. **Interactive Map for Spacex Launch Locations**:
   -  Building an interactive map to analyze the launch site proximity with Folium.
8. **Predictive Modeling**:
   - Implementing and comparing four machine learning algorithms:
     - Logistic Regression
     - Support Vector Machine (SVM)
     - Decision Tree
     - K Nearest Neighbour (KNN)
   - Optimizing models using GridSearchCV.
     
## Project Files

- **Data Collection Notebook**: [Data Collection](Jupyter_Notebooks/1-data-collection-api.ipynb)
- **Web Scraping Notebook**: [Web Scraping](Jupyter_Notebooks/2-jupyter-labs-webscraping.ipynb)
- **Data Wrangling Notebook**: [Data Wrangling](Jupyter_Notebooks/3-data-wrangling.ipynb)
- **Data Analysis Notebook**: [Data Analysis](Jupyter_Notebooks/4-sql-coursera-sqllite.ipynb)
- **EDA Notebook**: [EDA](Jupyter_Notebooks/5-edadataviz.ipynb)
- **SpaceX Launch Records Dashboard**: [Dashboard](Jupyter_Notebooks/7-spacex-dash-app.py)
- **Interactive Map for Spacex Launch Locations**: [Folium Map](Jupyter_Notebooks/6-launch-site-location.ipynb)
- **Predictive Modeling Notebook**: [Predictive Modeling](Jupyter_Notebooks/8-machine-learning-prediction.ipynb)

## Conclusion

This project provides a comprehensive approach to collecting, analyzing, and predicting the successful landing of the SpaceX Falcon 9 first stage. The insights gained will be instrumental in estimating launch costs and formulating competitive strategies for Space Y in the burgeoning commercial space industry.

Results: All findings have been summarised in the Final pdf presentation
