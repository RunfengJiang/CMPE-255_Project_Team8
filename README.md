# CMPE-255_Project_Team8
## Introduction
Abstract—COVID-19 is a contagious disease which is caused by a severe acute respiratory syndrome coronavirus 2(SARS-CoV-2) and is the reason for millions of deaths around the globe. This is no doubt one of the biggest pandemics the world has ever seen. This paper aims to study the effects of various vaccines on patients and their progress. Even though this paper also includes various datasets, it primarily studies the effects of the vaccine in California, U.S. The data starts from the 5th of January 2020 to the 9th of March 2022. The dataset would be expanded in the future for better analysis and results. It also includes the various steps involved in data mining which is pre-processing, encoding, scaling the data, and building an algorithm that would predict the best results for the datasets.
Keywords—COVID-19, Vaccine, Data Mining, Trend Analysis

## Data
- All Data underpath: https://github.com/RunfengJiang/CMPE-255_Project_Team8/tree/main/data
- Dirty Data: https://github.com/RunfengJiang/CMPE-255_Project_Team8/blob/main/data/Vaccine_Progress_Dashboard_Data.csv
- Preprocessed Data: https://github.com/RunfengJiang/CMPE-255_Project_Team8/blob/main/data/vacc_prog_clean.csv

We are using Preprocessed as our data use for the model

## Data Preprocess
### Handling the None value data
- If the dataset has multiple rows with multiple “NaN” values missing. In this case, dropping those rows would be the best solution
- If the dataset has a feature with multiple “NaNs”, then there could be multiple solutions to it such as replacing them with a completely new value, replacing them 
- with the most occurring value, replacing them with zeroes or with the mean or median values.
### Data Encoding
- Nominal Variable where the values have no relationship between themselves i.e., categorical variables.
- Ordinal variable where the values have a ranked ordering between the values.
### Data Scaling
- Standardization data
- MinMaxScaling data

## Training Model
- Support Vector Machine
- Neural Network
- Decision Trees
- K Nearest Neighbor

