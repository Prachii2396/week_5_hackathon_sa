# 🚗 Dynamic Pricing for Urban Parking Lots

**Capstone Project – Summer Analytics 2025**  
*Organized by Consulting & Analytics Club, IIT Guwahati*

---

## 📊 Overview

Urban parking is a scarce resource. This project simulates a real-time **dynamic pricing engine** that updates parking rates based on occupancy, queue length, traffic, vehicle type, and competitor pricing.

The goal is to balance demand and maximize parking space efficiency.

---

## 📦 What's Inside

✅ A clean dataset of 14 parking lots  
✅ 3 pricing models of increasing complexity  
✅ Real-time visualizations using **Bokeh**  
✅ Built only using `pandas`, `numpy`, `bokeh`, `pathway`

---

## 🧠 Models Implemented

### 🔹 Model 1 – Linear Baseline
Price increases proportionally with occupancy.

### 🔹 Model 2 – Demand-Based
Price is derived from a weighted demand function:
- occupancy rate
- queue length
- traffic congestion
- vehicle type
- special day

### 🔹 Model 3 – Competitive Pricing
Extends Model 2 with **location intelligence**:
- Computes distances using Haversine formula
- Adjusts price based on nearby competitors' rates

---

## 🛠️ How to Use

1. Clone this repo  
2. Open the notebook on Google Colab  
3. Upload the dataset `dataset.csv`  
4. Run all cells  
5. Use:
```python
plot_all_models("BHMBCCMKT01")
