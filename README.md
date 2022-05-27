# Disaster Response Pipeline Project
## _By: CMG_

# **Instructions to run the project:**

1- Run the following commands in the project’s root directory in terminal of VSCode to set up your database and model.
- To run ETL pipeline that cleans data and stores in database 
    - _**python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db**_
- To run ML pipeline that trains classifier and saves 
    - _**python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl**_

2- Run the following command in the app’s directory to run your web app. 
    _python app/run.py_ 
3- Go to http://0.0.0.0:3001/
