# 🚗 Electric Vehicle Market & Performance Analysis

## 📌 Project Overview
This project analyzes the **global Electric Vehicle (EV) market** using real-world automotive data to understand how **price, performance, and efficiency** are related. The analysis focuses on identifying key technical and brand-level factors that influence EV pricing and market positioning.

The dataset was collected through **web scraping** from a trusted EV industry source and analyzed using **Exploratory Data Analysis (EDA)** techniques to uncover trends, correlations, and trade-offs across EV models.

---

## 🎯 Objectives
- Analyze relationships between **EV price, battery capacity, range, efficiency, and acceleration**
- Identify **key factors influencing EV market value**
- Compare **brand-level performance and positioning**
- Segment EVs into **budget, mid-range, and premium categories**
- Generate **actionable insights** for consumers and manufacturers

---

## 📊 Dataset Details
- **Source:** EV Database (web scraped)
- **Total Models:** 973 Electric Vehicles
- **Features:** 15
- **Target Variable:** Price (€)

### Key Features
- **Performance:** Battery Capacity, Real-World Range, Acceleration, Fast Charging Speed  
- **Efficiency:** Energy Consumption  
- **Design:** Vehicle Weight, Cargo Volume, Towing Capacity  
- **Market & Brand:** Brand Name, Vehicle Status, Availability Years  

---

## 🛠️ Tools & Technologies
- **Python**
- **BeautifulSoup & Requests** – Web Scraping
- **Pandas & NumPy** – Data Processing
- **Matplotlib & Seaborn** – Data Visualization
- **Jupyter Notebook**

---

## 🧹 Data Cleaning Process
- Handled missing values intelligently  
- Filled missing **Availability End Year** for active vehicles with 2025  
- Used **median imputation** for Towing Capacity and Cargo Volume  
- Standardized units and corrected inconsistent entries  

Final dataset is **clean, complete, and analysis-ready**.

---

## 📈 Key Analysis Performed

### Univariate Analysis
- Brand market share distribution  
- Battery capacity, range, and efficiency distributions  

### Bivariate Analysis
- Battery capacity vs range correlation  
- Acceleration vs range trade-off  
- Price vs performance relationships  

### Multivariate Analysis
- EV market segmentation (Budget / Mid-range / Premium)  
- Cross-feature correlation patterns  

---

## 🔍 Key Insights
- **Battery capacity drives ~90% of real-world range**
- Faster acceleration often reduces range and efficiency
- EV pricing depends more on **brand and features** than raw specifications
- European manufacturers dominate multiple market segments
- Clear clustering exists across price and performance tiers

---

## 📂 Project Structure
