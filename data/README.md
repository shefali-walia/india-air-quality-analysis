# Data

This folder contains the processed dataset used for the exploratory analysis and machine learning stages of the project.

## `aqi_cleaned.csv`

`aqi_cleaned.csv` is a processed subset of the original India Air Quality dataset.

The original dataset was obtained from **Kaggle** and is not included in this repository. The processed dataset is included to make the analysis and modelling stages reproducible without committing the full source dataset.

The cleaning and preprocessing steps included:

- Selecting the relevant columns
- Removing observations with missing AQI values
- Filling missing PM2.5 values using the mean
- Converting `Date` to datetime
- Extracting the month number
- Creating the `Season` feature

The file is used as the input for:

- Exploratory Data Analysis
- Data Visualization
- Feature Engineering
- AQI Regression
- AQI Classification
- Model Evaluation

## Note

The processed dataset is a derived file and should not be considered the original source dataset.

The original Kaggle dataset is excluded from the repository through `.gitignore`.