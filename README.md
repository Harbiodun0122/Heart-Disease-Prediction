# Heart Disease Prediction
This repository contains a Python script for predicting heart disease using machine learning. The script includes data preprocessing, model training, evaluation, and prediction steps.

The dataset used in this project is provided by Data Science Nigeria for 2024 AI Bootcamp Qualification Hackathon on zindi.

## Folder Structure Setup
All files are in a single folder. Ensure your folder contains the following:

Test Dataset

Train Dataset

HEART_DISEASE_PREDICTION.ipynb: The script for running the prediction task.

## How to Run the Script
To run the prediction script, open the **HEART_DISEASE_PREDICTION.ipynb** file and execute all the cells

The script will preprocess the data, train the model, and save the results in the same folder.

## Features Used
The dataset includes the following features:

**Age:** The age of the individual.

**Sex:** The gender of the individual (0 and 1).

**Chest Pain Type:** Categorizes the type of chest pain.

**Resting Blood Pressure:** The resting blood pressure of the individual.

**Cholesterol Level:** Serum cholesterol in mg/dl.

**Fasting Blood Sugar:** Whether fasting blood sugar is > 120 mg/dl (1 = true, 0 = false).

**Resting ECG:** Resting electrocardiographic results.

**Max Heart Rate Achieved:** The maximum heart rate achieved during exercise.

**Exercise Induced Angina:** Whether the individual experienced angina during exercise.

**ST Depression:** Depression induced by exercise relative to rest.

**Slope of Peak Exercise ST Segment:** Slope of the peak exercise ST segment.

**Number of Major Vessels Colored by Fluoroscopy:** Number of major vessels colored by fluoroscopy.

**Thal:** Blood disorder test result (0 = normal; 1 = fixed defect; 2 = reversable defect).


## Environment Setup

To replicate the environment, you can use the provided requirements.txt file (for pip).

```pip install -r requirements.txt```


## Hardware Requirements
You can run the script either locally or on Google Colab.

**Google Colab:** The script can be easily run in Google Colab, which provides access to free GPUs and TPUs.

**Local Machine:** If running locally, here are the recommended specifications:

> **RAM:** Minimum 8GB

> **Processor:** Intel Core i5 or higher

> **GPU:** Optional but recommended for faster training


## Expected Run Time
The approximate time to run the script is:

Local Machine (8GB RAM, no GPU): ~ 5 minutes

Google Colab (with GPU): ~ 2 minutes
