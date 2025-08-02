# Accident-Hotspot-Analysis
Machine Learning project to detect and visualize accident hotspots using KMeans and DBSCAN clustering with interactive Folium maps.
# 🚦 Accident Hotspot Analysis using Machine Learning

## 📌 Overview
This project identifies **accident hotspots** using clustering algorithms like **KMeans** and **DBSCAN**.  
It helps analyze accident-prone areas based on location data and visualizes hotspots on an **interactive map** using Folium.

The project can help traffic authorities, researchers, and policymakers to **improve road safety** and **reduce accidents in high-risk zones**.

---

## 🔹 Features
✅ Data Preprocessing & Cleaning (handles missing and invalid coordinates)  
✅ Exploratory Data Analysis (EDA) with visualizations  
✅ Accident Hotspot Detection using **KMeans** and **DBSCAN**  
✅ **Interactive Folium Map** with Heatmaps and Cluster Markers  
✅ Customizable parameters (number of clusters, DBSCAN eps & min_samples)

---

## 📂 Dataset
The dataset contains the following fields:
- **Accident_ID** → Unique ID for each accident  
- **Latitude & Longitude** → Accident location coordinates  
- **Severity** → Accident severity (Low / Medium / High)  
- **Vehicles_Involved** → Number of vehicles in the accident  
- **Casualties** → Number of people injured/killed  
- **Date** → Date of the accident  

A sample dataset is included as `sample_accident_data.csv`. You can replace it with your own dataset.

---

## 🛠️ Tech Stack
- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)  
- **Machine Learning** → KMeans & DBSCAN Clustering  
- **Folium** → Interactive Map Visualization  

---

## 🚀 How to Run
1️⃣ Clone this repository  
```bash
git clone https://github.com/your-username/accident-hotspot-analysis.git
cd accident-hotspot-analysis
