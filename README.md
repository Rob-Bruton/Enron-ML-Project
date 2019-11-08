# Enron-ML-Project
Final project for Udacity Intro to Machine Learning course.

The goal of this project was to build a classification model that would identify persons of interest (POIs) in the Enron scandal based on the financial information and email corpus made available to the public following the resolution of the scandal. The financial information dataset contains information regarding salaries, bonuses, stock values, and more for a subset of 143 Enron employees. The idea is that a machine learning classification algorithm could be trained on this data and then used to determine which employees are likely to be POIs for investigation.

My final classifier uses the Gradient Boosting algorithm. When testing my classifier using tester.py, the accuracy was 0.93, precision was 0.88, recall was 0.97, the F1 score was 0.92, and the F2 score was 0.95.
