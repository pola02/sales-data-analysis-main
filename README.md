# 📊 Sales Analysis Project

## 🔍 Project Overview
This project analyzes sales data to uncover insights about revenue, performance across regions, and trends over time.  
It was developed in **Python (Jupyter Notebook)** using **Pandas** and **Matplotlib** for data analysis and visualization.  
The main goal is to make data speak clearly — #MAKE_DATA_TALK 🚀

---

## 📂 Dataset
- **File:** `large_sales_data.csv`  
- **Columns include:**
  - `Date` – Transaction date  
  - `Region` – Geographic region  
  - `SalesPerson` – Sales representative  
  - `Product` – Product sold  
  - `UnitsSold` – Number of units sold  
  - `UnitPrice` – Price per unit  

---

## 🧹 Data Cleaning & Preparation
- Checked **data types** for each column  
- Converted `Date` column to datetime format  
- Verified **no missing values** (all columns clean ✅)  
- Calculated a new column `TotalRevenue = UnitsSold * UnitPrice`

---

## 📈 Data Analysis & Visualizations
Key insights and visuals created using **Matplotlib**:

1. **Average Units Sold per Region** – using `groupby()` and `.mean()`  
2. **Total Revenue per Region** – using `.sum()` and visualized as a **Pie Chart**  
3. **Daily Revenue Trend** – plotted as a **Line Chart** to observe changes over time  

### 🧭 Key Visuals:
- Pie Chart → Revenue distribution per region  
- Line Chart → Total daily revenue trend  

---

## 🧠 Insights
- The highest revenue was generated in top-performing regions (identified through the pie chart).  
- Daily revenue trend shows fluctuations and peaks on specific dates — useful for forecasting and sales planning.  
- Clean data ensured accurate aggregation and visualization.

---

## ⚙️ Tools & Libraries Used
- **Python 3**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**

---

## 🗂️ Project Structure
```
Sales Analysis Project/
│
├── sales_analysis_project.ipynb      # Main notebook (code & analysis)
├── sales_analysis_project.html       # Exported HTML version for viewing
├── data/
│   └── large_sales_data.csv          # Original dataset
└── README.md                         # Project documentation
```

---

## 🌐 How to View
- Open the `.ipynb` notebook in **Jupyter** for interactive exploration.  
- Or view the HTML version directly in your browser.  
- You can also preview it online using **nbviewer**:  
  👉 [https://nbviewer.org](https://nbviewer.org)

---

## 💬 Author
**Mohamed Heta**  
Data Analyst | Power BI | Python | SQL  
Hashtags: #MAKE_DATA_TALK #معلومة_في_السكة
