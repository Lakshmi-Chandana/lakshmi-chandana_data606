# Capstone Data Science 606 (Proposal)

### Team Members:

Hari Chandana Datla

Lakshmi Chandana Shaik

# 500 cities: Local data for better health


## Issue of Interest

Health is a foremost important factor in the society. In the current fast living culture people are falling prey for chronic diseases. Unhealthy behaviors and eating habits are leading to chronic diseases like high blood pressures, diabetes and unhealthy cholestrol levels. Along with these people are also looking for ways to prevent these diseases by adopting much healthier choices. We have looked into the health data to explore more on the chronic diseases and how many people are into prevention and how many are taking action based on their health outcomes.

This kind of experiment helps in identifying the evolving health issues and this information and analysis could be accustomed to inform development and implementation of effective, targeted public health prevention activities.


## Issue Importance

By working on this health data, we can get to know the quality of public health in these practical situations. The analysis of this health data will be useful in understanding the trend of the chronic diseased and the unhealthy behaviors leading to them. Also this data will be useful for introducing new health policies and other preventive measures like digitalized health applications that can target people from a specific demography.


## Questions to be analysed


* The main objective is to analyze the unhealthy behaviors, health outcomes and prevention (3 variables) responsible for chronic diseases in major cities.
Which cities are more into prevention?
* Predicting cities which are more prone to chronic diseases
* Identifying which machine learning model gives the best accuracy score for our analysis.


## Data Procurement

The source for this data is CDC(Centers for Disease Control and Prevention), Division of Population Health, Epidemiology and Surveillance Branch and this project of making this dataset was funded by the Robert Wood Johnson Foundation (RWJF) in conjunction with the CDC Foundation. Data sources used to generate these measures include Behavioral Risk Factor Surveillance System (BRFSS) data (2016, 2015), Census Bureau 2010 census population data, and American Community Survey (ACS) 2012-2016, 2011-2015 estimates.

Link for the [Dataset](https://chronicdata.cdc.gov/500-Cities-Places/500-Cities-Local-Data-for-Better-Health-2018-relea/rja3-32tc)

* Dataset contains information from the years 2015 and 2016.
* This dataset was first created on December 4th, 2019 and this was last updated on December 5th, 2019.
* Size of dataset is 224.276 MB.
* The dataset has 810k rows and 24 columns.
* Dataset has information from 500 cities from the US which helps in bringing out data for better health.
* Attributes of the dataset are like states, city names, geographic level, datasource category, unique ID, measure, data value, low confidence limit, high confidence limit, population count, geolocation and short question text.
* Each row represents an estimate from various cities with a unique ID and on what measures it was taken with a measureID as well from the years 2015 and 2016. It was provided with a geographical location and geographical level like US or City or Census tract, from where the estimate was collected.
* In this dataset, we have found that the measures that cause chronic diseases were categorized into three major grades like Unhealthy behaviors, Health outcomes and Preventions. These brands are labelled under the column named ***Category***. This ***Category*** column has these three sections of measures that cause chronic diseases.



Below is a pie chart that exhibits the break down of those categories.

![image](https://user-images.githubusercontent.com/78044715/172450433-1e1c3af6-eff8-48e2-83c3-0584601a14af.png)


## Unit of Analysis

Our unit of analysis would be category which comprises of unhealthy behaviors, health outcomes and prevention. For example, we will analyse the rate of unhealthy behaviours in a particular state and the rate of their usage of preventive measures.


## What variables/measures do you plan to use in your analysis (variables should be tied to the questions in #3)?

We plan to use cities, states, measure and measureID in analyzing the category. The target variable that we will be predicting is ***Category***.


## What kinds of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?

* Logistic regression
* Decision tree
* Finding best paramaters using grid search
* Cross validation
* KNN classifier


## How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?

We are planning the metrics such as recall, accuracy, f-1 score and confusion matrix.


## What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practicle applications, etc)?

We will visualize the data with the use of Tableau. Further more, we are also contemplating in using plotly to develop the health status of the population in major cities.


## Work Distribution

### Hari Chandana Datla

* Data cleansing and preprocessing
* Logistic Regression
* KNN classifier
* Grid search
* Metrics


### Lakshmi Chandana Shaik

* Data EDA
* Decision Tree
* Cross Validation
* Data Visualization
