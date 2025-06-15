# E-Commerce Product Delivery Prediction 📦

## Overview
This classification project predicts whether an e-commerce product will be delivered on time.

## Problem Statement
Late deliveries impact customer satisfaction and logistics planning. This project helps predict delivery status to optimize operations.

## Dataset
The dataset includes features such as:
- Warehouse block
- Mode of shipment
- Customer care calls
- Product importance
- Weight, Discount, Cost
- Prior purchase behavior

## Approach
1. Preprocessing categorical features using One-Hot Encoding.
2. Checking for class imbalance and applying SMOTE.
3. Models Used:
   - Decision Tree Classifier
   - Random Forest Classifier
   - Logistic Regression
   - K Nearest Neighbors
4. Evaluation Metrics:
   - Accuracy, Precision, Recall, F1-Score, Confusion Matrix

## Results
The Decision Tree Classifier achieved the best results with **accuracy over 69%** and good recall for the 'late' class.

## Tools and Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## How to Run
1. Install dependencies from `requirements.txt`.
2. Run `E-Commerce Product Delivery Prediction.ipynb`.

## 📈 Visuals

- Correlation heatmap

## 🤝 Contribution

Feel free to fork the repo and submit pull requests for improvements or experiments with other models.

## 📄 License

This project is open source and available under the MIT License.
