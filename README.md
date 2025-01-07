# Day-1 Linear-Regression-Multi-Feature-Housing-Price-Prediction

## **Project Overview**
- Predict housing prices using the **California Housing Dataset**.
- Implement **Linear Regression**, **Ridge Regression**, and **Lasso Regression**.
- Optimize models using **GridSearchCV** for hyperparameter tuning.
- Evaluate models with metrics like **Mean Squared Error (MSE)** and **R² Score**.

---

## **Dataset**
- **Source:** `fetch_california_housing` from Scikit-learn.
- **Features:**
   - `MedInc`: Median income in the area.
   - `HouseAge`: Average age of houses.
   - `AveRooms`: Average number of rooms per household.
   - `AveBedrms`: Average number of bedrooms per household.
   - `Population`: Population in the area.
   - `AveOccup`: Average number of people per household.
   - `Latitude`: Latitude of the area.
   - `Longitude`: Longitude of the area.
- **Target Variable:** Median house value (`Target`).

---

##  **Technologies Used**
- **Programming Language:** Python
- **Libraries:**
   - `pandas` – Data manipulation and analysis.
   - `numpy` – Numerical computations.
   - `matplotlib` & `seaborn` – Data visualization.
   - `scikit-learn` – Machine Learning models and utilities.
   - `joblib` – Model saving.

---

##  **Project Workflow**

### **1. Exploratory Data Analysis (EDA)**
- Checked for **missing values**.
- Performed **summary statistics** analysis.
- Visualized feature relationships using:
   - **Correlation Heatmap**
   - **Pair Plots**

### **2. Data Preprocessing**
- **Feature Selection:** Selected predictor (`X`) and target (`y`) variables.
- **Train-Test Split:** 80% training, 20% testing.
- **Data Scaling:** Standardized features using **StandardScaler**.

### **3. Model Building**
- **Linear Regression:** Baseline predictive model.
- **Ridge Regression:** L2 Regularization to handle multicollinearity.
- **Lasso Regression:** L1 Regularization for feature selection.
- **GridSearchCV:** Hyperparameter tuning for Ridge and Lasso (`alpha` parameter).

### **4. Model Evaluation**
- **Mean Squared Error (MSE):** Measures prediction error.
- **R² Score:** Measures model fit.
- **Performance Comparison:** Linear, Ridge, and Lasso models.

### **5. Visualization**
- **Scatter Plot:** Compared actual vs predicted prices using Linear Regression.
