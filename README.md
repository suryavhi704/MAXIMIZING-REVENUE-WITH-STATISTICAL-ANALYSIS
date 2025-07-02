# 🚖 Maximizing Revenue for Taxi Drivers through Payment Type Analysis

This project leverages **NYC Yellow Taxi trip data** to uncover how **payment types** (card vs cash) impact **fare amounts** and overall revenue generation. The goal is to derive actionable insights to help taxi drivers and services optimize their strategies through data analysis.

---

## 📌 Problem Statement

In the dynamic taxi industry, **increasing driver revenue** is key. This project explores whether **payment methods** influence **fare amounts** and how encouraging certain types of payments (like card transactions) may benefit both drivers and service platforms.

---

## 🎯 Objectives

- Identify if fare amounts vary by **payment type**
- Assess whether **card payments** bring higher average revenue
- Understand customer **payment behavior**
- Recommend **data-driven strategies** to maximize driver earnings

---

## 🧠 Research Questions

- Is there a statistically significant relationship between **fare amount** and **payment type**?
- Can customers be nudged toward card payments without affecting the user experience?

---

## 📊 Dataset Overview

- Source: NYC Yellow Taxi Trip Records  
- Features used:
  - `passenger_count`
  - `payment_type` (Card/Cash)
  - `fare_amount`
  - `trip_distance`
  - `trip_duration`

---

## 🔎 Methodology

1. **Data Cleaning & Feature Engineering**
2. **Descriptive Analysis** of payment behaviors
3. **T-test Hypothesis Testing** (Card vs Cash fare amounts)
4. **correlation analysis** on trip duration vs fare
5. **Visualization** of trends and distribution

---

## 📈 Key Findings

- **Card payments** are linked to **higher average fares and longer trips**
- **67.5%** of transactions were **card-based**
- Statistically significant difference found (p < 0.05)
- Solo riders dominate transactions for both payment types

---

## ✅ Recommendations

- Offer **incentives for card users**
- Promote **secure, seamless card payment systems**
- Target longer-route trips for **card-payment preference nudging**

---

## 📎 Project Structure

├── data/ # Dataset and preprocessing files


├── notebooks/ # Jupyter notebooks for EDA & modeling
\

├── results/ # Graphs, plots, summary reports


├── hypothesis_test.py # T-test implementation


└── correlation_model # correlation analysis

