# AlmaBetter Capstone Project 3 - Regression : TED Talks Views Prediction

## This project is a part of the [Almabetter Pro Program Curriculum(Full Stack Data Science)](https://grow.almabetter.com/auth/signup?referralCode=4M11C2&utm_source=referral)

#### -- Project Status: [Completed]

#### -- Score: [ 93 / 100 ]

## Project Summary :
#### Problem Statement : 
The main objective is to build a predictive model, which could help in predicting the views of the videos uploaded on the TEDx website.


#### About the Data :
We have the data of previous TED talk events , which contains data points such as the length
(duration ) of the talk, topics , speaker occupation
and textual features such as Transcript , Title , and Description
And most importantly , the target variable : the view of the video
The Data is available for 4005 TED talks .


**Dataset info**

* 1.Number of records: 4,005

* 2.Number of features: 19

**Features information:**

The dataset contains features like:
* **talk_id**: Talk identification number provided by TED
* **title**: Title of the talk
* **speaker_1**: First speaker in TED's speaker list
* **all_speakers**: Speakers in the talk
* **occupations**: Occupations of the speakers
* **about_speakers**: Blurb about each speaker
* **recorded_date**: Date the talk was recorded
* **published_date**: Date the talk was published to TED.com
* **event**: Event or medium in which the talk was given
* **native_lang**: Language the talk was given in
* **available_lang**: All available languages (lang_code) for a talk
* **comments**: Count of comments
* **duration**: Duration in seconds
* **topics**: Related tags or topics for the talk
* **related_talks**: Related talks (key='talk_id',value='title')
* **url**: URL of the talk
* **description**: Description of the talk
* **transcript**: Full transcript of the talk
 
**Target Variable :** 
 * **views**: Contains Count of views of every talk


**Project Work flow**
----------------------------

1. Importing Libraries

2. Loading the dataset

3. Data Summary 

4. Data Cleaning & Data Analysis

5. Feature selection

6. Implementing Various Regression Algorithms

7. HyperParameter Tuning

8. Final selection of the model

9. Conclusion



#### Technical Details for ML : 
We used many Algorithms ( Random Forest , XGBoost and GBRegressor , Lasso , Ridge )
We used **GridSearchCV** for HyperParameter Tuning
Comparing both R2 Score , we can see that GBRegressor and XGBoost model performs the best

Miscellaneous :
* Google colab tools


