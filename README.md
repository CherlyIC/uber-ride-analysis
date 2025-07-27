Author: Imfurankunda Cherly

# uber-ride-analysis
## Introduction

This project presents a comprehensive data analysis of Uber rides using Power BI. The main objective is to uncover insights related to fare patterns, ride frequency, and spatial distributions within a given time period. The project aims to demonstrate data cleaning, visualization, and dashboarding capabilities as part of a data analyst skillset.

## Objectives

- Understand fare amount distributions and factors affecting them
- Analyze ride frequency by pickup and dropoff locations
- Identify trends over time (date, hours,mounth,...)
- Build an interactive dashboard to communicate insights effectively


## Data collection

the dataset used in this project was sourced from here Uber Fares Dataset (Kaggle), it was containing information such us:
- Pickup and dropoff coordinates
- Fare amount
- Timestamps
- Distance (calculated using haversine formula)

we have also done the data cleaning and preparation, using python(jupyter notebook) the following step was performed:

- Removed null values and invalid coordinates
- Calculated the distance between pickup and dropoff points 
- Removed outliers (extremely high or low fares and distances)
- Exported a cleaned version of the dataset to `cleaned_uber_data` for Power BI


the image of the dashboard
<img width="1195" height="717" alt="image" src="https://github.com/user-attachments/assets/0f18443a-3b3e-4452-80bb-c1dda7fc2b2a" />


You can access the final project dashboard by clicking on this link:https://drive.google.com/file/d/1kK08nWqsbE5MkMRctJPj3YI-Es3OMJPn/view?usp=drive_link



  



