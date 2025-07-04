📊 **IMDB Shows Rating Prediction**

A complete data science pipeline for predicting IMDB ratings of top TV shows using advanced regression models, with a focus on CatBoostRegressor and model interpretability.


🚀 **Project Overview**

This project demonstrates the end-to-end process of:

* Importing, cleaning, and preprocessing show data (shows.csv)

* Exploratory Data Analysis (EDA) and feature engineering

* Building, tuning, and comparing regression models (CatBoost, Random Forest, Gradient Boosting, Linear Regression)

* Interpreting results with feature importance analysis
  

🛠️ **Key Steps**

1. **Data Cleaning**

* Handled missing values and converted text fields (e.g., imbd_votes, duration) to numeric

* Dropped irrelevant and duplicate records

2. **Feature Engineering**

* Multi-hot encoding for genres

* Categorized years into decade bins

* One-hot encoding for year ranges

3. **EDA & Visualization**

* Explored data structure, distributions, and correlations

* Visualized relationships (votes vs rating, genre-based analysis, etc.)

4. **Model Building**

* Compared Linear Regression, Random Forest, Gradient Boosting, and CatBoostRegressor

* Used GridSearchCV for CatBoost hyperparameter optimization

5. **Model Interpretation**

* Extracted and visualized top 10 feature importances for IMDB rating prediction

  

📈 **Results**

**Best Model**: CatBoostRegressor (R² ≈ 0.84)

**Top Features**: rank, imbd_votes, duration_minutes, decade dummies, key genres

**Note:**

The model's accuracy can be further improved by fine-tuning the hyperparameters, such as learning_rate, depth, and n_estimators. This is especially beneficial for handling more complex data relationships.


🏁 **How to Run**

Place shows.csv in the data/ directory.

Run the notebook:

Open and execute Mini_Project:IMDB Rating Prediction.ipynb.


🔍 **Key Learnings**

* Data cleaning and feature engineering are crucial for tabular ML tasks.

* CatBoostRegressor is highly effective for categorical-rich datasets.

* Model interpretation (feature importance) helps understand key predictors.
