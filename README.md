# Diamonds_price_predicition
# 💎 Diamond Price Prediction: End-to-End Machine Learning Pipeline

## 📌 Project Overview
This project implements a complete Machine Learning pipeline to accurately predict the price of diamonds based on their physical characteristics (Carat, Cut, Color, Clarity, and Dimensions). 

Built with scalability and real-world application in mind, this regression model is designed to assist jewelers, appraisers, and e-commerce platforms in automating the diamond valuation process with high precision.

## 🚀 Key Highlights & Technical Achievements
*   **Data Leakage Resolution:** Successfully identified and eliminated a critical data leakage issue (index correlation via an unformatted column), ensuring the model evaluates real-world features rather than memorizing row orders.
*   **Algorithm Optimization:** Progressed through multiple predictive algorithms (Linear Regression, Support Vector Regression, Decision Trees) before selecting an ensemble method for final deployment.
*   **High Accuracy:** The final Random Forest model achieved an **R-squared score of 98.16%**, meaning it successfully explains over 98% of the variance in diamond pricing.

## 📊 Model Performance
After rigorous training and testing across a dataset of ~50,000 diamonds, the final **Random Forest Regressor** yielded the following metrics:
*   **R-squared ($R^2$):** `98.16%`
*   **Root Mean Squared Error (RMSE):** `$540.99` 

*(Note: An RMSE of ~$541 is highly competitive given the massive variance in diamond prices, which can range from $300 to over $18,000).*

### Feature Importance Insights
The model's decision-making process was analyzed to determine the most critical factors in diamond pricing:
1.  **Carat (Weight):** 61.6% impact
2.  **Y-Dimension:** 27.3% impact
3.  **Clarity:** 6.3% impact
4.  **Color:** 3.1% impact

## 🛠️ Built With
*   **Python:** The core programming language used.
*   **Scikit-Learn:** For model building, scaling, and evaluation metrics.
*   **Pandas & NumPy:** For data manipulation and mathematical operations.
*   **Joblib:** For serializing and saving the final model for production deployment.

## 📂 Repository Structure
*   `diamond_price_prediction.ipynb`: The complete Jupyter Notebook containing EDA, preprocessing, training, and evaluation.
*   `diamond_model.pkl`: The saved, production-ready Random Forest model.
*   `requirements.txt`: List of dependencies required to run the pipeline.
*   `README.md`: Project documentation.

## ⚙️ How to Use
To run this project locally or integrate the model into a web application:

1. Clone the repository:
   ```bash
   git clone https://github.com/Mariam-mostafa3/Diamonds_price_predicition.git 
