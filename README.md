

# 🚔 Crime Rate Prediction using Machine Learning 📊

## 🎯 Project Overview
The **Crime Rate Prediction** project aims to predict crime rates in different cities based on various factors such as historical crime data, crime types, and temporal aspects (time of occurrence). 

This project uses three different machine learning algorithms to build prediction models:
- **K-Nearest Neighbors (KNN)** 🤖
- **Random Forest** 🌳
- **KMeans Clustering** 📦

The goal is to analyze the relationship between various features and crime occurrences, enabling cities to better allocate resources for law enforcement and crime prevention.

---

## 🔧 Algorithms Used

### ✅ **K-Nearest Neighbors (KNN)**
A supervised learning algorithm used for classification tasks. The algorithm predicts the class of a data point based on the majority class of its nearest neighbors.

### 🌳 **Random Forest**
A versatile and powerful ensemble learning method for both classification and regression. It builds multiple decision trees and merges their results to improve accuracy and control overfitting.

### 📦 **KMeans Clustering**
An unsupervised learning algorithm used for clustering data into groups. KMeans identifies inherent groupings in the data, which can be useful for segmenting areas or types of crimes based on similar features.

---

## 📂 Dataset Description
The dataset contains various features related to criminal activities, including:

- **Crime Type:** The type of crime reported (e.g., burglary, assault).
- **City:** The city where the crime occurred.
- **Date and Time:** The date and time of the crime.
- **Crime Domain:** The broader category of the crime (e.g., violent crime, property crime).
- **Crime Reported:** Whether the crime was reported or not.
- **Other features:** Additional information such as victim age, weapon used, etc.

This data helps in understanding crime patterns and predicting crime rates in different locations.

---

## 📚 Libraries Used
Here are the essential Python libraries used in this project:

- 🐼 **Pandas:** For data manipulation and analysis.
- 🔢 **NumPy:** For numerical operations.
- 📊 **Matplotlib:** For creating static, interactive, and animated visualizations.
- 🎨 **Seaborn:** For statistical data visualization.
- ⚙️ **Scikit-learn:** For implementing ML algorithms (KNN, Random Forest, KMeans).
- 🔬 **SciPy:** For scientific and technical computing.
- 📈 **Plotly:** For creating interactive plots (if used).
- 💾 **Joblib:** For saving and loading trained ML models.

---

## 🔍 Model Training and Evaluation

### 🤖 **K-Nearest Neighbors (KNN)** 
- Used for classifying crime types based on historical data.
- Effective in predicting crime categories with high accuracy when data points are well-distributed.

### 🌳 **Random Forest**
- An ensemble method combining multiple decision trees.
- Robust and accurate, especially effective in handling large datasets.

### 📦 **KMeans Clustering**
- Applied to identify patterns and clusters of similar crimes.
- Helps in segmenting high-risk areas or crime types.

---

## 📈 Key Results or Findings
The implementation of the three algorithms provided the following insights:

- **KNN:** Showed good performance in predicting crime categories with high accuracy on well-distributed data.
- **Random Forest:** More robust and accurate in handling complex relationships between features, especially on large datasets.
- **KMeans Clustering:** Helped segment cities and crime types into clusters, revealing high-risk areas and similar crime patterns.

### 🔥 **Visualizations**
The project includes several visualizations, such as:
- 🌆 **Crime Rate by City**
- 📊 **Feature Distributions**
- 🔵 **KNN Decision Boundary**
- ⏳ **Crime Rates in Different Cities Over Time**

These visualizations enhance the understanding of the data and model performance.

---

## 🚀 How to Run the Project
1. Clone the repository:
```bash
git clone <repository_url>
```

2. Install the required libraries:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter Notebook or Python script:
```bash
jupyter notebook crime_rate_prediction.ipynb
```
or
```bash
python crime_rate_prediction.py
```

---

## 🙌 Contributing
Contributions are welcome! Feel free to:
- Submit pull requests.
- Report issues or suggest improvements.
- Share your insights or additional visualizations.

---

