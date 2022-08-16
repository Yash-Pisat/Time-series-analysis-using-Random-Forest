# Random Forest for Time series analysis
This project is a collaboration between me and Sneha khirwal.

## Analysis
The analysis is based on the data published by University of california (UCI). It contains data collected from car parks in Birmingham that are operated by NCP from Birmingham City Council. It provides Occupancy rates of the parking lot (8:00 to 16:30) from 2016/10/04 to 2016/12/19 for different system code number. The occupany for each system code number is different. 

The purpose of the analysis of this dataset is to build a model to predict occupancy rate of user specified system code number at a user specified date and time using Random Forest algorithm. Random forest is not a appropriate or the optimal algorithm to obtain the desired result in time series dataset but still we were able to obtain a decent accuracy using the same by doing some data analysis, pre-processing and preparation.

## The steps we follow are :
1. Data Understanding
2. Data Visualization
3. Data Preparation
4. Modelling
5. Hyperparameter tuning
6. Evaluation

## Contents of Repository
- ``Random Forest Time Series.py `` :   Python file with classifcation class utilised in index.ipynb
- ``READMEmd  ``         :   Markdown file with executive summay of project
- ``dataset.csv  ``      :   CSV file with data used for project
- ``Time Series Documentation.py  ``      :   Document for the code implemented
- ``index.ipynb   ``     :   Python Notebook containing main conent for project (code,visualisations,modelling,evaluation)
