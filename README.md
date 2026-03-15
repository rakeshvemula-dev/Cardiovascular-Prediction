# 🫀 Cardiovascular Disease Prediction

A machine learning project that predicts cardiovascular disease using multiple classification algorithms — comparing accuracy across SVM, KNN, Decision Trees, Logistic Regression, and Random Forest to identify the best-performing model.

---

## 📌 Overview

Cardiovascular disease accounts for 28.1% of global fatalities, making early and accurate diagnosis critical. This project applies supervised machine learning to a real cardiac dataset to build a reliable prediction system — enabling prompt diagnosis and potentially saving lives through data-driven insights.

---

## 🎯 Objectives

- Perform data preprocessing and exploratory data analysis (EDA)
- Visualize feature distributions and correlations
- Train and compare multiple ML classification models
- Evaluate accuracy levels across all models
- Build the best-performing model for heart disease detection

---

## 🗂️ Dataset

- **Source:** `cardio_train.csv`
- **Features include:** Age, gender, height, weight, blood pressure (systolic/diastolic), cholesterol, glucose, smoking, alcohol intake, physical activity
- **Target:** Binary classification — presence or absence of cardiovascular disease

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Data visualization |
| Scikit-learn | ML models, preprocessing, evaluation |
| Jupyter Notebook | Development environment |

---

## 📊 Project Pipeline

```
Raw Dataset (cardio_train.csv)
    ↓
Data Preprocessing (null handling, outlier removal, scaling)
    ↓
Exploratory Data Analysis (distributions, correlations)
    ↓
Correlation Matrix Visualization
    ↓
Model Training (SVM, KNN, DT, LR, RF)
    ↓
Accuracy Comparison
    ↓
Best Model Selection & Final Prediction System
```

---

## 🤖 Models Compared

| Model | Description |
|---|---|
| Support Vector Machine (SVM) | Finds optimal hyperplane for classification |
| K-Nearest Neighbor (KNN) | Classifies based on proximity to neighbors |
| Decision Tree (DT) | Rule-based tree structure for decisions |
| Logistic Regression (LR) | Probabilistic linear classifier |
| Random Forest (RF) | Ensemble of decision trees |

---

## 🔍 Key Steps

### 1. Data Preprocessing
- Handled missing values and removed outliers
- Scaled numerical features using StandardScaler
- Split dataset into training and test sets

### 2. Exploratory Data Analysis
- Visualized distributions of all health indicators
- Plotted feature relationships with the target variable
- Generated correlation heatmap to identify key predictors

### 3. Model Training & Evaluation
- Trained all five classifiers on the same dataset
- Evaluated using accuracy score, confusion matrix
- Compared performance to select the best model

### 4. Final Model
- Selected best-performing algorithm based on accuracy
- Built final prediction system for cardiovascular disease detection

---

## 📈 Sample Visualizations

> Correlation matrix, feature distributions, model accuracy comparison charts available in the notebook.

---

## 🚀 How To Run

```bash
# Clone the repository
git clone https://github.com/rakeshvemula-dev/Cardiovascular-Prediction.git
cd Cardiovascular-Prediction

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Launch notebook
jupyter notebook
```

---

## 💡 Key Insights

- Blood pressure and cholesterol levels are the strongest predictors of cardiovascular disease
- Random Forest outperformed all other models with the highest accuracy
- Age and weight show strong positive correlation with disease presence

---

## 🔮 Future Improvements

- [ ] Deploy as a web app with FastAPI for real-time predictions
- [ ] Add SHAP values for model explainability
- [ ] Experiment with XGBoost and deep learning approaches
- [ ] Integrate with a patient data input form

---

## 👤 Author

**Rakesh Vemula**
- GitHub: [@rakeshvemula-dev](https://github.com/rakeshvemula-dev)
- LinkedIn: [iamrakeshvemula](https://linkedin.com/in/iamrakeshvemula)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
