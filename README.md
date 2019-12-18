# Kaggle-solutions

I have used datasets from kaggle to analyze them.
This folder contains following files:

1. House pricing data: I analyzed house pricing data to predict the price of houses. First, chose the features which are useful for prediction. Then after cleaning the data (such as handling outliers and missing values), used both random forest and linear regression and chose the one which perform better.

2. Don't Overfit: In this the main task was not to overfit the data while predicting because of high dimension. First cleaned the data and then used logistic regression to classify.

3. Tmdb box office prediction: In this, I analyzed data from The movie database to predict the worldwide box-office revenue of movies. It contain following files:
   a) File 1- Feature extraction: In this I extracted features from variables like cast, crew and genres. Example of one feature, extracted top 15 most common genres among movies and created dummy for each of this genre.
   b) File 2- Data Exploration: After generating featurese, saw the relationship of these features with target variable through visualization.
   c) File 3- Model Building and Prediction using Random Forest: In this, used Random forest with grid search to predict revenue.
   d) File 4- Model Building and Prediction using Support Vector Regression: In this, used SVR to predict the revenue.
