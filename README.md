Asteroid Hazard Prediction Project
This project focuses on predicting the potential hazard level of Near Earth Objects using machine learning techniques. The dataset contains physical attributes and orbital characteristics of asteroids. You can access the source data at the following link: https://www.kaggle.com/datasets/adityaramachandran27/nasa-near-earth-objects-information

Project Overview
The primary objective is to classify asteroids as hazardous or non hazardous based on their physical properties. The dataset presents an imbalanced distribution where safe objects significantly outnumber hazardous ones. To address this issue the project implements data preprocessing and synthetic oversampling techniques.

Technical Methodology
The implementation follows a structured data science pipeline:

Data Cleaning removing irrelevant identifiers and non numeric attributes

Preprocessing handling missing values to ensure model stability

Balancing performing Synthetic Minority Over sampling Technique to improve detection of hazardous objects

Modeling utilizing Random Forest Classifier to achieve robust classification performance

Evaluation assessing model reliability through accuracy and recall metrics

Key Results
The model achieves high accuracy while focusing on identifying hazardous asteroids. By adjusting class weights and applying balancing techniques the system provides a reliable tool for orbital analysis. The Random Forest approach proves effective in distinguishing features that define asteroid threat levels.
