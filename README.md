# Anime Recommendations with Simple Linear Regression
This project focuses on building a simple linear regression model to predict anime ratings based on various features from the dataset, such as the number of members and genres. The data is cleaned, processed, and analyzed to provide meaningful insights and predictions.

## Project Overview  
The goal of this project is to predict anime ratings using linear regression techniques based on an anime dataset. We use feature engineering to refine the dataset and improve the accuracy of predictions.

## Table of Contents
1. Dataset  
2. Project Workflow
   
    Dataset Exploration  
    Feature Engineering  
    Linear Regression  
    Insights and Reporting
     
3. Installation   
4. Usage  
5. Results  
6. Conclusion  
7. Next Steps

## Dataset
The dataset used in this project consists of two files:

anime.csv: Contains information about various anime such as name, genre, rating, and the number of members.  
rating.csv: Contains user ratings for different anime.

### Key attributes:

name: Title of the anime  
genre: Genres associated with the anime  
rating: Average rating given to the anime  
members: Number of users who have watched the anime  

## Project Workflow

1. Dataset Exploration

Data Loading: Importing necessary libraries and loading the dataset.  
Handling Missing Values: Handling missing entries in rating, genre, and other columns.  
Visualization: Plotting the distribution of ratings and members to understand the data.  
Outlier Handling: Handling outliers in the number of members.  

2. Feature Engineering  

Log Transformation: Applying a log transformation to the members column to reduce skewness.  
Genre Count: Creating a new feature to count the number of genres per anime.  
One-Hot Encoding: Encoding the genre column using one-hot encoding for better feature representation.  

3. Linear Regression  

Regression Model: Fitting a simple linear regression model using the transformed features.  
Train-Test Split: Splitting the data into training and test sets.  
Model Evaluation: Calculating the Mean Squared Error (MSE) and visualizing the regression line.  

4. Insights and Reporting  

Feature Impact: Analyzing how the number of members impacts the anime rating.  
Predictive Insights: Highlighting the key predictive features.  

## Usage

Ensure the dataset (anime.csv and rating.csv) is placed in the appropriate folder.  
Run the Jupyter notebook WT-1 Anime Recommendations with Simple Linear Regression Rahul Manjhi.ipynb to perform data analysis, feature engineering, and regression.  

## Results

Mean Squared Error (MSE): 0.601  
Regression Slope: 0.291  
Regression Intercept: 4.32  

A scatter plot visualizes the relationship between the log of members and anime ratings, with a regression line indicating the model's fit.

## Conclusion
This project successfully demonstrates how a simple linear regression model can be used to predict anime ratings. Feature engineering significantly improved the model's predictive performance.

## Next Steps
Enhance the model by experimenting with additional regression techniques.  
Integrate more features, such as user-based and content-based collaborative filtering methods for better recommendation performance.  
Deploy the model as a web app for real-time anime recommendations.  

