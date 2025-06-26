# Diamond Price Prediction 💎

## Overview
This project predicts the price of diamonds based on their physical attributes using various regression models.

## Problem Statement
Accurately predicting diamond prices can help buyers and sellers make data-driven decisions in the gem industry.

## Dataset
The dataset contains over 53,000 diamond entries with features like:
- Carat
- Cut
- Color
- Clarity
- Depth
- Table
- Dimensions (x, y, z)

## Approach
1. **EDA** and **visualization** to understand data distribution.
2. Preprocessing included:
   - Handling missing values
   - Label Encoding for categorical features
   - Feature scaling
3. Model Building:
   - Decision Tree Regressor
   - Random Forest Regressor
4. Performance Evaluation using RMSE, MAE, and R² Score.

## Results
The best performing model was `Random Forest Regressor` with an R² Score of over **0.98** on the test data.

## Tools and Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## How to Run
1. Clone this repository.
2. Install dependencies from `requirements.txt`.
3. Run `Diamond Price Prediction.ipynb`.

## 📈 Visuals

- Correlation heatmap

## 🤝 Contribution

Feel free to fork the repo and submit pull requests for improvements or experiments with other models.

## 📄 License

This project is open source and available under the MIT License.
