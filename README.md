# Exploratory-Data-Analysis---FedEx-Logistics
End-to-end data analysis of logistics and delivery performance, including delay analysis, shipment mode comparison, and freight cost optimization insights.

# 📦 Logistics Delivery Performance Analysis

---

## 🔴 Problem

The logistics dataset contains inconsistencies in delivery timelines, shipment modes, and freight costs. The business lacks visibility into:

* Delivery delays across regions
* Cost distribution across shipment modes
* Operational inefficiencies in the delivery lifecycle

---

## 🟡 Approach

* Cleaned and preprocessed raw data (handled missing values, corrected date formats)
* Created derived features such as:

  * Delivery delay
  * Delivery status
  * Cost Per kg and Total cost
  * Delay Percentage
    
* Applied grouping and aggregation techniques to analyze patterns
* Built visualizations to understand distributions and trends

---

## 🔵 Analysis

* Performed country-level delay analysis to identify high-delay regions
* Compared shipment modes (Air, Ocean, Truck) based on delivery time
* Analyzed freight cost distribution across shipment modes
* Studied delivery time distribution to detect skewness and outliers
* Identified delayed vs on-time shipments including undelivered cases

---

## 🟢 Insights

* Most deliveries fall within a consistent range, but extreme delays exist
* Air shipments are faster but contribute significantly to total cost
* Ocean shipments are slower but more cost-efficient
* A small number of shipments account for disproportionately high freight costs
* Delays are primarily driven by process inefficiencies rather than transportation speed

---

## 🟣 Recommendations

* Optimize shipment mode selection based on urgency and cost
* Reduce reliance on Air for non-critical deliveries
* Investigate extreme delay cases to identify root causes
* Improve vendor and order processing efficiency
* Monitor high-cost shipments to control logistics expenses

---

## 🧰 Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook
* **Version Control:** Git & GitHub

---

## 📊 Key Metrics

* Average Delivery Time
* Delay Rate (%)
* Cost per Shipment
* Shipment Mode Efficiency

---

## 📁 Project Structure

```
├── EDA_Project.ipynb
├── README.md
└── SCMS_Delivery_History_Dataset.csv
```

---

## 🔮 Future Improvements

* Build an interactive dashboard using Power BI or Tableau
* Integrate SQL for scalable data querying
* Perform hypothesis testing for deeper statistical insights
* Develop a predictive model to forecast delivery delays
* Automate the data pipeline using tools like Airflow

---






---

## 💼 How to Run

1. Clone the repository

git clone https://github.com/Franklin251198/fedex-logistics-performance-analysis.git

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
