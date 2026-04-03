# 🧠 Advanced Customer Segmentation Project

This project focuses on customer segmentation using Machine Learning techniques and predicting customer spending behavior. It uses K-Means clustering for segmentation and Random Forest for regression.

---

## 🚀 Project Overview

The goal of this project is to:
- Segment customers into different groups based on income and spending habits
- Analyze customer behavior using data visualization
- Predict customer spending score using machine learning

---

## 📊 Dataset

- Dataset: Mall Customers Dataset
- Features:
  - Customer ID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas & NumPy (Data Processing)
- Matplotlib & Seaborn (Visualization)
- Scikit-learn (Machine Learning)

---

## 🔍 Project Steps

### 1. Data Preprocessing
- Label Encoding for categorical data
- Feature scaling using StandardScaler

### 2. Exploratory Data Analysis (EDA)
- Age distribution
- Income vs Spending Score
- Gender vs Spending behavior
- Correlation heatmap

### 3. Customer Segmentation
- K-Means Clustering
- Elbow Method to find optimal clusters
- Cluster visualization

### 4. Cluster Profiling
- Analyzing average values of each cluster

### 5. Spending Prediction
- Random Forest Regressor
- Model evaluation using:
  - R² Score
  - RMSE

---

## 📈 Results

- Successfully segmented customers into 5 clusters
- Built a prediction model for spending score
- Achieved good accuracy using Random Forest

---

## 📌 Key Insights

- Customers with high income and high spending form a valuable segment
- Different clusters show distinct purchasing behavior
- Machine learning helps in targeted marketing strategies

---

## 🧑‍💻 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Navigate to folder
cd your-repo-name

# Install dependencies
pip install -r requirements.txt

# Run the script
python your_script_name.py
