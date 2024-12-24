## Project Overview
This project classifies obesity levels using an Artificial Neural Network (ANN), analyzing user data to predict obesity categories while identifying key influencing factors.

## Motivation
Obesity is a global concern, and early identification can aid in targeted interventions. This project provides an automated, accurate classification method based on user lifestyle and health data.

## Approach
1.Data Collection and Preprocessing:

Cleaned dataset with user attributes like age, diet, and physical activity.
Removed irrelevant features and handled missing values.

2.Exploratory Data Analysis (EDA):

Used boxplots and correlation heatmaps to identify patterns and relationships.

3.Feature Engineering:

Transformed continuous variables like age into categorical bins for better interpretability.

4.Model Development:

Designed a multi-layer ANN with TensorFlow and Keras, using ReLU activation and softmax for classification.

5.Training and Evaluation:

Trained with categorical cross-entropy loss and Adam optimizer.
Achieved 89% accuracy with metrics like precision, recall, and F1-score.

## Challenges
Addressed imbalanced classes using SMOTE and class weighting, improving classification accuracy for minority classes.

## Results
Achieved 89% accuracy in classifying obesity levels across diverse profiles.
Identified key factors like age, dietary habits, and physical activity for targeted interventions.

## Tech Stack
Python, TensorFlow, Keras, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.

## Lessons Learned
Importance of data preprocessing and EDA for model performance.
Gained expertise in deep learning with TensorFlow and Keras.
