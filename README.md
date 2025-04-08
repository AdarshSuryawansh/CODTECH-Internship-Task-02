# 🧠 Predictive Analysis using Machine Learning

## 📌 Objective
To build a machine learning model that can predict outcomes based on a real-world dataset. This project demonstrates a complete data science workflow including data preprocessing, feature selection, model training, and evaluation. The focus is on regression analysis to predict housing prices.

---

## 📂 Dataset Used: California Housing Dataset
The dataset is provided by `sklearn.datasets` and contains housing data from various districts in California.

### 🔑 Features:
- `MedInc`: Median income in block (in $10,000s)
- `HouseAge`: Median age of houses in the block
- `AveRooms`: Average number of rooms per household
- `AveBedrms`: Average number of bedrooms per household
- `Population`: Population of the block
- `AveOccup`: Average number of household members
- `Latitude`: Geographical latitude
- `Longitude`: Geographical longitude

### 🎯 Target:
- `Target`: Median house value (in $100,000s)

---

## 🧪 Workflow Steps

### 1. Data Loading & Exploration
- Loaded California Housing dataset using `sklearn`
- Converted to a Pandas DataFrame
- Viewed descriptive statistics and correlations

### 2. Feature Selection
- Used correlation heatmap to understand feature relationships
- Retained all features for modeling due to good correlation

### 3. Data Preprocessing
- Applied `StandardScaler` for normalization
- Split data into training and testing sets using `train_test_split`

### 4. Model Training
- Trained a **Random Forest Regressor** with 100 trees

### 5. Evaluation
- Evaluated using:
  - **Root Mean Squared Error (RMSE)**
  - **R² Score**
- Plotted **actual vs predicted** values to visualize performance

---

## 🧰 Tools & Technologies
- **Language**: Python  
- **Libraries**: pandas, numpy, seaborn, matplotlib, scikit-learn  
- **Model**: Random Forest Regressor  
- **Metrics**: RMSE, R² Score  
- **Visualization**: Heatmap, scatter plot  

---

## ✅ Outcome
The notebook successfully demonstrates how to apply machine learning for predictive analysis. The model shows reliable accuracy and helps predict house prices based on socio-economic and geographical features.

---

## 📁 File Structure
