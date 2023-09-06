# DataScience_House-Price-Prediction
## Description
Everyone who wants to buy a house has different criteria. Number of rooms, number of bathrooms, distance to the city center, ease of transportation, etc.  How does the combination of all these criteria determine the price of a house?
This project aims to create a house price prediction model with 79 explanatory variables for residential homes in Ames, Iowa.  In the project, the data was prepared for the machine learning model through data analysis and variable engineering. Then different machine learning models were tested and the best one was selected. 
## Content
Since the dataset is from a kaggle competition, there are two different csv files, train and test. In the test dataset, house prices are left blank and you are expected to predict these values.
## Columns
You can use this link to examine the data.
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview/evaluation
## Flow
- The data was uploaded and generally analyzed.
- Categorical, numeric columns captured. Also hierarchical and non-hierarchical columns were identified for encoding   operations.
- Categorical and numerical variables were analyzed.
- Categorical variables were analyzed according to the target variable.
- Outlier analysis was performed. Outliers were replaced with upper and lower limits by suppression.
- Columns with missing values were captured. The problem was solved with different strategies according to the rate of missing values.
- Categorical columns in the hierarchical structure were encoded according to their hierarchy.
- Rare value analysis was used to combine underrepresented classes of categorical variables.
- Various new columns have been added through feature engineering.
- Label endocing was applied to binary variables.
- One-hot encoding was applied to non-hierarchical and multi-class categorical variables.
- Standardization was applied to numeric variables. Logarithmic transformation was also applied to the target variable.
- Test and train data at the beginning of the study were separated. 
- Dependent and independent variables were created over the train data.
- Models were built with different algorithms for model selection.
- The Light GBM algorithm was chosen and with it the model was built and hyperparameter optimization was performed.
- We looked at the importance of features. 
- Finally, prediction data was generated.
