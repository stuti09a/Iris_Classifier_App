# Iris_Classifier_App
An interactive Iris Flower Prediction app built with Python and Streamlit that lets users adjust sepal and petal measurements to instantly predict the Iris species with confidence scores. Explore interactive visualizations, dataset insights, and feature analysis to understand the model and how each feature influences predictions.

Live App : https://irisclassifierapps.streamlit.app/

**Files created:**


training_model.py : Training the RandomForest model and save iris_model.joblib

iris_model.joblib : Trained model and metadata (features, target_names)

Iris_app.py : Streamlit app for prediction and exploration

data_exploration.py : To compute descriptive stats and save histograms

requirements.txt : Python packages required

README.md : This file

**How to run:**


First we need to create and activate a virtual environment (using latest python version as 3.11.9)

Install required modules: pip install -r requirements.txt

To retrain the model: python training_model.py

This will create or update the 'iris_model.joblib' in the current folder.

To run the Streamlit app: streamlit run Iris_app.py

Open the displayed local URL in browser (usually http://localhost:8501)

**Notes**

The app contains two modes: Prediction and Data Exploration ( using histograms and scatter plots).

The trained model file 'iris_model.joblib' is included.
