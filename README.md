# Flight Fare Prediction

## Problem Statement:
Travelling through flights has become an integral part of today’s lifestyle as more and more people are opting for faster travelling options. The flight ticket prices increase or decrease every now and then depending on various factors like timing of the flights, destination, and duration of flights various occasions such as vacations or festive season. Therefore, having some basic idea of the flight fares before planning the trip will surely help many people save money and time.

## Approach:
The main goal is to predict the fares of the flights based on different factors available in the dataset.

1.Data Exploration : I started exploring dataset using pandas,numpy,matplotlib and seaborn.

2.Data visualization : Ploted graphs to get insights about dependend and independed variables.

3.Feature Engineering : Removed missing values and created new features as per insights.

4.Model Selection I : Tested all base models to check the base accuracy.
Also ploted residual plot to check whether a model is a good fit or not.

5.Model Selection II : Performed Hyperparameter tuning using gridsearchCV and randomizedSearchCV.

6.Pickle File : Selected model as per best accuracy and created pickle file using joblib .

7.Webpage & deployment : Created a webform that takes all the necessary inputs from user and shows output.
After that I have deployed project on google cloud as well as on heroku platform.

## Deployment Links:
Heroku link:https://flightfarepredictors.herokuapp.com/predict

## User Interface:
![Screenshot (499)](https://user-images.githubusercontent.com/62504908/134799815-8e647e0a-b836-4c9c-a06d-74f10f23596b.png)


## Technologies Used:
Python

Sklearn

Flask

Html

Css

Pandas, Numpy

Database

Hosting

Technical aspect:

1.Python 3.9

2.Front-end: HTML, CSS

3.Back-end: Flask

4.IDE: Jupyter Notebook, VisualStudio

5.Database: MongoDB Atlas

6.Deployment: Heroku
![image](https://user-images.githubusercontent.com/62504908/134799801-4018e369-5911-4ad8-a356-d25ded29dc46.png)


## Run Locally
1.Clone the project
git clone https://github.com/Sc4rrr/Flight_Fare_Prediction

2.Go to the project directory
cd Flight_fare_prediction

3.Install dependencies
pip install -r requirements.txt

4.Setting up the Controllers files
Update the values inside the Controllers folder

5.Run the app.py
python app.py

## Help Me Improve
Hello Reader if you find any bug please consider raising issue I will address them asap.
