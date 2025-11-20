# Swiggy Data Analysis 🍔📊

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![pandas](https://img.shields.io/badge/pandas-Data%20Cleaning-150458)
![Excel](https://img.shields.io/badge/Excel-Reporting-green)
![seaborn](https://img.shields.io/badge/seaborn-Visualization-orange)

## 📌 Project Overview
This project analyzes over 100,000 food delivery orders from Swiggy across 10+ Indian cities to uncover consumer behavior patterns. By cleaning and standardizing large datasets, the analysis identifies key trends such as peak demand windows and popular cuisines.

The insights are delivered via **Excel reports** with business-friendly charts, supporting targeted marketing strategies and campaign optimization.

## 🚀 Key Features
- **Data Cleaning**: Robust pipeline to handle duplicates, data errors, and timestamp parsing for 100,000+ records.
- **Pattern Recognition**: Identified the **7-9 PM** peak demand window, critical for resource allocation.
- **Market Analysis**: Aggregated orders by cuisine, city, and time slots to find top-performing categories.
- **Actionable Reporting**: Automated Excel exports with embedded charts for stakeholders.

## 🛠️ Tech Stack
- **Language**: Python
- **Data Processing**: pandas, NumPy
- **Visualization**: matplotlib, seaborn
- **Reporting**: Excel (xlsxwriter)

## 📂 Project Structure
```
├── swiggy_analysis_script.py  # Main analysis and reporting script
├── Swiggy_dataset.csv         # Raw dataset
├── Swiggy_Analysis_Report.xlsx # Generated Excel report with charts
├── images/                    # Generated plots
└── README.md                  # Project documentation
```

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Swiggy-Data-Analysis.git
   cd Swiggy-Data-Analysis
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn xlsxwriter
   ```

## 🏃‍♂️ Usage
### Run Analysis
Execute the script to clean data, perform analysis, and generate the Excel report:
```bash
python swiggy_analysis_script.py
```

### View Report
Open `Swiggy_Analysis_Report.xlsx` to see the data tables and embedded charts showing hourly demand trends.

## 📊 Key Findings
- **Peak Time**: 7-9 PM is the highest demand period.
- **Optimization**: Recommendations focus on campaign targeting during these peak hours.