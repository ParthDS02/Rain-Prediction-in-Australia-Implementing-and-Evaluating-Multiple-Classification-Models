## Project Overview

This project was completed as part of the Honors portion of the **IBM Machine Learning with Python course on Coursera**. The goal of the project was to build a classifier capable of predicting whether there will be rain the following day, based on historical weather data.

## Coursera Certification

I have completed the **IBM Machine Learning with Python** course on Coursera. You can view my certification below:

[View Certificate](https://www.coursera.org/account/accomplishments/verify/PXXD5XJ8YNJW)

### Dataset

The dataset used for this project was sourced from the Australian Government's Bureau of Meteorology. It contains daily weather observations from 2008 to 2017. The dataset includes several weather-related features such as temperature, rainfall, humidity, wind speed, and more, along with the target variable, **RainTomorrow**, which indicates whether it will rain the next day.

You can access the dataset from the [Bureau of Meteorology](http://www.bom.gov.au/climate/dwo/) or from the Rattle repository [here](https://bitbucket.org/kayontoga/rattle/src/master/data/weatherAUS.RData).

### Key Features

The dataset contains the following columns:

| **Field**        | **Description**                                       | **Unit**         | **Type**   |
|------------------|-------------------------------------------------------|------------------|------------|
| Date             | Date of the observation                               | YYYY-MM-DD       | object     |
| Location         | Location of the observation                           | Location         | object     |
| MinTemp          | Minimum temperature                                  | Celsius          | float      |
| MaxTemp          | Maximum temperature                                  | Celsius          | float      |
| Rainfall         | Amount of rainfall                                   | Millimeters      | float      |
| Evaporation      | Amount of evaporation                                | Millimeters      | float      |
| Sunshine         | Amount of sunshine                                   | Hours            | float      |
| WindGustDir      | Direction of the strongest wind gust                 | Compass Points   | object     |
| WindGustSpeed    | Speed of the strongest wind gust                     | Kilometers/Hour  | float      |
| WindDir9am       | Wind direction before 9am                            | Compass Points   | object     |
| WindDir3pm       | Wind direction before 3pm                            | Compass Points   | object     |
| WindSpeed9am     | Wind speed before 9am                                | Kilometers/Hour  | float      |
| WindSpeed3pm     | Wind speed before 3pm                                | Kilometers/Hour  | float      |
| Humidity9am      | Humidity at 9am                                      | Percent          | float      |
| Humidity3pm      | Humidity at 3pm                                      | Percent          | float      |
| Pressure9am      | Atmospheric pressure at 9am                          | Hectopascal      | float      |
| Pressure3pm      | Atmospheric pressure at 3pm                          | Hectopascal      | float      |
| Cloud9am         | Fraction of the sky obscured by cloud at 9am         | Eighths          | float      |
| Cloud3pm         | Fraction of the sky obscured by cloud at 3pm         | Eighths          | float      |
| Temp9am          | Temperature at 9am                                   | Celsius          | float      |
| Temp3pm          | Temperature at 3pm                                   | Celsius          | float      |
| RainToday        | Whether it rained today                              | Yes/No           | object     |
| RainTomorrow     | Whether it will rain tomorrow                        | Yes/No           | float      |

### Methodology

In this project, I cleaned and preprocessed the dataset, then applied various machine learning classification algorithms to build a predictive model for rain prediction. The algorithms used include:

1. **Linear Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Decision Trees**
4. **Logistic Regression**
5. **Support Vector Machines (SVM)**

### Evaluation Metrics

The performance of the models was evaluated using the following metrics:

1. Accuracy Score
2. Jaccard Index
3. F1-Score
4. Log Loss
5. Mean Absolute Error (MAE)
6. Mean Squared Error (MSE)
7. R²-Score

<code> Parth B Mistry</code>
