# 📌 PRODIGY_DS_05 – Traffic Accident Data Analysis  

## 🌟 Project Overview  
This project analyzes **US traffic accident data** to identify **patterns related to road conditions, weather, and time of day**.  
The goal is to uncover **accident hotspots** and understand **contributing factors** that impact road safety.  

---

## 🚀 Workflow  

### 1️⃣ Data Preprocessing  
- Loaded accident dataset (`US_Accidents_Dec20.csv`)  
- Selected important columns: `Severity`, `Weather_Condition`, `Start_Time`, `State`, `Temperature(F)`, etc.  
- Handled missing values & converted date-time features  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Accident count by **state** (top 10 states)  
- Accident distribution by **time of day (morning, afternoon, evening, night)**  
- Relationship between **weather conditions & accidents**  

### 3️⃣ Visualization  
- **Bar plots & count plots** for accident severity and time patterns  
- **Heatmap** for correlations between numerical features  
- **Accident Hotspots Map** (using Folium/Matplotlib for states with highest cases)  

---

## 📊 Visualizations  
📌 **Accidents by State** – Bar chart showing top states with highest accident counts  
📌 **Accidents by Hour of Day** – Pattern of accidents during different hours  
📌 **Weather Conditions** – Distribution of accidents under different weather types  
📌 **Heatmap (Correlation)** – Relation between features like temperature, humidity, visibility  

---

## ⚙️ Tech Stack  
- Python 🐍  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

## 📈 Results & Insights  
- **California, Florida, and Texas** reported the most accidents  
- Accidents peak during **rush hours (7-9 AM, 4-7 PM)**  
- **Rain & foggy conditions** significantly increase accident likelihood  
- Severity levels are higher during **nighttime & adverse weather**  
