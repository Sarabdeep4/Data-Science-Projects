# Hotel Reservation Cancellation Prediction 🏨❌

## Overview
This classification project predicts whether a hotel booking will be canceled using customer and reservation details.

## Problem Statement
Hotel cancellations disrupt inventory and revenue forecasting. Accurate prediction allows for better planning and overbooking strategies.

## Dataset
Contains variables such as:
- Lead time
- Deposit type
- Market segment
- Booking changes
- Total of special requests
- Previous cancellations

## Approach
1. Categorical encoding & null value treatment
2. Data balancing using SMOTE
3. Models applied:
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier

4. Evaluation metrics:
   - Confusion matrix
   - Precision, Recall, F1-Score
   - ROC-AUC

## Results
Decision Tree Classifier gave the best accuracy of **84.7%** and balanced class prediction.

## Tools and Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## How to Run
1. Download this repo.
2. Open `Hotel Reservations Cancellation Prediction.ipynb`.
3. Ensure all libraries are installed via `requirements.txt`.

## 📈 Visuals

- Correlation heatmap

## 🤝 Contribution

Feel free to fork the repo and submit pull requests for improvements or experiments with other models.

## 📄 License

This project is open source and available under the MIT License.
