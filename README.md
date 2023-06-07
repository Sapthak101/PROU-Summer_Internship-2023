# PROU-Summer_Internship-2023
This repository contains the code file and resources of my Summer Internship Project under PROU Education

Abstract:

  Machine Learning is a branch of artificial intelligence (AI) that focuses on the development of algorithms and models that enable computers to learn and make predictions or decisions without being explicitly programmed. It involves the use of statistical techniques to give computers the ability to learn from and analyze data, identify patterns, and make intelligent decisions or predictions.

  The key idea behind machine learning is to create computer programs or models that can automatically learn from data and improve their performance over time. Instead of following strict rules or instructions, these models learn by example and experience, extracting meaningful insights from the data they are trained on.

Dataset:

  https://drive.google.com/drive/folders/1fXxF9Z6aPNRgP5CW_IXHMsxiLyhI7ZNF?usp=sharing
  
  (File Name: train.csv, size: 97 MB)
  
1.General Description

  1.1 Problem Statement: To accurately predict Airbnb price, we aim to collect a dataset containing features which directly impact the rental price. No better place to start than by gathering a number of listings with fields directly from the site. Below you will find a list of the features that were taken from Airbnb and which turn out to be very important attributes in the price prediction. Since we know the price for each row, this can be classified as a supervised learning problem, and we will split our data into distinct training, test, and cross-validation sets. For now, we will examine the dataset as a whole, and come back to this division later. As a general rule, I like to examine a dataset’s features for several characteristics before proceeding or deciding to gather additional data. These characteristics include: 
  • Number of missing values and how to deal with them (NaN or null) 
  • Type of data (categorical, boolean, image, numerical, text, etc) 
  • Shape and size of data (this impacts the type of model we will use) 
  • Classical statistical analysis (mean, median, range, variance, st. dev, etc

  2.2 Tools Implmented: 
  IDE: Visual Studio
  Language: Python 3.11 (Jupyter Notebook)
  Python Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn, Tensorflow, 
  Keras etc.
  
2.Design Details:

  2.1 Functional Architecture: This is Supervised Machine Learning task. The whole project has been implemented on the Jupyter Notebook using Python 3.11 as the base language. We have also implemented libraries like NumPy, Pandas for getting the required database on an acceptable format. Then using libraries like Matplotlib and Seaborn we have done the necessary visualizations and exploration. Then discarded features which do not significant affect our desired outcome that is the price, and we have also filled the Nan values or missing data with relevant data based on the distribution weight of the existing data and number of Nan values. In this way we did the necessary data preprocessing. Then we have developed the models for both Regression Deep Learning and Normal Regression and found the predicted value for our test values and compared them with the actual values to find the efficiency of our proposed models.
  3.2 Optimization: There are some features which cannot be directly feed into our model, so featured engineered them by taking them into an acceptable form to include them into our models to increase efficiency of our models.
  
3. KPIs:

  3.1 KPIs (Key Performance Indicators): The Key Performance Indicators we have implemented on our models are given below:
        I. MSE (Mean Square Error)
        ii. RMSE (Root Mean Square Error)
        iii. MAE (Mean Absolute Error)
