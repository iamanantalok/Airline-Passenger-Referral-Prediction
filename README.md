# Airline Passenger Referral Prediction

![image](https://github.com/iamanantalok/Airline-Passenger-Referral-Prediction/assets/117917485/2ac8931e-93ae-414b-89d5-f8b341abe346)


Predicting aircraft passenger referrals and uncovering the main influencing factors can help airlines improve their services and gain a competitive edge. This repository contains a machine learning project focused on predicting whether a passenger will refer an airline to others. We will explore a dataset that includes past passengers' referral behavior, as well as various features such as age, gender, flight class, and route information. By identifying potential advocates, airlines can improve customer satisfaction and loyalty while attracting new customers.

## Table of Contents

1. [Objective](#objective)
2. [Description of Features](#description-of-features)
3. [Data Preparation](#data-preparation)
4. [Exploratory Data Analysis (EDA)](#eda)
5. [Feature Engineering & Data Pre-processing](#feature-engineering--data-pre-processing)
6. [Model Building](#model-building)
7. [Model Evaluation](#model-evaluation)
8. [Conclusion](#conclusion)

## Objective

The main objective of this project is to predict whether passengers will refer the airline to their friends.

## Description of Features

- `airline`: Name of the airline.
- `overall`: Overall rating given to the trip on a scale of 1 to 10.
- `author`: Author of the trip.
- `reviewdate`: Date of the review.
- `customer review`: Review of the customers in free text format.
- `aircraft`: Type of the aircraft.
- `travellertype`: Type of traveler (e.g., business, leisure).
- `cabin`: Cabin on the flight.
- `date flown`: Flight date.
- `seatcomfort`: Rated between 1-5.
- `cabin service`: Rated between 1-5.
- `foodbev`: Rated between 1-5.
- `entertainment`: Rated between 1-5.
- `groundservice`: Rated between 1-5.
- `valueformoney`: Rated between 1-5.
- `recommended`: Binary target variable (0 or 1).

## Data Preparation

- Dropping rows with entirely missing values.
- Dropping columns that do not add value for analysis.
- Removing duplicates.

## Exploratory Data Analysis (EDA)

EDA helps us gain insights into the data, detect errors, understand data patterns, and identify relationships between variables. Some key findings from EDA include:
- Relationship between traveler types and cabin class ratings.
- Seat comfort ratings based on travel purpose.
- Distribution of food and beverage ratings.

## Feature Engineering & Data Pre-processing

- Handling missing values and imputing missing values using the median.
- Categorical encoding using label encoding.
- Textual data preprocessing for the 'customer review' feature using NLP techniques.

## Model Building

We implemented the following machine learning models:
- Logistic Regression
- K-Nearest Neighbors
- Support Vector Machine

## Model Evaluation

We used various evaluation metrics, including precision, recall, and ROC AUC score, to assess the performance of our models. These metrics help determine the impact on business outcomes. Striking a balance between precision and recall is crucial depending on the specific context and cost considerations.

## Conclusion

In this project, we conducted a comprehensive analysis to predict airline passenger referrals. We explored the dataset, built and evaluated multiple machine learning models, and selected the Support Vector Machine (SVM) model with hyperparameter tuning as our final prediction model due to its high accuracy. The project's insights can assist airlines in understanding passenger preferences and optimizing their services to enhance customer satisfaction and referrals.
