# MachineLearninginR
Machine Learning Assignments from R for Data Science course
\
In this course we covered concepts and R libraries to both help us deal with data issues before training machine learning models and about various machine learning algorithms. The R markdown files contain code for machine learning algorithms trained in R.
\
Before training, a few things we were told to check include:
* missing values through multiple imputations
* find out whether our data is skewed and how to fix that skewness through diffrent transformations(Box-Cox, Tukey, logarithmic, cube/square root Transformations, data normalization/ standardization)
* Assumptions for Valid Linear Regression, Descriptive Statistics for Exploratory Data Analysis, among other things
\
We experimented with the following Machine Learning Algorithms:
* Linear and Logisitic Regression
* Regression Trees
* KNN
* Naive Bayes
* Kmeans and Hierarchical Clustering
* Introductory Text Mining

For Assignment 1 of the course, we covered basic data cleaning, missing value imputations, writing functions in R to filter, mutate and select specific variables
\
For Assignment 2 of the course, the following libraries were used for analysis:
* tidyverse, dplyr, lmtest, ggplot2, rcompanion, MASS, and corrplot
We merged and analyzed datasets from different packages, performed data cleaning, drew graphs and histograms to test for skewness, performed Shapiro-Wilkes to test for normality, performed linear regression, analyzed residuals for normality and for outliers, used Breusch-Pagan test to check for constant variance, and used stepwise regression to find the independent variables with the highest predictive power.
\
For assignment 3 the concepts covered in the previous assignments (like using stepwise regression for feature selection) were revisited and new machine learning algorithms were implemented. KNN was applied individually on the Abalone Dataset and the elbow method was used to find the best k clusters for accurate prediction of Abalone age. We also built emsemble models of Random Forests, Naive Bayes, SVM and Logistic regression and applied these ensemble models to predict wine quality and calorie range (low or high) from a wine quality dataset and from a USDA nutritional counts dataset. Labels of low quality and high quality and low calorie and high calorie were derived Correlation plots were used to remove highly correlated variables from the dataset before training models. Kmeans clustering was applied to find clusters in the old faithful geyser eruption dataset. The last part of the assignment covered text analytics of Martin Luther King's "I have a Dream" and Barack Obama's and Donald J Trump's State of the Union speeches. The speeches were broken down into bi-grams and sentiment analysis was performed to understand the sentiment of the words used.
\
The Assignments were completed individually by me. The Final Assignment was done as a group. We tried to predict whether stock prices of a certain stock would increase or decrease based on a labelled dataset(which indicated year-end increase or decrease) available on Kaggle. This dataset had over 200 financial indicators for over 4000 companies spanning 4 years. We also used Weekly pharmaceutical sales data (over a perod of 4 years) and attempted to extract insights about the seasonality of certain drugs. Unfortunately, as time series was not covered in this course, the analysis we obtained from the pharma sales dataset is not 100% accurate but this assignment allowed us to think about interesting questions and implement the techniques we learned in class to a real world problem.
