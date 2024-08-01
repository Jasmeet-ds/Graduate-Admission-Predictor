# Graduate-Admission-Predictor

## Overview

This project aims to build a machine learning model that predicts the probability of admission to a graduate program based on various factors such as GRE score📝, TOEFL score🔖, university rating📈, statement of purpose (SOP)📄, letter of recommendation (LOR)📩, undergraduate GPA💯, and research experience👩🏼‍🔬.

## Dataset

The dataset used in this project contains the following features:

* GRE Score: Graduate Record Examination score (out of 340)
* TOEFL Score: Test of English as a Foreign Language score (out of 120)
* University Rating: Rating of the university (1 to 5)
* SOP: Strength of the Statement of Purpose (1 to 5)
* LOR: Strength of the Letter of Recommendation (1 to 5)
* GPA: Undergraduate Grade Point Average (out of 10)
* Research: Research experience (0 or 1)
* Chance of Admit: Probability of admission (ranging from 0 to 1)

## Project Structure

* Data Preprocessing: Cleaning and preparing the data for modeling.
* Exploratory Data Analysis (EDA): Analyzing the dataset to understand the relationships between features.
* Feature Engineering: Creating and selecting features that will improve the model’s performance.
* Model Building: Training various regression models to predict the chance of admission.
* Model Evaluation: Evaluating the models using metrics such as RMSE (Root Mean Squared Error) and R² (R-squared).

## Models Used

* Random Forest Regressor

## Results

The *RandomForestRegressor* gives a moderate RMSE value of 0.07 indicating that it was the moderate in predicting the probability of graduate admissions.
