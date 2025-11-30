# Real Estate price prediction using Linear Regression and XGBoosting and Comparative Analysis of model performance
Real Estate Price Prediction project comparing Linear Regression (simple baseline) and XGBoost (high-performance ensemble) for valuation. Focuses on data cleaning, feature engineering, hyperparameter tuning, and comparing accuracy to find the optimal model.


🏠 Real Estate Price Prediction: Linear Regression vs. XGBoostProject 
🎯 Project Goals
The objective of this project is twofold:To build robust regression models capable of predicting property sale prices based on various structural and locational features.To conduct a rigorous comparative analysis between a simple, interpretable model (Linear Regression) and a highly accurate, complex ensemble model (XGBoost) to assess the trade-off between model simplicity and predictive performance on a non-linear dataset.


🛠️ Methodology & Workflow
The project follows a standard Data Science lifecycle:
Data Acquisition: Loading the raw real estate transaction dataset.
Exploratory Data Analysis (EDA): Visualizing feature distributions, checking correlations, and identifying potential outliers.
Data Preprocessing: Handling missing values (Imputation). Managing categorical variables (One-Hot Encoding). Feature engineering (Creating new, insightful variables). Outlier detection and removal.
Model Training & Tuning: Training the baseline Linear Regression model. Training and optimizing the XGBoost Regressor using techniques like Grid Search CV for hyperparameter tuning.
Model Evaluation: Assessing performance using metrics such as MSE and R².
Comparative Analysis: Directly comparing the metrics and insights from both models to draw conclusions on the best approach for this prediction task.


🚀 Key Results & Conclusion
Based on the final evaluation metrics:

Model                                        R-squared (R²)                          Mean Squared Error (MSE)

Linear Regression (LR)                       0.5497                                  124.5794

XGBoost Regressor                            0.4526                                  151.4235

The Linear Regression (LR) model unexpectedly outperformed the XGBoost Regressor, achieving a higher R² score of 0.5497 and a lower Mean Squared Error of 124.5794.

Conclusion: In this specific analysis, the LR model proved to be the superior predictor. This suggests that the relationship between the features and the target price in the analyzed dataset may be more predominantly linear than initially assumed, or that the XGBoost model's configuration required further, extensive hyperparameter optimization to realize its potential gain over the simple linear baseline.

Tech Stack
Language: Python
  Core Libraries: pandas, numpy
  Visualization: matplotlib, seaborn
  Modeling: scikit-learn
  Boosting Framework: XGBoost
  
▶️ How to Run the ProjectClone the repository:
  git clone https://github.com/real-rayezwtkl/real_estate_price_prediction.git
  cd real_estate_price_prediction

  Run the analysis:
  Open the main Jupyter Notebook to execute the entire workflow from data cleaning to model comparison
