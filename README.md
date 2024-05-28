# Portfolio
In this repository, I'll be adding some of my data science projects over time under the pretense that I found the project itself interesting and am generally happy with how clean the code and commenting are.

## Project 1: Heatmap for Peak Foot Pressure Values
[notebook](https://github.com/MuellerPJ/MuellerPJ.github.io/blob/0a704907a47fde2b5e421d9da41f12edfafe5898/notebooks/Heatmap_Foot_Pressure.ipynb)  [nbviewer](https://nbviewer.org/github/MuellerPJ/MuellerPJ.github.io/blob/main/notebooks/Heatmap_Foot_Pressure.ipynb)<br>
As part of my master’s thesis, I created heatmaps of the average maximum pressure values of the foot during running across multiple subjects at the same speed and wearing the same shoes. This notebook demonstrates the process using one of the speed/shoe combinations. 
Key steps include:
* Dynamic Separator Detection
* Data Preprocessing with Pandas
* Interpolation with SciPy
* Data Visualization with Matplotlib

## Project 2.1: Exploratory Data Analysis of Crime Trends in Los Angeles
[notebook](https://github.com/MuellerPJ/MuellerPJ.github.io/blob/main/notebooks/EDA_Los_Angeles_Crime_Trends.ipynb) [nbviewer](https://nbviewer.org/github/MuellerPJ/MuellerPJ.github.io/blob/main/notebooks/EDA_Los_Angeles_Crime_Trends.ipynb) <br>
This project involves an exploratory data analysis of crime trends in Los Angeles. As the original file size exceeded GitHub's upload limit of 55mb, it was split into several parts. The analysis looked at various factors such as the month, the day of the week, the time of day, but also the city areas in order to identify noticeable trends by visualizing the data. The dataset used was obtained from [Kaggle](https://www.kaggle.com/datasets/sahityasetu/crime-data-in-los-angeles-2020-to-present). The additional geojson data used to define the boundaries of the different districts of the LAPD in the heatmap was obtained from [here](https://geohub.lacity.org/datasets/lahub::lapd-divisions/explore?location=34.017393%2C-118.410104%2C9.90). Key steps of the project include:
* Data Preprocessing with Pandas
* Data Visualization with Matplotlib and Seaborn
* Geospatial Visualization with Folium and Geopandas



## Project 2.2: Heatmap over Time - Monthly Crime
[notebook](https://github.com/MuellerPJ/MuellerPJ.github.io/blob/main/notebooks/Heatmap_over_Time_monthly.ipynb) [nbviewer](https://nbviewer.org/github/MuellerPJ/MuellerPJ.github.io/blob/main/notebooks/Heatmap_over_Time_monthly.ipynb) <br>
In this notebook, the initial steps from the previous notebook are repeated to arrive at the same data. The main focus here is to visualize the data as a heatmap over time, displaying the crime statistics for each month from 2020 to 2023.

## Project 2.3: Heatmap over Time - Hour of the Day
notebook<br>
