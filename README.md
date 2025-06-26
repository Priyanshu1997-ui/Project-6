# 🏪 Rossmann Pharmaceutical Store Sales Forecasting

Welcome to the **Rossmann Sales Forecasting** project, developed by **NextHikes IT Solutions**.  
This project is designed to **predict daily sales** across multiple pharmaceutical retail stores using **machine learning** and **deep learning** techniques, and provide insights through a **user-friendly web interface**.

---

## 📌 Project Objective

To forecast sales across various Rossmann stores by:
- Understanding customer purchasing behavior
- Building accurate ML and DL models
- Deploying predictions via a web interface

---

## 📊 Project Pipeline

### 🔍 1. Exploratory Data Analysis (EDA)
- Analyze customer behavior before, during, and after holidays
- Visualize impacts of promotions, store types, and competitors
- Explore seasonal trends (Christmas, Easter, etc.)
- Treat missing values, outliers, and visualize correlations

---

### 🔧 2. Data Preprocessing
- Feature engineering from `Date` (e.g., holiday flags, weekends, month-start/mid/end)
- Apply encoding (Label/OneHot) and scaling for model compatibility

---

### 🤖 3. Model Building

#### 🧮 Machine Learning
- **Model:** Random Forest Regressor (via Scikit-learn Pipelines)
- **Loss Function:** Custom loss function used and documented

#### 🔗 Deep Learning
- **Model:** LSTM (Long Short-Term Memory) using TensorFlow/Keras
- Focused on sequential sales forecasting

---

### 📈 4. Model Evaluation
- Analyze feature importance
- Perform confidence interval analysis
- Visualize residuals and predictions vs. actual sales

---

### 🧠 5. Model Serialization & MLOps

- Model saved with **timestamps** for version tracking
- **MLflow** used for:
  - Experiment tracking
  - Parameter logging
  - Model versioning and reproducibility
- **DVC (Data Version Control)** for dataset tracking

---

### 🌐 6. Web App Deployment

- **Framework:** Flask
- **Features:**
  - Input by Store ID or CSV Upload (with Date, Promo, Holiday, etc.)
  - Returns predicted sales and customer count
  - Allows CSV export of results

---

## 🚀 Tech Stack

- **Python**, **Pandas**, **NumPy**
- **Scikit-learn**, **TensorFlow/Keras**
- **MLflow**, **DVC**
- **Flask** for the web interface
- **Matplotlib**, **Seaborn** for visualization
