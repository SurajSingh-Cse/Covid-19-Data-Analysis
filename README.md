# 🦠 COVID-19 Data Analysis Project

A data analysis project to explore, visualize, and understand global COVID-19 case trends using the Johns Hopkins COVID-19 time series datasets.

---

## 🎯 Objective

Analyze the global spread and progression of COVID-19 by:
- Tracking confirmed cases over time
- Calculating daily new infections
- Visualizing high-risk countries
- Drawing insights for better pandemic response

---

## 📊 Dataset

- 📁 Source: [Johns Hopkins University COVID-19 Dataset](https://github.com/CSSEGISandData/COVID-19)
- Files Used:
  - `time_series_covid19_confirmed_global.csv`
  - `time_series_covid19_deaths_global.csv`
  - `time_series_covid19_recovered_global.csv`

---

## 🧪 Project Workflow

### 1️⃣ Data Collection
- Loaded global COVID-19 time-series data
- Used pandas for initial cleaning and aggregation

### 2️⃣ Preprocessing
- Removed unnecessary columns (`Lat`, `Long`)
- Grouped by `Country/Region`
- Transposed dataset to make dates as rows
- Converted date index to `datetime` format

### 3️⃣ Data Visualization
- 📈 **Confirmed Cases Over Time** for India, US, Brazil, Russia
- 📉 **Daily New Cases** using `.diff()`
- 🔥 **Bar Plot of Top 10 Most Affected Countries**

### 4️⃣ Insights & Conclusion
- Identified spikes in key countries
- Visualized transmission trends clearly
- Useful for planning lockdowns and health policies

---

## 📌 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📎 Folder Structure

COVID-19-Data-Analysis/
│
├── data/
│ └── time_series_covid19_confirmed_global.csv
│ └── time_series_covid19_deaths_global.csv
│ └── time_series_covid19_recovered_global.csv
│
├── covid19_analysis.ipynb
├── README.md

## 🙌 Author

**Suraj Singh**  
📧 [LinkedIn](https://www.linkedin.com/in/surajsingh-cse)  
💻 GitHub: [github.com/SurajSingh-Cse](https://github.com/SurajSingh-Cse)

---

⭐ *If you found this project helpful, don't forget to give it a ⭐ on GitHub!*
