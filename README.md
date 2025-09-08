# Heart Disease Prediction Project

## 📌 Overview
This project analyzes heart disease dataset and builds machine learning models to predict the likelihood of heart disease.  
It includes **exploratory data analysis (EDA)** with visualizations and multiple ML models such as:

- Random Forest Classifier
- Logistic Regression (with Grid Search)
- XGBoost Classifier (with Grid Search)
- Support Vector Machine (with Grid Search)

## 📊 Features
1. **Exploratory Data Analysis (EDA):**
   - Target distribution
   - Age vs Heart Disease
   - Gender vs Heart Disease
   - Correlation heatmap
   - Chest Pain type analysis
   - Heart Rate and Oldpeak analysis
   - Pairplot visualization

2. **Machine Learning Models:**
   - Random Forest Classifier
   - Logistic Regression with hyperparameter tuning (GridSearchCV)
   - XGBoost Classifier with hyperparameter tuning (GridSearchCV)
   - Support Vector Machine with scaling and hyperparameter tuning

3. **Evaluation Metrics:**
   - Classification Report (Precision, Recall, F1-score)

## ⚙️ Requirements
- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost
- numpy

Install dependencies:
```bash
pip install pandas matplotlib seaborn scikit-learn xgboost numpy
```

## 🚀 Usage
1. Clone the repository or extract the zip file.
2. Place the `heart.csv` dataset inside the project folder.
3. Run the script:
```bash
python main.py
```

## 📂 Project Structure
```
heart-disease-ml/
│── main.py       # Main Python script with EDA & ML models
│── README.md     # Project documentation
│── heart.csv     # Dataset (not included in repo)
```

## 📝 Notes
- Ensure `heart.csv` is available in the project directory.
- You can modify ML models or visualization parameters for further analysis.

---
💡 *This project is designed for learning purposes and demonstrates end-to-end data science workflow.*
