# 🖊️ Handwritten Digit Classification using KNN
## 📌 Project Overview

This project demonstrates handwritten digit classification using the K-Nearest Neighbors (KNN) algorithm. It focuses on distance-based classification, feature scaling, and K tuning to improve model accuracy. The project evaluates model performance using accuracy, confusion matrix, and classification report, and visualizes predictions on test images.

## 🎯 Objective

Classify handwritten digits (0–9) using KNN.

Explore the effect of different K values on model performance.

Understand the importance of feature scaling for distance-based classifiers.

Visualize results and misclassifications using confusion matrix and sample predictions.

## 🛠️ Tools & Libraries

Python

Scikit-learn

NumPy

Matplotlib & Seaborn

## ⚙️ Techniques Applied

Loaded Sklearn Digits dataset (built-in, no external dataset required).

Visualized sample digit images to confirm labels.

Split dataset into training and testing sets.

Applied StandardScaler to normalize features.

Trained KNN model with baseline K=3.

Tuned K values (3, 5, 7, 9) and plotted Accuracy vs K.

Generated confusion matrix for best K to analyze misclassifications.

Displayed sample test images with predicted labels.

## 📊 Evaluation Metrics

Accuracy

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

## 💻 How to Run

Install dependencies:

pip install numpy scikit-learn matplotlib seaborn


Run the notebook — it will:

Load and visualize the digits dataset

Train KNN models

Plot accuracy vs K

Show confusion matrix

Display sample predictions

## 📦 Deliverables

Jupyter Notebook

Accuracy vs K plot

Confusion matrix

Sample predictions on test images

## ✅ Final Outcome

Successfully classified handwritten digits using KNN.

## Author

Rushita Bhosale

Learned importance of feature scaling and K tuning.

Gained experience in distance-based classification and visualizing model performance.
