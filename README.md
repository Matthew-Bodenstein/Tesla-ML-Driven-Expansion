# ML-Driven Tesla Expansion

A machine learning-powered project that analyzes U.S. EV charging data to identify high-priority cities for Tesla Supercharger expansion using classification models, SMOTE balancing, and geospatial mapping.

---

## Tesla Supercharger Expansion Predictor 

This project uses real-world EV charging station data to:
- Predict whether a station belongs to Tesla using a Random Forest model
- Identify U.S. cities with strong fast-charging infrastructure but no Tesla Superchargers
- Visualize top recommended expansion cities using an interactive map

---

## Tools Used
- Python (Pandas, Scikit-learn, Folium, Geopy)
- SMOTE for handling class imbalance
- Random Forest for classification
- Data visualization and mapping with Matplotlib & Folium

---

## Key Results
- Model Accuracy: **87.47%**
- Tesla Recall (after SMOTE): **0.65**
- Top predictors: **Level 2** and **DC Fast Charger** counts
- 30 U.S. cities identified with strong EV infrastructure but **no Tesla stations**

---

## Getting Started
1. Open `ml_driven_tesla_expansion.ipynb` in **Google Colab** or **Jupyter Notebook**.
2. Upload the dataset file: `EV_Charging_Stations_Feb82024.xlsx`.  
   *(You can download it from the U.S. Department of Energy or use the version included if available.)*

---

## Output
The final output is an interactive HTML map:  
`tesla_expansion_map.html`  
It displays the top recommended U.S. cities where Tesla should consider expanding its Supercharger network.
