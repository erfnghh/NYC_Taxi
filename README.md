# NYC_Taxi


![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

A comprehensive data analysis and visualization project exploring New York City taxi trip data to uncover patterns, trends, and business insights through interactive Power BI dashboards.



## 🚀 Quick Start

### Prerequisites
- Power BI Desktop
- Python 3.8+
- Jupyter Notebook (optional)

### Installation
```bash
# Clone the repository
git clone https://github.com/erfnghh/NYC_Taxi.git
cd nyc-taxi-analysis

# Install Python dependencies
pip install -r requirements.txt
```

### Usage
1. Open `nyc_taxi.pbix` in Power BI Desktop
2. Connect to your data source if needed
3. Use filters and slicers for interactive analysis

## 📁 Project Structure

```
nyc-taxi-analysis/
│
├── dashboard/
│   └── nyc_taxi.pbix          # Main Power BI dashboard
│
├── notebooks/
│   └──data_cleaning_analysis.ipynb           # Data preprocessing & outlier handling
│    
│
├── images/                              # Visualization exports
├── data/                                # Sample data
├── requirements.txt                     # Python dependencies
└── README.md
```


## 📊 Dashboard Overview

<div align="center">


<img src="images/image.png" width="700" alt="Main Dashboard" style="border-radius: 8px; border: 1px solid #e1e4e8; box-shadow: 0 4px 12px rgba(0,0,0,0.1); margin: 10px;">

  
<img src="images/pg2nd.png" width="700" alt="Geographic Analysis" style="border-radius: 8px; border: 1px solid #e1e4e8; box-shadow: 0 4px 12px rgba(0,0,0,0.1); margin: 10px;">


<img src="images/pg3rd.png" width="700" alt="Temporal Patterns" style="border-radius: 8px; border: 1px solid #e1e4e8; box-shadow: 0 4px 12px rgba(0,0,0,0.1); margin: 10px;">

</div>

## 🔍 Key Insights

### 📈 Performance Metrics
- **Avg Fare**: $12.42 per trip
- **Avg total-amount**: $15.68 per trip
- **Airport Routes**: higher revenue than city trips

### 🗺️ Geographic Analysis
- **Hotspots**: Manhattan, JFK/LGA airports

## 🛠️ Technical Features

### Data Processing
```python
# Advanced data cleaning pipeline
def clean_taxi_data(df):
    df = remove_geographic_outliers(df)
    df = filter_trip_durations(df, 0.1, 100)
    df = handle_missing_values(df)
    return df
```

### Power BI Capabilities
- **Interactive DAX measures and columns**
- **Custom geographic visualizations**
- **Time intelligence functions**

## 📊 Dataset

**Source**: [NYC TLC Trip 2016-3 Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

**Columns Analyzed**:
- Pickup/Dropoff datetime & locations
- Trip distance & duration
- Fare amount,tip amount & total amount
- Passenger count & trip count

## 🎯 Business Applications

- **Revenue Optimization**:

<div align="center">
<img src="images/revenue.png" width="650" 
     alt=" revenue Strategy Analysis"
     style="border-radius: 8px; 
            border: 1px solid #e1e4e8;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            transition: all 0.3s ease;"
     onmouseover="this.style.boxShadow='0 8px 24px rgba(0,0,0,0.15)'; this.style.transform='scale(1.02)'"
     onmouseout="this.style.boxShadow='0 4px 12px rgba(0,0,0,0.1)'; this.style.transform='scale(1)'">
</div>

- **Pricing Strategy**: 

<div align="center">
<img src="images/pricing strategy.png" width="650" 
     alt="Pricing Strategy Analysis"
     style="border-radius: 8px; 
            border: 1px solid #e1e4e8;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            transition: all 0.3s ease;"
     onmouseover="this.style.boxShadow='0 8px 24px rgba(0,0,0,0.15)'; this.style.transform='scale(1.02)'"
     onmouseout="this.style.boxShadow='0 4px 12px rgba(0,0,0,0.1)'; this.style.transform='scale(1)'">
</div>



---

⭐ **If you find this project useful, please give it a star on GitHub!**

---
