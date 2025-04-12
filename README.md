## 🌦️ **Weather Forecast Prediction Using Random Forest & Power BI**  
**An end-to-end ML project to predict weather conditions and visualize insights using Python, Power BI & automation.**  

---

## **📖 Table of Contents**  

1️⃣ [Executive Summary](#1️⃣-executive-summary)  
2️⃣ [Project Scope & Objectives](#2️⃣-project-scope--objectives)  
3️⃣ [Methodology & Approach](#3️⃣-methodology--approach)  
4️⃣ [Key Findings & Analysis](#4️⃣-key-findings--analysis)  
5️⃣ [Features & Functionalities](#5️⃣-features--functionalities)  
6️⃣ [Technologies & Tools Used](#6️⃣-technologies--tools-used)  
7️⃣ [Deliverables & Files](#7️⃣-deliverables--files)  
8️⃣ [Future Enhancements & Improvements](#8️⃣-future-enhancements--improvements)  
9️⃣ [How to Run This Project](#9️⃣-how-to-run-this-project)  
🔟 [Conclusion](#🔟-conclusion) 

![image](https://github.com/user-attachments/assets/5f778887-a6da-4159-aafc-8d4dca63b1ab)


---

## **1️⃣ Executive Summary**  

### 📌 **Overview of the Project**  
This project uses a **Random Forest classifier** to predict **weather conditions** (Rainy, Sunny, etc.) using **historical weather data**. It includes an automated prediction pipeline and a **Power BI dashboard** for interactive weather trend analysis.
This project provides a weather forecasting solution using machine learning models trained on historical weather data.

The final insights are visualized using an interactive Power BI dashboard.

The dashboard gives a clear view of weather trends across different Indian states and helps users observe patterns in temperature, weather conditions, and precipitation over time.

### 📌 **Impact & Benefits**  
- Helps users and organizations **plan activities** based on predicted weather.  
- Offers **real-time, data-driven forecasts** through automation.  
- Enables easy visualization and exploration using **Power BI filters and visuals**.


----

## **2️⃣ Project Scope & Objectives**  

### 📌 Problem Statement  
Can we accurately **predict tomorrow’s weather condition** using features like temperature, humidity, wind speed, etc.?

### 📌 Objectives  
✔ Forecast categorical weather (Rainy/Sunny/etc.)  
✔ Automate predictions using historical and new data  
✔ Visualize trends using Power BI  
✔ Maintain high accuracy and interpretability  

---

## **3️⃣ Methodology & Approach**  

✔ **Data Source:**  
Used `seattle-weather.csv` from Kaggle as the historical dataset  

✔ **Preprocessing & Feature Engineering:**  
- Cleaned null values  
- Encoded categorical features  
- Extracted month, year, and season  
- Created the target column `weather_condition`
  ![image](https://github.com/user-attachments/assets/77351da2-d177-400f-acb5-318cfea99a05)


✔ **Model Building – Random Forest Classifier** 🌳  
- Trained on features: `temp_max`, `temp_min`, `wind`, `precipitation`, `month`, etc.  
- Achieved **94% accuracy** on test data  
- Exported predictions to `weather_with_predict.csv` and `weather_with_predictions.xls`  

✔ **Power BI Dashboard**  
- Created in `Weather_Prediction_project.pbix`  
- Displays filters by date, condition, and precipitation  
- Graphs for weather condition frequency, trends over time, and city-wise analysis  

---

## **4️⃣ Key Findings & Analysis**  

✔ Rainy and Cloudy conditions appear most frequently  
✔ High humidity and wind correlate with Rainy predictions  
✔ Random Forest outperformed Logistic Regression in accuracy  
✔ Achieved **94% accuracy** on unseen test data  
✔ Dashboard allows filtering by weather condition, date, and more  

---

## **5️⃣ Features & Functionalities**  

✅ Weather condition prediction using Random Forest  
✅ Multiple output formats: CSV, XLS  
✅ Interactive Power BI dashboard for insights  
✅ Prediction automation ready via script integration  

---

## **6️⃣ Technologies & Tools Used**  

- **Python** (Pandas, Scikit-learn, Seaborn, Matplotlib)  
- **Random Forest Classifier**  
- **Power BI** for visual analytics  
- **CSV/XLS Export** for reporting and sharing  

---

## **7️⃣ Deliverables & Files**  

📂 `MI_model_for_Predictions.ipynb` → Main notebook for ML modeling  
📂 `seattle-weather.csv` → Raw dataset from Kaggle  
📂 `weather_with_predict.csv` → CSV file with predictions  
📂 `weather_with_predictions.xls` → Excel file with predicted results  
📂 `Weather_Prediction_project.pbix` → Power BI dashboard file  
📂 `README.md` → Project documentation  

---
 ## **8️⃣ Key Insights from Dashboard**  

📌 Based on the observations:

Telangana recorded the highest sum of temperature (35 units) with frequent rainy conditions.

Kerala and Gujarat mostly experienced cloudy or sunny weather.

Precipitation patterns showed spikes in early and late 2015.

The temperature range between 24°C to 36°C dominates most states.

Dashboard allows filtering by state, weather condition, and quarter-wise trends.

## **8️⃣ Future Enhancements & Improvements**  

🔄 Add real-time data using a weather API  
📈 Compare with other models like XGBoost or SVM  
🌐 Deploy on Streamlit or Flask for real-time user access  
🧠 Add SHAP/LIME for model interpretability  

---

## **9️⃣ How to Use the Project**
Clone the repo

Train or load the saved model (weather_model.pkl)

Update the data in seattle-weather.csv

Generate predictions and save to weather_with_predictions.csv

Refresh Power BI dashboard with new data

---

## **🔟 Conclusion**  

This project demonstrates the effective use of **Random Forests and Power BI** to forecast weather, analyze trends, and deliver clear insights. With a 94% accuracy, it shows strong potential for real-world applications in daily planning, logistics, and agriculture.

---

