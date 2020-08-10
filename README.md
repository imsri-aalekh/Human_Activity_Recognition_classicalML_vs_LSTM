**Human Activity Recognition**

This project is to build a model that predicts the human activities such as 
1. Walking, 
2. Walking_Upstairs, 
3. Walking_Downstairs, 
4. Sitting, 
5. Standing  
6. Laying.

This dataset is collected from 30 persons(referred as subjects in this dataset),
performing different activities with a smartphone to their waists. 
The data is recorded with the help of sensors (accelerometer and Gyroscope) in that smartphone. 
This experiment was video recorded to label the data manually.Thanks to UCI for the dataset

In this project we have performed sanity check like checking for nan values , outliers , imbalanced dataset ,
performed Exploratory Data Analysis.

In this project we have applied classical machine learning algorithms on 561 dimensional hand engineered features by experts.

Since the dataset collected from UCI says that the data is a timeseries data which is also present as raw files collected by applying 
windowing technique, so we decided to use Long Short Term Memory (since sequence matters inthis case) and reported an accuracy of 91.7% 
using the raw data only.
