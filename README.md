
# A Multiple Linear Regression Model for Predicting Life Expectancy In Developing and Developed Countries
![lifeexpectancy](https://user-images.githubusercontent.com/117164514/212286126-aa767538-b443-404a-85c6-3ad8627b26a7.jpg)


## Overview
This project aims to predict the life expectancy using multilinear regression model using a dataset obtained from kaggle containing information on countries such as; status, life expectancy, adult motality and many more.
### Dependancies
* python3
* numpy
* pandas
* seaborn
* sklearn
* statsmodels
* matplotlib

## Problem Statement
To investigate which elements are most closely associated with life expectancy and how they vary between different factors such as education level, status, and BMI. By doing so, it aims to identify potential areas for improvement to increase life expectancy and ultimately improve population health and well-being.

## Main Objective
To build a multilinear regression model that will predict the life expectancy of a given population.
## Specific Objectives
* To investigate if an immunization has an impact on life expectancy

* To determine if schooling affects life expectancy
 
* To determine whether adult mortality rates affect life expectancy

## Data Understanding
### Data Source
The dataset used in this project was obtained from Kaggle.
### Data Description
The Life Expectancy Data.csv contains 2938 rows and 22 columns. The columns cointain both numerical and categorical data.
### Data Preparation
The data was checked to ensure it was in useable form. This was done by checking duplicates, null values, outliers, removing white spaces and filing the missing values.

## Explanatory Data Analysis
### Count plot between developed and developing countries 
![image2](https://user-images.githubusercontent.com/117164514/212286407-d359f1d3-37b0-4a64-be4b-d26953cfbd1d.png)

The majority of people have a life expectancy between the ages of 72-76.
### Life Expectancy distribution
![image3](https://user-images.githubusercontent.com/117164514/212286366-b7906153-7d61-4d73-893f-d67cb42e7d4a.png)

The majority of people have a life expectancy between the ages of 72-76.
### Comparison of percentage expenditure between developed  and developing countries

![image4](https://user-images.githubusercontent.com/117164514/212286927-8d5893e0-cf69-4a1b-be7c-a53a0782e4db.png)

Developed countries spend more on health than developing countries.
### Hepatitis_b and diphtheria immunization in developed and developing countries
![image5](https://user-images.githubusercontent.com/117164514/212287204-5dcf7d6f-f808-4a5f-957d-36f2e95a3da6.png)

Developed countries have more Immunization coverage among 1-year-olds as compared to the Developing countries.

## Modelling
The Multiple Linear Regression model was used for the prediction.
It involved checking correlation, creating subsets, dealing with categorical variables, binary encoding, standardizing the variables by zero centering.
The first model had an adjusted R-Squared of 74% while the second model had an adjusted R-Squared of 75%.
## Conclusion
The model predicted:

* Developing countries should not only focus on bringing more children into school but also to improve the quality of the educational system itself by reducing the cost of education, investing in school lunch programs, educating parents and improving resources for teachers.

* Developing countries should make vaccines more accessible by partnering with local pharmacies, paramedics, and healthcare providers to offer door-to-door vaccination services and set up a hotline and an online form for people to request at-home vaccinations.

* The BMI range of a person also directly affects their life expectancy. People who are in the middle range, meaning neither too thin nor too fat have longer life spans. 

* Developing countries should also improve access to healthcare by expanding insurance to cover healthcare costs, extend telehealth services, provide cheaper drugs, and educate the public about multiple healthcare sites.


## Repository Guide
The data used for the project can be found here https://github.com/VictoriaBay/Life-Expectancy/blob/main/Life%20Expectancy%20Data.csv

The images from EDA can be found here https://github.com/VictoriaBay/Life-Expectancy/tree/main/Images

The notebook that contains the project can be found here https://github.com/VictoriaBay/Life-Expectancy/blob/main/Multi_Linear_Regression_Project__Group_Goku%20(1).ipynb

The presentation for this project can be found here https://www.canva.com/design/DAFXcxoLKC8/P1Ij9Ag2Y9flm8mwstfADg/edit?utm_content=DAFXcxoLKC8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

A Data Report for this project can be found here  https://github.com/VictoriaBay/Life-Expectancy/blob/main/Data%20Report%20(GOKU).pdf
