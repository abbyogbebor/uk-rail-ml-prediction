**PREDICTING SERVICE EFFICIENCY AND REVENUE PATTERNS IN UK NATIONAL RAIL TRANSPORT USING MACHINE LEARNING TECHNIQUES**

This project focuses on predicting train journey outcomes (On Time, Delayed, or Cancelled) using machine learning models. The dataset includes train schedules, journey details, ticket prices, and other operational features. 
The goal is to improve scheduling, minimize delays, optimize railway operations, and increase revenue.

**The dataset includes**

Date of Journey

Train Details (Train No, Train Name, Source, Destination, Station Code)

Timing Information (Departure Time, Arrival Time, Actual Arrival Time)

Fare Information (Price)

Status (Journey Status: On Time, Delayed, Cancelled)

**Data Preprocessing**

Handled missing values in Actual Arrival Time and Price

Converted date and time into meaningful features (e.g., Day, Month, Hour)

Calculated Delay Duration

Feature Engineering

Feature Selection

Treated outliers in ticket prices using the IQR method

Applied log transformation for skewed price distribution

Encoded categorical variables (Label Encoding + One-Hot Encoding)

**Exploratory Data Analysis (EDA)**

Distribution of ticket prices

Delay patterns across stations and time of day

Correlation between features and journey outcomes

Class balance of On Time vs Delayed vs Cancelled

**Machine Learning Models**

The following models were trained and evaluated:

XGBoost

CatBoost

LightGBM

Support Vector Machine (SVM)

Lasso

Ridge

Polynomail

Evaluation metrics include Accuracy, Precision, Recall, F1-score, Confusion Matrix, MAE, MSE, RMSE, and R²
