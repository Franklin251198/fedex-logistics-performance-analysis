# Exploratory-Data-Analysis---FedEx-Logistics
End-to-end data analysis of logistics and delivery performance, including delay analysis, shipment mode comparison, and freight cost optimization insights.

# 📦 Logistics Delivery Performance Analysis

## 📌 Overview
This project focuses on analyzing logistics and supply chain data to evaluate delivery performance, delays, shipment efficiency, and freight cost distribution.

The goal is to identify operational inefficiencies and provide actionable business insights for improving delivery timelines and reducing logistics costs.

---

## 🎯 Objectives
- Analyze delivery delays across countries
- Understand shipment mode performance (Air, Truck, Ocean)
- Evaluate cost vs speed trade-offs
- Identify high-cost freight outliers
- Detect operational inefficiencies in the delivery lifecycle

---

## 📊 Key Analyses Performed

### 1. Delivery Delay Analysis
- Calculated delay using scheduled vs actual delivery dates
- Identified top countries with highest delays
- Segmented delayed vs on-time shipments

---

### 2. Shipment Mode Analysis
- Compared average delivery time across shipment modes
- Identified tradeoff between:
  - 🚀 Speed (Air)
  - 💰 Cost efficiency (Ocean/Truck)

---

### 3. Freight Cost Distribution
- Analyzed total freight cost contribution by shipment mode
- Identified high-cost outliers
- Visualized cost concentration using pie charts and histograms

---

### 4. Delivery Time Distribution
- Plotted histogram of delivery time
- Detected right-skewed distribution
- Identified extreme delays (outliers)

---

### 5. Advanced Business Logic
- Created delivery status classification:
  - Delivered
  - In Transit
  - Delayed
  - Critically Delayed
- Calculated delay percentage including undelivered shipments

---

## 🔍 Key Insights

- Most deliveries occur within a consistent range, but extreme delays exist
- Air shipments are fastest but contribute heavily to cost
- Ocean shipments are slow but cost-efficient
- A small number of shipments drive disproportionately high freight costs
- Delays are often caused by process inefficiencies, not just transportation

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📈 Sample Visualizations

- Delivery Time Distribution (Histogram)
- Freight Cost % Distribution
- Shipment Mode vs Delivery Time
- Country-wise Delay Analysis

---

## 🚀 Business Recommendations

- Optimize shipment mode selection based on urgency
- Reduce dependency on expensive Air shipments for non-urgent deliveries
- Investigate extreme delay cases to identify root causes
- Improve vendor and order processing efficiency

---

## 📁 Project Structure

├── EDA_Project.ipynb
├── README.md
└── dataset



---

## 💼 How to Run

1. Clone the repository

git clone https://github.com/Franklin251198/fedex-logistics-performance-analysis

2. Open Jupyter Notebook


3. Run `EDA_Project.ipynb`

---

## 📌 Future Improvements

- Add Power BI Dashboard
- Build predictive model for delivery delays
- Optimize shipment mode selection using ML

---

## 🤝 Author

Franklin Mathias  
Aspiring Data Analyst | Data Science Student  

---

## ⭐ If you like this project
Give it a star ⭐ and feel free to connect!
