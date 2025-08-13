# 🏠 House Price Prediction — Machine Learning Project

This project focuses on predicting house prices based on features such as square footage, number of bedrooms, location, and more.
The workflow includes **data cleaning**, **exploratory data analysis (EDA)**, **feature engineering**, **model training**, and **evaluation**.



## 📌 Instructions Followed

* Cleaned and preprocessed the dataset (handled missing values, encoded categorical variables, normalized numerical values).
* Performed **EDA** to identify relationships between house features and price.
* Split data into training and validation sets.
* Trained regression models (Random Forest Regressor).
* Evaluated models using:

  * **Root Mean Squared Error (RMSE)**
  * **Mean Absolute Error (MAE)**
* Visualized actual vs predicted prices.
* Selected the best-performing model.

---

## 📊 Exploratory Data Analysis (EDA) — Key Observations

* Price tends to increase with **larger square footage** and **better location ratings**.
* **Number of bedrooms** alone is not a strong predictor without considering house size.
* Some categorical variables like **neighborhood** and **house style** have a significant effect on price.
* Removed or adjusted extreme outliers to improve model stability.

---

## ⚙️ Models and Evaluation
### 3. **Random Forest Regressor** 

* Improved accuracy by averaging multiple decision trees.
* Provided feature importance rankings.

---

## 📈 Metrics Used

* **RMSE** 
* **MAE**

---

## 📦 Libraries Used

* **pandas** → Data manipulation and preprocessing.
* **numpy** → Numerical computations.
* **matplotlib & seaborn** → Data visualization.
* **scikit-learn** → Model building and evaluation.

---

## 📌 Conclusion

This project provided hands-on experience in:

* Real estate data cleaning and preprocessing.
* Identifying trends in property prices.
* Training and evaluating regression models.
* Understanding which features most influence house prices.


## 📁 Dataset
Publically available dataset on kaggle regarding house price prediction.


The dataset used in this project is based on publicly available house price data (e.g., Kaggle's Ames Housing dataset or similar).

