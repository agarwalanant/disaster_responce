# Installations
In order to run the codes in this project, the following libraries must be installed:
1. Pandas
2. Numpy
3. Sci-kit Learn
4. Flask
5. SQL Alchemy
6. Plotly
7. NLTK

# Motivation
This project was done to complete the requirements for Udacity's Data Scientist Nanodegree. Using text data from Figure-8, a company specializing in data analytics and machine learning, the purpose was to classify messages that were created during a disaster into 36 categories to help in aid efforts.

# Files
The project is divided into 3 folders: one for data and data processing; another one is for building a machine learning pipeline; and the third is for the web app. There are also 3 screenshots for the final web app.

### Files in the Data Folder
1. Messages data: disaster_messages.csv
2. Categories data: disaster_categories.csv
3. SQL Database: DisasterResponse.db

### Files in the Models Folder
1. Python script for training the classifier: train_classifier.py
2. A pickle file that contains the trained model: classifier.pkl { ### should be downloaded from google drive link https://drive.google.com/file/d/1IpszRqikVnHxiixKI5kPGOD0SugRR8ds/view?usp=sharing )

### Files in the App Folder
1. Python script for running the web app: run.py
2. templates folder that contains 2 HTML files for the app front-end: go.html and master.html

# Instructions for running the Python scripts:
1. Run the following commands in the project's root directory to set up your database and model.
    - To run ETL pipeline that cleans data and stores in database: `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves it: `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`
2. Run the following command in the app's directory to run your web app: `python run.py`

3. Go to http://0.0.0.0:3001/ 

#Screenshots:
[screen 1]https://github.com/agarwalanant/disaster_responce/blob/master/file1.JPG

[screen 2]https://github.com/agarwalanant/disaster_responce/blob/master/file2.JPG

[screen 3]https://github.com/agarwalanant/disaster_responce/blob/master/file3.JPG

# Results
The final output of the project is an interactive web app that takes a message from the user as an input and then classifies it.

# Acknowledgement
Thanks to Udacity for providing guidance to complete the project and thanks to Figure-8 for providing the data
