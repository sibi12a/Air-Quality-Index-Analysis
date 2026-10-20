# Air Quality Index (AQI) Analysis 

## 📌 Project Overview
This project analyzes daily PM2.5 air pollution levels across three cities: Metro City, Valley Town, and Harbor Town, for the year 2025. Using Python, NumPy, Pandas, and Matplotlib, it simulates air quality data, classifies pollution levels into health-related categories, and compares pollution trends across cities.

## 🎯 Objectives
- Analyze daily PM2.5 concentrations over 365 days.
- Classify air quality into six categories: Good, Moderate, Sensitive Groups, Unhealthy, Very Unhealthy, and Hazardous.
- Calculate annual average PM2.5 levels and count days in each category.
- Use 7-day rolling averages to identify pollution trends and peak pollution periods.
- Identify the five worst pollution days across all cities.
- Visualize and compare air quality distributions using charts and boxplots.

## 🛠️ Technologies Used
- **Python** – Core programming language
- **NumPy** – Numerical calculations and pollution data simulation
- **Pandas** – Data processing, categorization, and statistical analysis
- **Matplotlib** – Data visualization and dashboard creation
- **JSON** – Exporting analysis results

## 📊 Key Features
- Seasonal PM2.5 data simulation with random pollution events.
- AQI category classification using `pandas.cut()`.
- Category-wise daily counts using `pivot_table()`.
- 7-day rolling mean analysis to smooth daily fluctuations.
- Identification of extreme pollution days using `nlargest()`.
- Four-panel visualization dashboard with line charts, stacked bar charts, boxplots, and a worst-days summary table.
- Automatic generation of `chart.png` and `results.json`.

## 📁 Project Outputs
- `chart.png` – Air quality analysis dashboard.
- `results.json` – Summary of annual averages, unhealthy days, AQI category counts, worst pollution day, and highest 7-day average.

## 🚀 How to Run
1. Install Python 3 and the required libraries:
   ```bash
   pip install numpy pandas matplotlib
   ```
2. Run the Python script or execute the notebook in Jupyter Notebook.
3. View `chart.png` and `results.json` in the output directory.

## 📚 Learning Outcomes
This project demonstrates practical skills in data simulation, data cleaning and transformation, statistical analysis, time-series smoothing, categorical data analysis, and data visualization using Python.

## ⚠️ Disclaimer
The dataset is simulated for educational and analytical purposes. The results do not represent actual air quality measurements or official AQI reports.

## 👨‍💻 Author
**SIBIRAJAN A**

<img width="1910" height="1181" alt="chart" src="https://github.com/user-attachments/assets/c0dc0660-c7a6-4c8a-acd0-857e66516e8e" />

