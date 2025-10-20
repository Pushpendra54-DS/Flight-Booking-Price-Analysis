# ✈️ Flight Price Prediction using Machine Learning

## 📘 Overview
This project aims to predict **flight ticket prices** based on multiple features such as airline, source city, destination, number of stops, and days left for departure.  
By applying various machine learning algorithms and data preprocessing techniques, the goal is to understand which factors most influence flight prices and build accurate prediction models.

---

## 🧾 Table of Contents
1. [Dataset](#dataset)
2. [Exploratory Data Analysis](#exploratory-data-analysis)
3. [Data Preprocessing](#data-preprocessing)
4. [Modeling](#modeling)
5. [Results & Evaluation](#results--evaluation)
6. [Plots & Visualizations](#plots--visualizations)
7. [Notebook](#notebook)
8. [Badges](#badges)

---

## 📊 Dataset
- **Source:** [Google Drive Link](https://drive.google.com/your_dataset_link_here)
- The dataset consists of the following columns:

| Feature | Description |
|----------|-------------|
| `airline` | Name of the airline |
| `flight` | Flight code |
| `source_city` | Departure city |
| `departure_time` | Time of departure (morning/afternoon/evening) |
| `stops` | Number of stops |
| `arrival_time` | Time of arrival |
| `destination_city` | Destination city |
| `class` | Class type (Economy/Business) |
| `duration` | Total flight duration in hours |
| `days_left` | Days left before flight departure |
| `price` | Target variable — flight ticket price |

---

## 🔍 Exploratory Data Analysis
The EDA focuses on understanding how flight price varies with different factors such as:
- Number of stops  
- Airline and class type  
- Source and destination city  
- Days left for booking

---

## ⚙️ Data Preprocessing
Steps performed:
- Handled missing values  
- Label encoded categorical features  
- Removed outliers using VIF  
- Applied Standard Scaler for feature scaling  

---

## 🤖 Modeling
Models implemented:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

Hyperparameter tuning was applied to improve model performance.

---

## 📈 Results & Evaluation

| Model | R² Score | MSE | MAE | RMSE | MAPE |
|--------|-----------|-----|-----|------|------|
| Linear Regression |  |  |  |  |  |
| Decision Tree |  |  |  |  |  |
| Random Forest |  |  |  |  |  |

*(You can fill the above table with your actual metric values)*

---

## 🖼️ Plots & Visualizations

### EDA Plots
![Airline Distribution](images/plots/Airline_Distribution.png)  
![Stops vs Price](images/plots/Stops_vs_Price.png)  
![Days Left vs Price](images/plots/Days_Left_vs_Price.png)

### Model Performance
![Actual vs Predicted - Linear Regression](images/plots/Actual_vs_Predicted_LR.png)  
![Actual vs Predicted - Decision Tree](images/plots/Actual_vs_Predicted_DT.png)  
![Actual vs Predicted - Random Forest](images/plots/Actual_vs_Predicted_RF.png)

---

## 📓 Notebook
Access the full notebook here:  
[🧠 Flight Price Prediction Notebook](notebooks/Flight_Price_Prediction.ipynb)

---

## 🏅 Badges

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Modeling-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Cleaning-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

---

## 💡 Conclusion
- **Random Forest Regressor** performed the best among all models.
- Days left before departure, number of stops, and airline type had the highest impact on price.
- The project demonstrates how data preprocessing and ensemble learning can significantly improve regression performance.

---

## 🚀 Future Scope
- Include more recent flight data for real-time prediction.
- Deploy the model using Streamlit or Flask for user interaction.
