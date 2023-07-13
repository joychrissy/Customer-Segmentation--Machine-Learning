# Customer-Segmentation--Machine-Learning
This is an unsupervised machine learning project which is aimed at building a model that will identify and segment customers base on purchasing behaviour and similar characteristics to help develop targeted marketing campaigns, personalized product recommendation etc.
# Steps
1. library importation
2. Load and assess the dataset
4. perform data wrangling/ cleaning
5. perform feature engineering
6. Exploratory Data Analysis (EDA)
7. Machine learning modelling (using PCA and Clustering)
8. observations
# Library importation
Python libraries were imported for Data Analysis, Data visualization, plots and charts , scaling, principal component analysis(PCA) and Clustering
# Loading and assesment of the dataset
    ● the dataset was in a CSV format and it was imported using pandas
    ● It was assessed for presence of missing values and data types
# Data Wrangling and Cleaning
    ● missing values were dropped
    ● the data date object datatype was converted to python date time
# Feature Engineering
    ● Creating new features; "Customer_For","Age" and " is Parent" and "total spent"
    ● modifying existing features; "education"
    ● renaming some features for more clarity
    ● dropped off more redundant features
# Exploratory Data Analysis
    ● bivariate data analysis was caried out on the data set and the presence of outliers was detected.
# Machine Learnind Modeling (PCA and Clustering)
    ● PCA technique was applied to reduce the dimensionality of the data
    ● The elbow method was used to determine the number of clusters to be used for the model and clustering was performed using the Kmeans clustering and lastly the new clusters were plotted out and examined
# Observation
  The following observations were deduced from the Model;
    ● cluster 1 are high earners and high spenders
    ● cluster 0 and cluster 2 are low earners and low spenders
    ● cluster 3 are average to high earners but average spenders
