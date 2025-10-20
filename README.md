# ✈️ Flight Booking Price Analysis using Machine Learning

## 📘 Overview
This project predicts **flight ticket prices** based on factors such as airline, source and destination cities, number of stops, class, and days left before departure.  
By exploring data patterns and implementing multiple regression models, the project identifies key factors influencing ticket prices and builds an accurate predictive system.

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
9. [Owner](#owner)

---

## 📊 Dataset
The dataset is large, so it has been uploaded to Google Drive.

📂 **Access Dataset:**  
👉 [Click Here to Download Dataset](https://drive.google.com/file/d/1Mh9-pGHUPuwXkZckud2QRovx4ecMAYR6/view?usp=drive_link)

📁 **Path in Repository:**  
`Flight-Booking-Price_Analysis/data/Dataset/.gitkeep`

**Features Included:**

| Feature | Description |
|----------|-------------|
| `airline` | Name of the airline |
| `flight` | Flight code |
| `source_city` | Departure city |
| `departure_time` | Time of departure (Morning/Afternoon/Evening) |
| `stops` | Number of stops |
| `arrival_time` | Time of arrival |
| `destination_city` | Destination city |
| `class` | Class type (Economy/Business) |
| `duration` | Total duration of flight |
| `days_left` | Number of days left before departure |
| `price` | Target variable (Flight Ticket Price) |

---

## 🔍 Exploratory Data Analysis
Explored key insights such as:
- How **airline** and **class** impact ticket prices  
- Relationship between **days left before departure** and **price**  
- Correlation between numerical features  
- Flight duration and its effect on cost  

---

## ⚙️ Data Preprocessing
Steps performed:
- Removed unnecessary columns  
- Handled missing values  
- Label encoded categorical variables  
- Standardized numerical features  
- Checked multicollinearity using VIF  
- Outlier detection and removal  

---

## 🤖 Modeling
Models Implemented:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

Hyperparameter tuning was applied to enhance model accuracy.

---

## 📈 Results & Evaluation

| Model | R² Score | MAE | MAPE | MSE | RMSE |
|--------|-----------|-----|------|------|------|
| **Linear Regression** | 0.9046 | 4627.36 | 0.4361 | 49,201,433.71 | 7014.37 |
| **Decision Tree Regressor** | 0.9723 | 1305.97 | 0.0847 | 14,273,792.33 | 3778.07 |
| **Random Forest Regressor** | 0.9827 | 1193.23 | 0.0780 | 8,922,193.14 | 2987.00 |

✅ **Observation:** Random Forest achieved the **highest R² (0.9827)** with the **lowest error values**, making it the best-performing model for this problem.

---

## 🖼️ Plots & Visualizations

### 🧭 EDA Plots
![Airline vs Price](images/plots/Airline%20Vs%20Price%20Plot.png)  
![Average Flight Price by Airline](images/plots/Average%20Flight%20Price%20by%20Airline.png)  
![Average Flight Price by Class and Airline](images/plots/Average%20Flight%20Price%20by%20Class%20and%20Airline.png)  
![Correlation Heatmap](images/plots/Correlation%20Heatmap.png)  
![Days Left vs Ticket Price](images/plots/Days%20Left%20Fore%20Departure%20Versus%20Ticket%20Price%20Plot.png)  
![Source and Destination vs Price](images/plots/source%20and%20destination%20vs%20price.png)  
![Categorical Feature Distribution](images/plots/Flight%20Data%20Categorical%20Feature%20Distribution.png)

### ⚙️ Model Performance
![Linear Regression Actual vs Predicted](images/plots/Linear%20Regression%20Actual%20Vs%20Predicted.png)  
![Decision Tree Regressor Actual vs Predicted](images/plots/Decision%20Tree%20Regressor%20Actual%20Vs%20Predicted.png)  
![Random Forest Regressor Actual vs Predicted](images/plots/Random%20Forest%20Regressor%20Actual%20Vs%20Predicted.png)

---

## 📓 Notebook
Access the complete notebook here:  
[🧠 Flight Price Analysis Notebook](notebooks/flight_booking.ipynb)

---

## 🏅 Badges

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Modeling-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

---

## 👤 Owner
**Project By:** Pushpendra Singh  
📧 [LinkedIn Profile](https://www.linkedin.com/in/pushpendra-singh54-ds)  
💻 [GitHub Profile](https://github.com/Pushpendra54-DS)

---

## 💡 Conclusion
- **Random Forest Regressor** provided the best accuracy and least error metrics.  
- Ticket price depends heavily on **airline**, **class**, **number of stops**, and **days left**.  
- The project demonstrates how regression models can effectively predict real-world pricing scenarios.

---

## 🚀 Future Scope
- Use live flight APIs for real-time predictions.  
- Deploy the model using Streamlit or Flask.  
- Add interactive dashboards using Power BI.
