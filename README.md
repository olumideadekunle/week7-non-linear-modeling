# Week 7 – Non-Linear Modeling in Machine Learning

This project is part of my Week 7 assessment, focusing on non-linear machine learning algorithms for both classification and regression tasks. The goal is to compare linear models with more powerful non-linear algorithms and evaluate their performance.

---

##  Project Overview

* **Datasets Used**:

  * One **classification dataset**
  * One **regression dataset**
* **Tasks Performed**:

  1. Data cleaning and preprocessing
  2. Exploratory Data Analysis (EDA)
  3. Built baseline **linear models**:

     * Linear Regression (regression)
     * Logistic Regression (classification)
  4. Built **non-linear models**:

     * Decision Trees
     * Random Forest
     * XGBoost
     * CatBoost
  5. Performed **k-fold cross-validation**
  6. Conducted **hyperparameter tuning**
  7. Compared results between linear vs. non-linear models



##  Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn (for visualization)
* XGBoost, CatBoost



##  How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/<your-username>/week7-non-linear-modeling.git
   cd week7-non-linear-modeling
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:

   ```bash
   jupyter notebook week7_non_linear_modeling.ipynb
   ```



## 📈 Results & Observations

* **Linear Models**: Provided a simple baseline but struggled with complex relationships.
* **Non-Linear Models**:

  * Decision Trees captured non-linear patterns but overfitted.
  * Random Forest improved generalization.
  * XGBoost & CatBoost achieved the **best performance** after tuning.
* **Key Insight**: Non-linear models significantly outperformed linear models on both classification and regression tasks.



##  Repository Structure

```
week7-non-linear-modeling/
│── week7_non_linear_modeling.ipynb   # Main Colab notebook
│── regression_dataset.csv            # Regression dataset
│── classification_dataset.csv        # Classification dataset
│── requirements.txt                  # Dependencies
│── README.md                         # Project documentation
```



##  License

This project is licensed under the **MIT License** – feel free to use and adapt with attribution.



 This repo is part of my growing Machine Learning portfolio.
