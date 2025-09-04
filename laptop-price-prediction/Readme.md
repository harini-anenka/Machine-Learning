# Laptop Price Prediction using Linear Regression

This project applies Linear Regression to predict laptop prices based on their specifications. The dataset includes features such as storage, screen resolution, and other hardware details.

## **Project Workflow**

### **Data Preparation**

Loaded the dataset.

Checked for missing values and duplicates → none found.

Converted and cleaned columns (e.g., storage split into SSD/HDD, resolution parsing).

Feature Engineering

Log-transformed the target variable (Price) to stabilize variance and improve regression performance.

Encoded categorical variables for model compatibility.

### **Model Training**

Implemented Linear Regression on processed features.

Trained and evaluated the model using performance metrics.

### **Model Evaluation**

Compared performance on original prices vs. log-transformed prices.

### **Final Results**

Original Model (no log transform):

**RMSE**: 206.34

**R²**: 0.98

**Log-Transformed Model:**

**Mean Squared Error** (MSE): 0.01

**R² Score**: 0.97 (Train) / 0.97 (Test)

## **Key Insights**

Linear Regression fits well overall, with very strong R² values.

Log transformation reduced MSE and made the model more stable across different price ranges.

High-end laptops are predicted more accurately compared to cheaper laptops.
