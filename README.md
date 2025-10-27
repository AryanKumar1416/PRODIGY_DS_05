# 🚗 Road Accident Data Analysis

## 📋 Overview
This project presents an **exploratory data analysis (EDA)** of road accident data to identify key trends, contributing factors, and safety insights.  
The goal is to understand when and where accidents most frequently occur and provide data-driven recommendations for prevention and policy planning.

---

## 🔍 Key Findings

### 🧹 Data Quality
- No missing values were found in the dataset after initial preprocessing.

### 🕒 Time of Day
- Accidents are most frequent during the **afternoon (12 PM – 5 PM)** and **evening (5 PM – 9 PM)**.  
- The fewest accidents occur **at night**.

### 📅 Day of Week
- **Friday** has the highest number of accidents (**2041**).  
- **Sunday** records the lowest (**1467**).

### 🛣️ Road Conditions
- Most accidents occur on **Dry road surfaces (9340)**.  
- **Asphalt roads (11468)** account for the highest accident count.

### 🛤️ Road Alignment & Type
- **Tangent roads with flat terrain (10601)** show the highest number of accidents.  
- **Two-way divided roads with broken lines (4796)** and **Undivided two-way roads (3796)** are particularly accident-prone.

### 🚦 Junction Type
- **Y-Shape junctions (5430)** and **No junction areas (3837)** report the highest accident frequencies.

### 🌤️ Weather & Light Conditions
- The majority of accidents occur under **Normal weather conditions (10063)**.  
- **Daylight (8798)** has the highest frequency, followed by **Darkness – lights lit (3286)**.

### 🏙️ Area Type
- Accidents are most common in **“Other”**, **“Office areas”**, and **“Residential areas”**.

### 💥 Accident Severity
- **Slight injuries** are the most common across nearly all causes.  
- Common causes for **slight and serious injuries** include:
  - *Changing lane to the right*
  - *No distancing*
  - *Changing lane to the left*  
- **Fatal injuries** are most associated with:
  - *Moving backward*
  - *Changing lane to the right*
  - *No distancing*
  - *Changing lane to the left*

---

## 📈 Insights & Recommendations

1. **🎯 Focus on High-Risk Periods**
   - Conduct road safety campaigns during **afternoon and evening hours**, especially on **Fridays**, to target peak accident times.

2. **🚧 Improve Junction Safety**
   - Analyze **Y-Shape junctions** and **areas without junctions** to identify visibility or structural issues and implement corrective measures.

3. **🛣️ Monitor Road Conditions**
   - Since most accidents occur on **dry asphalt roads**, prioritize **speed control**, **lane discipline**, and **signage improvements** over weather-related measures.

4. **📢 Enhance Public Awareness**
   - Run campaigns emphasizing **safe lane changing** and **maintaining distance** between vehicles to reduce both minor and serious accidents.

---

## 🧰 Tools & Techniques Used

| Category | Tools/Techniques |
|-----------|------------------|
| **Language** | Python |
| **Libraries** | pandas, matplotlib, seaborn |
| **Techniques** | Data Cleaning, Descriptive Statistics, Visualization, Trend Analysis |

---

## 🔮 Future Work
- Incorporate **geospatial mapping** to visualize accident hotspots.  
- Apply **machine learning models** (e.g., Logistic Regression, Random Forest) to predict accident severity.  
- Integrate **traffic volume, vehicle type**, and **driver behavior** data for deeper insights.

---

## 🧾 Author
**Data Analyst:** *[Aryan Kumar]*  
**Project Title:** *Road Accident Data Analysis*  
**Date:** *October 2025*

---

> 📊 *This analysis aims to support evidence-based road safety strategies and reduce accident frequency through data-driven insights.*
