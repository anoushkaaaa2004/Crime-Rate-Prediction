# 🚔 Crime Rate Prediction using Machine Learning 📊

## 🎯 Project Overview

This project aims to predict whether a **criminal case will be closed (Yes/No)** using machine learning. It analyzes crime data from Indian cities based on features like crime type, victim details, location, and weapon used. 

The project includes the following machine learning algorithms:

- K-Nearest Neighbors (KNN) 🤖
- Random Forest 🌳
- Logistic Regression 📈
- Support Vector Machine (SVM) 🧠
- Decision Tree 🌲
---

## 🔧 Algorithms Used

### ✅ K-Nearest Neighbors (KNN)
- Predicts crime categories based on nearest neighbors.
- Good for well-distributed and structured datasets.

### 🌳 Random Forest
- An ensemble of decision trees for classification.
- Handles non-linear data and large datasets effectively.

### 📈 Logistic Regression
- Binary classification to predict **Case Closed: Yes (1) / No (0)**.
- Explains feature impact via coefficients.
- Used for its simplicity, interpretability, and performance in binary classification.

### 🧠 Support Vector Machine (SVM)
- Finds the **optimal hyperplane** that separates classes with maximum margin.
- Works well with both linear and non-linear data using kernel tricks.
- Provides robust performance in high-dimensional feature spaces.

### 🌲 Decision Tree
- Splits data into branches based on feature values to make decisions.
- Easy to interpret and visualize.
- Handles both numerical and categorical features efficiently.
- Can capture non-linear patterns but may overfit without tuning (use pruning or max_depth).

---

## 📂 Dataset Description

The dataset includes various features:
- **City**
- **Crime Description**
- **Crime Domain**
- **Victim Gender**
- **Victim Age**
- **Weapon Used**
- **Police Deployed**
- **Case Closed** (Target variable)

### 🛠️ Preprocessing Includes:
- Dropping unnecessary columns (e.g., date/time fields)
- Handling missing values
- Label encoding of categorical features

---

## 📚 Libraries Used

- 🐼 `pandas`
- 🔢 `numpy`
- ⚙️ `scikit-learn`
- 📊 `matplotlib`
- 🎨 `seaborn`
- 💾 `pickle`

---

## 🔍 Model Training & Evaluation

### 1. Preprocessing
- Label encoding for `City`, `Crime Type`, `Victim Gender`, etc.
- Feature-target split with `Case Closed` as target

### 2. Train-Test Split
```python
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
```

### 3. Model Training
```python
# Logistic Regression
model_lr = LogisticRegression(max_iter=1000)
model_lr.fit(X_train, y_train)

# SVM
model_svm = SVC(kernel='rbf', probability=True)
model_svm.fit(X_train, y_train)

# Decision Tree
model_dt = DecisionTreeClassifier(max_depth=5, random_state=42)
model_dt.fit(X_train, y_train)
```

### 4. Evaluation

#### 📋 Metrics:
- ✅ **Confusion Matrix**
- 📌 **Classification Report**
- 📉 **ROC Curve** with AUC score

#### 📊 Visualizations:

- ✅ **Confusion Matrix**  
- 📌 **Feature Importance** (model coefficients)  
- 🔁 **Case Closed Distribution**  
- 🔫 **Top 10 Crime Types**  
- 🗺️ **Crime Domain by City Heatmap**  
- 👥 **Victim Age Distribution**  
- 📊 **Pair Plot of Key Features**  
- 📉 **ROC Curve**

---

## 💾 Model Saving

After training:
```python
with open('models/crime_logistic_model.pkl', 'wb') as file:
    pickle.dump(model, file)
```

---

## 🚀 How to Run the Project

1. **Clone the repository**:
```bash
git clone https://github.com/yourusername/crime-rate-prediction.git
cd crime-rate-prediction
```

2. **Install dependencies**:
```bash
pip install -r requirements.txt
```

3. **Run the notebook**:
```bash
jupyter notebook notebooks/crime_prediction_logistic.ipynb
```

---


