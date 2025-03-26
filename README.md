# ✈️ Flight Delay Analysis

This project explores U.S. domestic flight delay patterns using real-world aviation data.  
The goal is to identify which airlines, days, or operational factors contribute to higher delays and provide actionable insights through data visualization.

---

## 📑 Table of Contents
- [Project Overview](#project-overview)
- [Business Problem](#business-problem)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
- [Next Steps](#next-steps)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)

---

## 📌 Project Overview

Flight delays are a significant concern for airlines, passengers, and the broader transportation ecosystem.  
This project analyzes historical flight data to uncover trends in departure delays by airline, day of week, and time.

The focus is on understanding:
- Which airlines are most delayed?
- When do delays typically occur?
- Are delays predictable?

---

## 🧩 Business Problem

Frequent and unpredictable flight delays lead to:
- Increased operational costs for airlines
- Reduced passenger satisfaction
- Missed connections and cascading delays

This project aims to support:
- Airline performance evaluation
- Strategic scheduling
- Enhanced customer transparency

---

## 🧾 Data Description

The dataset contains over 1 million U.S. domestic flights and includes features like:
- `CarrierName`: Airline name
- `DepDelay`: Departure delay in minutes
- `DayOfWeek`: Day of the week (1 = Monday, 7 = Sunday)
- Additional metadata (airport, origin, time of day, etc.)

For analysis, a sample of 100,000 rows was used for performance optimization.  
Missing and extreme outliers were removed to improve clarity.

---

## ⚙️ Methodology

1. **Data Cleaning & Preprocessing**
   - Dropped null delay values
   - Filtered out extreme outliers (> 1000 mins)
   - Sampled the dataset for consistency

2. **Exploratory Data Analysis**
   - Bar charts, histograms, and boxplots to analyze delay patterns
   - Grouped by airline and day of the week

3. **Visualization**
   - Used Seaborn and Matplotlib for clean visual output

---

## 📊 Key Findings

- Certain airlines consistently have longer average delays
- Mondays and Fridays tend to show higher delay levels
- Delay distributions are right-skewed with long tails (extreme delays)
- Wide variability even within the same airline

---

## 🔮 Next Steps

- Perform time-series analysis by month or time of day
- Predict delay likelihood using machine learning
- Expand analysis with weather and airport traffic data

---

## 🛠 Technologies Used

- Python (Pandas, NumPy)
- Seaborn & Matplotlib for visualization
- Google Colab
- Dataset: U.S. Domestic Flights (CSV format)

---


