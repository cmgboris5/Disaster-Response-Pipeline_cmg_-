
# Disaster Response Pipeline Project
## by cmg__
### Table of Contents

1. [Summary](#Summary)
2. [Introduction](#Introduction)  
3. [Instructions](#Instructions) 


## Summary <a name="Summary"></a>

## File Description
~~~~~~~
        disaster_response_pipeline
          |-- app
                |-- templates
                        |-- go.html
                        |-- master.html
                |-- run.py
          |-- data
                |-- disaster_message.csv
                |-- disaster_categories.csv
                |-- DisasterResponse.db
                |-- process_data.py
          |-- models
                |-- classifier.pkl
                |-- train_classifier.py
          |-- README
~~~~~~~ 
      


## Introduction: <a name="introduction"></a>

Our mission is to develop (NLP) model that can categorize communications in real time. 

This project in the following sections:
Processing data, putting together an ETL pipeline to extract data from a source in collaboration.  We will be working with a data set provided by [Figure Eight](https://www.figure-eight.com/) containing real messages. We will cleaning it up, and save it in a SQLite database.
Implement a machine learning pipeline to build a classifier that can classify text messages into different categories.
Developing a web app that displays model results in real time.

## Instructions <a name="instructions"></a>

1- Run the following commands in the project’s root directory in terminal of VSCode to set up your database and model.
- To run ETL pipeline that cleans data and stores in database 
    - _**python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db**_
- To run ML pipeline that trains classifier and saves 
    - _**python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl**_

2- Run the following command in the app’s directory to run your web app. 
    _python app/run.py_ 
    
3- Go to http://0.0.0.0:3001/


## The project contains a web app on the following:

![Screenshot(01)](https://user-images.githubusercontent.com/103899117/170536793-df5720d2-6b48-4566-a383-fa7015cda0a7.png)
![Screenshot(02)](https://user-images.githubusercontent.com/103899117/170536796-a01e7e0e-e19d-4cc5-abb0-aadc8a1a8f99.png)
