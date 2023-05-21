# Crime-Prediction-Using-Machine-Learning
Performed binary classification to identify violent crimes in San Francisco using machine learning algorithms in R.

# Business Problem
San Francisco, California has long struggled with crime and safety concerns. In recent years, the city has seen an increase in violent crime, particularly in neighborhoods with high poverty rates. In order to address this issue, it is essential that law enforcement agencies use data to make more informed decisions about where to allocate resources and how to prevent crime. Police dispatchers receive 240 million calls per year, amounting to 7.6 calls every second. Since a majority of these calls have nothing to do with crime or violence, I thought it would be beneficial to be able to predict violent crimes to provide law enforcement with the means to make safer, data-supported decisions. I attempted to predict violent crimes using a variety of models that were trained and tested on the same data set.

**Why is this important?**
* By making accurate predictions, a model can allow police to utilize more resources for violent crimes / conserve resources for non-violent crimes.
* Allows for safer interactions between law enforcement and the public

# Data Used
The data used in this project was collected from [DataSF](https://datasf.org/opendata/), which is a site containing hundreds of data sets from the city of San Francisco. By navigating to the ‘Public Safety’ tab, I was able to find a crime data set that seemed to contain the most predictive variables for violent crimes. The data set I finally used is from 2016, due to its expansive number of records with minimal missing values.

# Approach
The biggest challenge was to identify the key feautures which are important to predict whether a crime incident will be violent or not. I first cleaned my data to remove redundant and insignificant predictors, and then performed **feature engineering** to create new variables to aid in prediction. Next, I performed **Exploratory Data Analysis** and tried to form a hypothesis based on intuition as well as the results from EDA. I then proceeded with my analysis by training the following three **machine learning models** to make predictions:
1. Decision Tree
2. Naive Bayes
3. Random Forest

Following the creation of these models, their performances were evaluated by a combination of testing accuracy, precision, and recall. The complete code and model comparisons are available in the repository.
