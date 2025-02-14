Multiple Disease Prediction System

This is a web-based application developed using Streamlit that allows users to predict the likelihood of having Diabetes, Heart Disease, or Parkinson's Disease using trained machine learning models.

Features

Diabetes Prediction

Heart Disease Prediction

Parkinson's Disease Prediction

User-friendly interface with Streamlit

Model-based predictions using saved ML models

Installation

Prerequisites

Ensure you have Python installed on your system. Install the required dependencies using:

pip install streamlit pickle5 streamlit-option-menu

Running the App

To start the Streamlit application, navigate to the project directory and run:

streamlit run app.py

Project Structure

Multiple-Disease-Prediction/
│── SavFiles/
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   ├── parkinsons_model.sav
│── app.py
│── README.md

Usage

Select a Disease: Use the sidebar menu to choose between Diabetes, Heart Disease, or Parkinson's Disease Prediction.

Enter the Required Inputs: Provide the necessary medical data in the input fields.

Get Prediction: Click the prediction button to get the results.

Model Details

The models are pre-trained and saved using pickle.

They take numeric inputs and return a classification result.

Requirements

Python 3.x

Streamlit

Pickle

streamlit-option-menu

Notes

Ensure that the .sav model files are available in the SavFiles folder.

All input values should be numeric to avoid errors.

The models used are trained externally and not part of this repository.
