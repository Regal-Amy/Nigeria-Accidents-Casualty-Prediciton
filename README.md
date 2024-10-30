# Nigeria Road Accidents Casualty Prediction

## Project Overview
This project analyzes road accident data in Nigeria to identify patterns and predict future accident casualties. It utilizes data spanning over two years to understand the leading causes of accidents and their severity across different states. The ultimate goal is to develop a predictive model to help policymakers enhance road safety measures.

## Data Description
Datasets Used
Accident Cases Dataset:

Contains details of reported road accidents in Nigeria.
Key columns include:
STATE: Name of the state
FATAL: Number of fatal accidents
SERIOUS: Number of serious accidents
MINOR: Number of minor accidents
TOTAL CASES: Total number of reported accident cases
NUMBER INJURED: Total number of people injured
NUMBER KILLED: Total number of fatalities
TOTAL CASUALTY: Total number of casualties
PEOPLE INVOLVED: Total number of people involved in accidents
PERIOD: Quarter of the year
Accident Causes Dataset:

Contains detailed causes of road accidents categorized by state.
Key columns include:
SPV: Speeding
UPD: Unsafe parking/driving
TBT: Tire blowouts
MDV: Mechanical defects/failures
Additional columns for various causes of accidents

## Analysis
Key Findings
Total Reported Accidents: Ogun State has the highest number of total reported accident cases (approximately 1750) over two years, closely followed by the Federal Capital Territory (FCT) Abuja.
People Involved: Ogun State also has the highest number of people involved in accidents.
Leading Causes of Accidents: Speeding and mechanical defects are identified as the leading causes of accidents in Ogun State.
Accident Severity: FCT and Ogun have the highest accident severity based on the number of serious and fatal accidents reported.

## Visualizations
Several bar plots were generated to visualize the relationship between states and various metrics, such as:

Total cases reported by state
People involved in accidents by state
Causes of accidents by state
Severity of accidents by state

## Predictive Model
Model Selection
A Random Forest Regressor was chosen for predicting total casualties from the dataset. The model leverages various features related to accident causes and conditions.

## Model Implementation Steps
Data Preprocessing:

Merged datasets, handled missing values, and converted categorical features to numerical.
Scaled features using StandardScaler.
Train-Test Split:

The dataset was split into training (80%) and testing (20%) sets.

## Model Training:

Trained the Random Forest Regressor on the training set.
Evaluated model performance using metrics like Mean Squared Error (MSE) and R-squared (R²).

## Results
The model's performance indicates its effectiveness in predicting total casualties based on the input features. An accuracy of 78.9% was achieved

## Conclusion
The analysis of road accident data in Nigeria reveals critical insights into accident patterns and their causes. The predictive model provides a valuable tool for forecasting road safety issues, which can aid in decision-making for enhancing road safety measures in Nigeria.

## Future Work
Explore additional machine learning algorithms for comparison.
Implement hyperparameter tuning to optimize model performance.
Conduct more in-depth analysis on specific states or accident types
