# Capstone-Project-2--News-Prediction

This project is part of the “Machine Learning &Advanced Machine Learning” curriculum as capstone projects at AlmaBetter.

OBJECTIVE


The main objective is to create a machine learning model to predict the popularity of news on different social media platforms such as Facebook, LinkedIn and Google Plus





PROJECT FILES DESCRIPTION

This Project includes 1 executable files and 1 project documentation as follows:

Executable Files:

News_Popularity_Prediction.ipynb - Complete notebook containing Data exploration/Data processing/transformation/model development.







Documentation:

News Popularity Prediction_cohort_seattle.pptx - Includes the documentation of the project






METHODS USED

Descriptive Statistics

Data Visualization

Machine Learning






Technologies

Python

Pandas

Numpy

Matplotlib

Seaborn

Scikit-learn

XGBoost








Abstract


News popularity on various social media platforms depends on multiple features like the topic, source of publication, time-span and sentiment score. Here we are provided with a dataset that contains news items and their respective social feedback on different platforms: Facebook, GooglePlus and LinkedIn. Based on the previous trend, this data analysis and prediction with machine learning models can help us understand what are the reasons for news popularity on social media and obtain the best regression model.








DATA DESCRIPTION

We have 13 dataset which are categorised into 2 types News_Final dataset and Time Span Dataset.

1. News_Final Dataset(1 Dataset):
It contains information of news related to 4 topics Microsoft, Obama, Economy and Palestine collected from different sources and their popularity on 3 social media platform namely Facebook, GooglePlus and LinkedIn.



IDLink (numeric): Unique identifier of news items

Title (string): Title of the news item according to the official media sources

Headline (string): Headline of the news item according to the official media sources

Source (string): Original news outlet that published the news item

Topic (string): Query topic used to obtain the items in the official media sources

PublishDate (timestamp): Date and time of the news items' publication

SentimentTitle (numeric): Sentiment score of the text in the news items' title

SentimentHeadline (numeric): Sentiment score of the text in the news items' headline

Facebook (numeric): Final value of the news items' popularity according to the social media source Facebook

GooglePlus (numeric): Final value of the news items' popularity according to the social media source Google+

LinkedIn (numeric): Final value of the news items' popularity according to the social media source LinkedIn

VARIABLES OF SOCIAL FEEDBACK DATA

IDLink (numeric): Unique identifier of news items

TS1 (numeric): Level of popularity in time slice 1 (0-20 minutes upon publication)

TS2 (numeric): Level of popularity in time slice 2 (20-40 minutes upon publication)

TS... (numeric): Level of popularity in time slice ...

TS144 (numeric): Final level of popularity after 2 days upon publication







NEEDS OF THIS PROJECT

data exploration/descriptive statistics

data processing/cleaning

predictive modeling









 Execution Instruction
 
The order of execution of the program files is as follows:


1) News_Popularity_Prediction.ipynb

The News_Popularity_Prediction.ipynb contains the entire code for Data exploration/Data processing/transformation/model development

References 
https://towardsdatascience.com 


https://www.analyticsvidhya.com


https://machinelearningmastery.com
