# udacity-disaster-response-pipeline-project by Dilupa Chandrasekara

## Table of Contents
1. Introduction
2. File Description
3. Installation
4. Instructions
5. Acknowlegements

## Introdcution
This project is part of the Udacity Data Scientist Nanodegree and was created in collaboration with Figure Eight. It aims to categorize disaster messages in real-time during a disaster event, by using pre-labeled disaster messages to build a model. The project includes a web application where disaster response workers can input messages and see the classification results.

## File Description
The project consists of several files and folders:

The "app" folder contains the "run.py" script to launch the web application and the "templates" folder with web dependency files.
The "data" folder contains "disaster_messages.csv" and "disaster_categories.csv" with the real messages and their categories, the "process_data.py" script for the ETL pipeline, and the "DisasterResponse.db" database.
The "models" folder includes the "train_classifier.py" script for the ML pipeline, the "classifier.pkl" file with the trained model, and a Jupyter Notebook for preparing the ML pipeline.

## Installation
To install, there should be no additional libraries required apart from those that come with the Anaconda distribution. The codes should work with Python 3.5 and above.

To run the project, use the following steps:

Run the "process_data.py" script to clean the data and store it in the database.
Run the "train_classifier.py" script to train the model and save it as a pickle file.
Use the "run.py" script in the app's directory to run the web application.

## Acknowledgements
This project was made possible with the support of Udacity for providing the Data Scientist training program and Figure Eight for the dataset. There are screenshots provided to show the main page, the process of entering a message, and the classification results.
