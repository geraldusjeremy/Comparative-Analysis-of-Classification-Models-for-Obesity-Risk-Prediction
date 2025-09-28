
# Comparative Analysis of Classification Models for Obesity Risk Prediction

Project Overview

This project tackles the multi-class classification problem of predicting obesity levels based on a comprehensive dataset of personal and lifestyle factors. The primary objective was to build, evaluate, and compare the performance of two powerful classification algorithms: **Random Forest** and **XGBoost**.

The project lifecycle included several key stages:
- **Data Cleaning & Preprocessing:** Handled inconsistencies and missing values within the dataset. Categorical features were transformed using a combination of Label, Ordinal, and One-Hot Encoding to prepare the data for modeling.
- **Model Training:** Implemented both a RandomForest Classifier and an XGBoost Classifier.
- **Hyperparameter Tuning:** Utilized **GridSearchCV** to systematically find the optimal hyperparameters for both models, significantly boosting their predictive accuracy.
- **Performance Evaluation:** The tuned models were evaluated using detailed classification reports, with the final XGBoost model achieving an outstanding **accuracy of 96%**.
- **Feature Importance Analysis:** The project concludes by visualizing the most influential features that contribute to the prediction of obesity levels, providing valuable insights into the key drivers of the model's decisions.

Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn (for `RandomForestClassifier`, `GridSearchCV`, preprocessing)
- XGBoost
- Matplotlib
- Seaborn

Dataset
The dataset used is `1B.tsv`, which contains various attributes of individuals, such as age, gender, eating habits, physical activity, and transportation methods.

How to Run this Project
1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/geraldusjeremy/Comparative-Analysis-of-Classification-Models-for-Obesity-Risk-Prediction.git](https://github.com/geraldusjeremy/Comparative-Analysis-of-Classification-Models-for-Obesity-Risk-Prediction.git)
