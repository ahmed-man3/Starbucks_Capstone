Starbucks Capstone Challenge

A model that classifies offers success.



Table of Contents


File Descriptions
Instructions
Licensing, Authors, and Acknowledgements
Installation

No necessary libraries to run the code except the ones available as part of the Anaconda distribution of Python. run the below to ensure having the correct pacages. install the necessary packages using requirements.txt by executing following command: - "pip install -r requirements.txt"

File Descriptions

There are 3 main folders as follows:

app:

run.py: Flask app
templates:
master.html: index web page.
go.html: classification result page of web app
data:

disaster_categories.csv: data to process
disaster_messages.csv: data to process
process_data.py: python file to process and clean the data
models:

train_classifier.py: python file to build and test the model
Instructions

Run the following commands in the project's root directory to set up your database and model.

To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv sqlite:///data/DisasterResponse.db
To run ML pipeline that trains classifier and saves python models/train_classifier.py sqlite:///./data/DisasterResponse.db models/classifier.pkl
Run the following command in the app's directory to run your web app.. python run.py

Go to http://0.0.0.0:3001/

Licensing, Authors, Acknowledgements

feel free to use the code here as you would like!