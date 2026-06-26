Student Engagement & Churn Prediction

Project Overview

This project leverages machine learning to predict student engagement levels in educational environments using physiological and behavioral data. By analyzing EEG signals and eye-tracking metrics, this model provides an early-warning system for educators to identify students at risk of disengaging from learning platforms (churn).

Key Features

Data Analysis: Processed complex physiological datasets, including EEG frequency bands (Delta, Theta, Alpha, Beta, Gamma) and eye-tracking metrics (pupil dilation, blink rate, fixation, and saccade).

Machine Learning: Implemented a Random Forest Classifier to map physiological patterns to engagement levels.

Predictive Modeling: Successfully converted multi-class engagement labels into a binary classification model to detect potential churn with 70% accuracy.

Analysis & Interpretation

The model demonstrates high reliability in identifying low-engagement states (Class 0), with a recall of 0.99. Feature importance analysis revealed that Theta and Alpha brain waves are the most significant predictors of student focus. This suggests that a student's underlying neurological state is a stronger indicator of engagement than basic behavioral metrics.

Technologies Used

Language: Python

Data Handling: Pandas, NumPy

Machine Learning: Scikit-learn

Visualization: Matplotlib

How to Run

Clone this repository: git clone [https://github.com/Aeman2026/student-engagement-churn-predictionl]

Install dependencies: pip install pandas scikit-learn matplotlib

Run the notebook: jupyter notebook churn.ipynb

