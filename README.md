# 🚗 Dynamic Pricing for Urban Parking Lots

**Capstone Project | Summer Analytics 2025**  
Hosted by: Consulting & Analytics Club × Pathway  
Submitted by: Rajat Singh
rajatsingh2710.24@kgpian.iitkgp.ac.in

---

## 📌 Problem Statement

Urban parking spaces are limited and unevenly used.  
This project builds a real-time, intelligent pricing system for 14 parking lots based on demand patterns, vehicle types, queue lengths, traffic conditions, and special days — using only `NumPy`, `Pandas`, `Pathway`, and `Bokeh`.

---

## 🧠 Models Implemented

### ✅ Model 1: Baseline Linear Model
Simple pricing logic:
\[
P_{t+1} = P_t + \alpha \cdot \left( \frac{\text{Occupancy}}{\text{Capacity}} \right)
\]

### ✅ Model 2: Demand-Based Pricing
Dynamic pricing using:
- Occupancy Rate
- Queue Length
- Traffic Congestion
- Special Day Indicator
- Vehicle Type (weighted)

\[
\text{Price} = \text{BasePrice} \cdot (1 + \lambda \cdot \text{NormalizedDemand})
\]

---

## ⚙️ Real-Time Features

- **Pathway** used to simulate live data stream from CSV
- **Pricing logic** is applied row-by-row with 1-second delay
- **Bokeh** used for interactive price visualization

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `main_notebook.ipynb` | Full model code, EDA, Pathway pipeline |
| `report.pdf` | Formatted PDF version of notebook |
| `stream.csv` | Cleaned dataset for streaming |
| `README.md` | You're reading it! |



## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Pathway (real-time simulation)
- Bokeh (interactive plots)
- Google Colab

---

## 🎓 Notes

- All models are implemented from scratch
- No external ML libraries were used
- Entire pipeline is real-time and visualized

---

### 🔗 Final Submission Link:
GitHub Repo: [https://github.com/RajatSingh02160/dynamic_pricing_project_sa2025]
