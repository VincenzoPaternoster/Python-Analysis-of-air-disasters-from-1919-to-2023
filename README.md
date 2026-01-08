# 📌 Analysis of air disasters from 1919 to 2023
 The International Alliance for Safe Skies (IASS) has tasked you with conducting a thorough analysis of all aircraft accidents that occurred between 1919 and 2023.

---
##### *NOTE: These analyses are for educational purposes only*
---

## 📂 Repository Structure
```
Analysis-of-air-disasters/
│── data/
      ├── aviation_accident.csv
│── images/
      ├── Cartograms
      ├── Barcharts
│── python/
      │── Analysis_of_air_disasters_from_1919_to_2023.ipynb
      |── Analysis_of_air_disasters_from_1919_to_2023.py
│── README.md
```

## 🎯 Project objectives

##### 1. The main objective of the project is to conduct an in-depth analysis of all aircraft accidents that occurred between 1919 and 2023
---

## 🗂️ Dataset
**Source:** Profession AI - Master in Data Analytics
**Period examined:** from 1919 to 2023  
**Dimension of dataset:** 23967 accidents

### 📌 Key variables
| Variables | Description |
|----------|-------------|
| date | date of accident |
| type  | type of aircraft |
| registration| registration code of aircraft |
| operator | Aircraft operator|
| fatalities | Number of victims|
| location | Place where accident occurred|
| country | Country of accident|
| cat | Category of accident described by ASN|
| day | Day of the week of the accident|
| year | Year of accident|

---

## 🧹 Data Cleaning
Key operations performed:
- Handling missing values
- Handling "unknown" and special character

---

---

## 🔍 Key results
- **Insight 1**: The United States is the country with the highest number of deaths caused by plane crashes. [View graph](https://github.com/VincenzoPaternoster/Python-Analysis-of-air-disasters-from-1919-to-2023/blob/main/image/Barcharts/Most_accidents.png)
- **Insight 2**: Friday is the day of the week with the most accidents. [View graph](https://github.com/VincenzoPaternoster/Python-Analysis-of-air-disasters-from-1919-to-2023/blob/main/image/Barcharts/Accidents_and_days.png)
 
- **Insight 3**: USAF, USAAF, and RAF operators are the least safe operators [View graph](https://github.com/VincenzoPaternoster/Python-Analysis-of-air-disasters-from-1919-to-2023/blob/main/image/Barcharts/Unsafe_and_safe.png)
- 
- **Insight 4**: The Douglas C-47A (DC-3) is the aircraft model that has caused the most victims.  [View graph](https://github.com/VincenzoPaternoster/Python-Analysis-of-air-disasters-from-1919-to-2023/blob/main/image/Barcharts/Type_of_planes_and_death.png)

- **Insight 5**: The number of plane crashes after September 11, 2001, did not decrease in the following years  [View graph](https://github.com/VincenzoPaternoster/Python-Analysis-of-air-disasters-from-1919-to-2023/blob/main/image/Barcharts/2001.png)

- **Insight 6**: These cartograms show how the number of accidents is distributed around the world [View cartograms](https://github.com/VincenzoPaternoster/Python-Analysis-of-air-disasters-from-1919-to-2023/tree/main/image/Cartograms)

- **Insight 7**: The most frequent category accidents is A1 (Accidents withouth victim followed by A2 category (Accident with at leat one victim) [View graph](https://github.com/VincenzoPaternoster/Python-Analysis-of-air-disasters-from-1919-to-2023/blob/main/image/Barcharts/category_accidents.png)
 
 

---

## 🧠 Conclusions
##### In this project, I learned how to use matplotlib and its various parameters to display different types of information. I also practiced with a unique type of graph: cartograms. 

---

## 🛠️ Tools
- Python (pandas,matplotlib)
- Google Colab
- Obsidian

---

## 📬 Contacts

- **Vincenzo Paternoster**
- Email: vincenzopaternoster99@gmail.com
- LinkedIn: www.linkedin.com/in/vincenzo-paternoster
