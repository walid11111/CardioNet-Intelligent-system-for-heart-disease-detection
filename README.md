# 🫀 CardioNet – Intelligent System for Heart Disease Detection

CardioNet is a machine learning-based intelligent system built to predict heart disease using real-world healthcare datasets. It provides an end-to-end ML pipeline covering everything from data loading and exploration to model training, evaluation, and deployment readiness.

---

## 🎯 Objective

To classify whether a patient is at high risk of developing a disease (e.g., heart disease, diabetes, or stroke) using demographic and medical data. The project involves binary and multi-class classification tasks using structured healthcare features.

---

## 📁 Project Workflow

1. **Google Drive Mounting:** Accessing dataset files from Google Drive.
2. **Data Loading:** Importing the dataset into a pandas DataFrame.
3. **Exploratory Data Analysis (EDA):**
   - Dataset shape and summary
   - Missing value analysis
   - Correlation heatmap
4. **Visualization:**
   - Histograms
   - Count plots
   - Heatmaps
5. **Preprocessing:**
   - Missing value imputation (using `SimpleImputer`)
   - Feature encoding
   - Data standardization
6. **Feature Engineering:**
   - Polynomial features
   - Feature selection (e.g., SelectKBest)
7. **Model Training:**
   - Logistic Regression
   - Decision Trees
   - Random Forest
   - XGBoost
   - Gradient Boosting
   - Neural Networks
8. **Evaluation Metrics:**
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - ROC-AUC
9. **Model Comparison:** Performance analysis of different models.

---

## 📊 Dataset Features

The dataset includes the following attributes:

- Age  
- Gender  
- Blood Pressure  
- Cholesterol Level  
- BMI (Body Mass Index)  
- Glucose Level  
- Heart Rate  
- Smoking and Alcohol History  
- Other diagnostic indicators  

📌 **Note:** Dataset is loaded from Google Drive and processed in the Colab environment.

---

## 📦 Libraries Used

- `pandas`, `numpy` – Data manipulation  
- `matplotlib`, `seaborn` – Data visualization  
- `scikit-learn` – ML models and utilities  
- `xgboost`, `lightgbm` – Advanced boosting algorithms  
- `tensorflow.keras` – For neural network modeling  

---

## 🚀 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Mount your Google Drive
3. Ensure your dataset is uploaded at the required path
4. Run all cells in sequence

---

## 📈 Results

Each model's performance is evaluated using accuracy, precision, recall, F1-score, and ROC-AUC to ensure robust comparison. Visual outputs such as confusion matrices and ROC curves are also included.

---

## 🤝 Contributing

Contributions, feedback, and suggestions are welcome! Please open an issue or submit a pull request.

---

## 📜 License

This project is for educational purposes only. If used for commercial deployment, ensure proper medical validation and compliance.

---

## 🙋‍♂️ Author

Made with ❤️ by **Walid Khan**

---

