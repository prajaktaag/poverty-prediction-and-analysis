# Poverty Prediction
Predict which families in Latin America needs a social welfare assitance. Dataset can be downloaded [here](https://www.kaggle.com/c/costa-rican-household-poverty-prediction/data)

## Description 
This is a kaggle competition. The Inter-American is asking for help with income qualification for some of the world's poorest families. The main task is to find the which households needs a social welfare assistance. 

In Latin America, one popular method uses an algorithm to verify income qualification. It’s called the Proxy Means Test (or PMT). To improve on PMT, the IDB (the largest source of development financing for Latin America and the Caribbean) believe that new methods beyond traditional econometrics, based on a dataset of Costa Rican household characteristics, might help improve PMT’s performance.
This problem can be extended to different countries beyond Costa-Rica as many countries face this same problem of inaccurately assessing social need. 

## Requirments
- Python 3.7
- Sklearn (0.19.1)
- Pandas (0.23) and Numpy (1.15)
- Matplotlib (2.2.2) and Seaborn Library (0.90) for visualization
- XGboost (0.70) and LightGBM ()
- Anaconda Python distribution (0.80)
- Jupyter Notebook

## Dataset 

### Core Dataset features 

- **Id** - a unique identifier for each row.

- **Target** - the target is an ordinal variable indicating groups of income levels.   
    1 = extreme poverty   
    2 = moderate poverty   
    3 = vulnerable households   
    4 = non vulnerable households  

- **idhogar** - this is a unique identifier for each household. This can be used to create household-wide features, etc. All rows in a given household will have a matching value for this identifier.
parentesco1 - indicates if this person is the head of the household.

This data contains 142 total columns. Detailed description of dataset can be found here [here](https://www.kaggle.com/c/costa-rican-household-poverty-prediction/data)

**Additionally, multiple people can be part of a single household but only predictions for heads of household are scored.**

## Data Preprocessing and Machine Learning 
### Exploratory Data Analysis
### Feature Engineering
### Building Models
### Model Evaluation




