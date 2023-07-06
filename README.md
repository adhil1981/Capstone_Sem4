
# Crime Prediction and Analysis - San Francisco

This project focuses on analyzing crime patterns in San Francisco using a dataset of criminal incidents from 2018 to 2023. The goal is to understand the spatiotemporal distribution of crime, identify prevalent types of crime, and examine the relationship between crime and factors like time, location, and weather conditions. By leveraging big data and machine learning techniques, the project aims to develop a predictive model to forecast the likelihood of future criminal activity in different areas of the city. The insights gained from this analysis can help law enforcement agencies and policymakers make data-driven decisions to enhance public safety in San Francisco


## Methodology

This project aims to analyze crime patterns in San Francisco using the San Francisco Crime Classification dataset from 2018 to 2023. The project involves data cleaning and preprocessing, exploratory data analysis (EDA) to identify patterns, and the development of machine learning models to predict the likelihood of crimes in different areas. The models will consider factors such as location, time, and day of the week. The project will conclude with findings and recommendations to enhance public safety in San Francisco
## EDA
The crime prediction model we're building uses a dataset with several variables, including:
Dates: A timestamp of the crime incident
Category: The category of the crime incident, which serves as the target variable for our model
Descript: A detailed description of the crime incident
DayOfWeek: The day of the week when the crime occurred
PdDistrict: The name of the police department district where the crime occurred
Resolution: The resolution of the crime incident
Address: The approximate street address of the crime incident
X: The longitude of the incident location
Y: The latitude of the incident location
By analysing and interpreting this data, we aim to create a model that can accurately predict the Location of crime that is likely to occur based on the time, location, and other relevant factors. This predictive model has the potential to help law enforcement agencies in San Francisco to more effectively prevent and respond to crimes.
This code reads in a dataset of crime incidents from a CSV file ('train.csv') using the Pandas library in Python. The dataset has 373,989 rows and 9 columns.

Crimes day wise
https://prnt.sc/T-oA8Yl9K9hP

crimes month wise
https://prnt.sc/1GTk5TsbEjaG

Crimes area wise
https://prnt.sc/DDg49Y6s_mol

## Files

The entire coding part is bifurcated into 3 sections.

1. Loading and EDA : Previous EDA works loading of the data is   present in this file. Description and graphical representation of the data is shown in this file.
2. Transformation: This file contains the necessary columns that must be modified in order to provide better insights. After the transformation was completed, it was saved in a new file called encoded.csv.
3. Model building and fitting:Creation of different models are done in this file to achieve the best score.
