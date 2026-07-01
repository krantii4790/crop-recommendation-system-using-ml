# 🌱 Crop Recommendation System using Machine Learning

> **ML-powered crop recommendation based on soil nutrients and environmental conditions**

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-4C72B0)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📖 Project Overview

Agriculture plays a vital role in ensuring food security, and selecting the right crop for a given soil and climate is essential for maximizing productivity.

This project uses **Machine Learning** to recommend the most suitable crop based on soil nutrients and environmental conditions.

The system analyzes:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- Soil pH
- Rainfall

and predicts the best crop from **22 different crop varieties** using classification algorithms.

---

# 🎯 Objectives

- Build an intelligent crop recommendation system.
- Perform Exploratory Data Analysis (EDA).
- Compare multiple Machine Learning algorithms.
- Improve prediction accuracy using hyperparameter tuning.
- Help farmers make data-driven crop selection decisions.

---

# 📂 Dataset

The project uses the **Crop Recommendation Dataset**.

### Dataset Information

- Total Records: **2200**
- Features: **7**
- Target Classes: **22 Crop Types**

### Input Features

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall

### Target Variable

- Crop Label

---

# 🌾 Supported Crop Types

The model predicts one of the following crops:

- Rice
- Maize
- Chickpea
- Kidney Beans
- Pigeon Peas
- Moth Beans
- Mung Bean
- Black Gram
- Lentil
- Pomegranate
- Banana
- Mango
- Grapes
- Watermelon
- Muskmelon
- Apple
- Orange
- Papaya
- Coconut
- Cotton
- Jute
- Coffee

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 🛠 Machine Learning Algorithms

The following classification models were implemented and compared:

- Decision Tree Classifier
- Random Forest Classifier
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

The best-performing model was selected based on evaluation metrics.

---

# 📊 Exploratory Data Analysis

The project includes:

- Dataset Inspection
- Missing Value Analysis
- Duplicate Record Check
- Crop Distribution Analysis
- Correlation Heatmap
- Feature Distribution
- Pairplot Analysis
- Boxplot Analysis for Outlier Detection

---

# ⚡ Data Preprocessing

The preprocessing pipeline includes:

- Missing Value Verification
- Duplicate Removal
- Label Encoding
- Feature Scaling using StandardScaler
- Train-Test Split

---

# 📈 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Hyperparameter tuning was performed using **GridSearchCV** to optimize the Random Forest classifier.

---

# 📊 Results

The Random Forest Classifier achieved the best overall performance for crop prediction.

Key observations:

- High prediction accuracy across all crop classes.
- Random Forest outperformed the other classification models.
- Hyperparameter tuning further improved prediction performance.
- Soil nutrients and rainfall were among the most influential features.

---

# 📁 Project Structure

```text
Crop_Recommendation_System
│
├── Data
│   └── Crop_recommendation.csv
│
├── notebook
│   └── Crop_Recommendation_System.ipynb
│
├── requirements.txt
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Crop_Recommendation_System.git
```

Navigate to the project

```bash
cd Crop_Recommendation_System
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```text
Crop_Recommendation_System.ipynb
```

---

# 📦 Requirements

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

# 🌟 Key Features

- Intelligent Crop Recommendation
- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Multiple ML Model Comparison
- Hyperparameter Tuning
- Confusion Matrix Analysis
- Feature Importance Visualization
- High Prediction Accuracy

---

# 🎓 Learning Outcomes

This project demonstrates practical experience in:

- Data Preprocessing
- Exploratory Data Analysis
- Classification Algorithms
- Model Evaluation
- Hyperparameter Tuning
- Feature Engineering
- Machine Learning Workflow
- Agricultural AI Applications

---

# 🔮 Future Improvements

- Web Application using Flask or Streamlit
- Real-time Soil Sensor Integration
- Weather API Integration
- Fertilizer Recommendation System
- Crop Yield Prediction
- Disease Detection Integration
- Deep Learning-based Recommendation
- Mobile Application Deployment

---

# 👨‍💻 Author

**Krantikumar Patil** [krantikumar4211@gmail.com]

AI Engineer | Data Scientist | Java Full Stack Developer

---
