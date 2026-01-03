# 🌊 Watershed & Flow Direction Analysis of Nagaon District, Assam

## 🔹 Project Overview / Problem Statement
Watershed and flow direction analysis plays a crucial role in hydrological planning, flood assessment, and water resource management.  
This project focuses on **watershed delineation and stream network extraction of Nagaon District, Assam**, using DEM-based hydrological techniques to understand surface water flow patterns.

---

## 🎯 Objectives
- To extract and analyze watershed boundaries of Nagaon District  
- To generate flow direction and flow accumulation maps  
- To delineate stream networks and assign stream order using the **Strahler method**

---

## 📍 Study Area
The study area covers **Nagaon District, Assam**, characterized by a mix of plains and gentle slopes with dense drainage networks influenced by monsoonal rainfall.

📌 *Refer to the study area and watershed maps in the final output.*

---

## 🗂 Data Sources
- **SRTM DEM (30 m resolution)**  
  USGS Earth Explorer  
  https://earthexplorer.usgs.gov/

- **Administrative Boundary (Nagaon District)**  
  Open Government / Survey of India sources

---

## 🛠 Tools & Methods

### Software Used
- ArcGIS 10.8
- Spatial Analyst or Arc Hydro Tools

### Methodology
1. DEM extraction using mask  
2. Sink filling to remove surface depressions  
3. Flow direction computation (D8 algorithm)  
4. Flow accumulation analysis  
5. Stream raster generation using threshold values  
6. Stream ordering using **Strahler method**  
7. Vectorization (polygonisation) of stream networks  

---

## 🗺 Key Outputs
- Extracted DEM of Nagaon District  
- Filled DEM  
- Flow Direction Map  
- Flow Accumulation Map  
- Stream Order Map (Strahler)  
- Polygonised Stream Network Map  

---

## 📌 Final Map Output
The final composite map for this project is:

**`Nagaon Watershade & Flow Direction Analysis.jpg`**

This map integrates:
- DEM preprocessing  
- Flow direction and accumulation  
- Stream ordering  
- Watershed boundary  

📷 *(See the image file in this repository)*

---

## 📊 Results & Interpretation
- Flow accumulation highlights **major drainage corridors** across the district.
- Stream ordering indicates a **well-developed drainage system**, with streams up to **5th order**.
- Higher-order streams represent major rivers responsible for **water conveyance and flood flow**.
- The watershed boundary clearly defines **hydrologically connected areas** useful for planning and management.

---

## 📘 What I Learned
- Watershed delineation at a **district scale**
- Stream ordering concepts and interpretation
- Raster-to-vector conversion techniques
- Importance of **threshold selection** in stream extraction

---

## 🔮 Future Improvements
- Flood hazard and flood susceptibility mapping  
- Integration of rainfall, soil, and land-use datasets  
- Watershed prioritization for water resource planning  
- Validation using observed stream networks  

---
