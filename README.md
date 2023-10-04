# Fair Market Value Prediction of Used Cars from CarGurus

In this notebook, we will use the dataset that we acquired by Web-Scraping the CarGurus used car listing website, to predict the fair market value prices for used cars. 

## Reading the dataset from the MongoDB Database 

We will start the project by reading the dataset from the local instance of the MongoDB database that we created from the scraped listings. We will save each document in the collections we created as a list of dictionaries and convert them into Pandas data frames to further conduct our analysis.

## Data Cleaning 

In this stage of our analysis, we will go over our dataset, check for the existence of null values, fill some of them up using our priori knowledge about cars, some using regression imputation, and drop some of the unnecessary columns and rows from our dataset that will not add much predictive power to our models that we will later use to predict the fair market value for used cars. We will also get rid of the outliers that could deceive our model and hurt its predictive power. 

## Exploratory Data Analysis 

Next, we will conduct exploratory data analysis on our dataset and see the relationship between our variable of interest a.k.a. price, and the available features in our dataset. We will visualise our dataset using different techniques such as ScatterPlots and Boxplots and check the Pearson correlation coefficient between variable of interest and some of the features, as well. 

## Model Building
Lastly, we will fit different regression models to our dataset including Lasso Regression, Ridge Regression, XGBoostRegressor and RandomForestRegressor to predict the fair market value of used cars. We will also evaluate In-Sample and Out-Of-Sample performance of our models to check for their predictive power, and if they are overfitting the data. 

