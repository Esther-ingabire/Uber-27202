# Uber Data Analysis Project

**Student Information:**

- Name: Ingabire Esther
- ID: 27202
- Course: Big Data Analytics Assignment 1
- Date: July 2025
- Lecturer: Maniraguha Eric

## 📋 Project Overview

This project presents a comprehensive analysis of Uber ride data using Power BI and Python. The analysis explores ride patterns, fare structures, geographical distributions, and temporal trends to provide actionable business insights for ride-sharing operations.

## 🎯 Objectives

- Analyze Uber ride patterns and customer behavior
- Investigate fare structures and pricing trends
- Examine geographical distribution of rides
- Identify temporal patterns in ride demand
- Provide data-driven recommendations for business optimization

## 📊 **ACCESS POWER BI DASHBOARD**

### 🚀 [Direct Download: Esther_ingabire.pbix](./Esther_ingabire.pbix)

**How to Use:**

1. Download the `.pbix` file above
2. Install Power BI Desktop (free from Microsoft)
3. Open the file in Power BI Desktop
4. Explore the interactive visualizations and insights

> **💡 Tip:** The dashboard includes interactive maps, fare analysis, temporal patterns, and passenger insights with cross-filtering capabilities.

## 📊 Dataset Information

- **Source:** Uber ride dataset
- **Size:** 200,000 records
- **Time Period:** 2009-2015
- **Geographical Focus:** New York City area
- **Key Variables:**
  - Pickup/Dropoff coordinates
  - Fare amounts
  - Passenger counts
  - Pickup datetime
  - Trip distances

## 🗂️ Repository Structure

```
BigDataAssignment1/
├── README.md                          # Project documentation
├── Esther_ingabire.pbix              # Power BI Dashboard
├── load_uber_data.ipynb              # Data analysis notebook
├── uber.csv                          # Original dataset
├── uber_cleaned.csv                  # Cleaned dataset
├── uber_enhanced.csv                 # Enhanced dataset with features
├── Screenshots/                      # Documentation screenshots
│   ├── Data_loading.png             # Data loading process
│   ├── Cleaning_steps.png           # Data cleaning steps
│   ├── DAX_measure.png              # DAX measures used
│   ├── Dashboard_before_slicers.png # Dashboard development stage 1
│   ├── DAshboard_with_some_slicers.png # Dashboard development stage 2
│   ├── Visualizations.png           # Chart types and visualizations
│   └── Correlation.png              # Data analysis insights
└── ANALYTICAL_REPORT.md             # Comprehensive analysis report
```

## 🛠️ Technologies Used

- **Power BI:** Interactive dashboard creation and visualization
- **Python:** Data analysis and preprocessing
  - pandas: Data manipulation
  - numpy: Numerical computations
  - matplotlib: Data visualization
  - seaborn: Statistical visualization
- **Jupyter Notebook:** Analysis environment
- **GitHub:** Version control and project hosting

## 📈 Key Findings

### Data Quality

- **Data Range:** 6.5 years of ride data
- **Geographic Coverage:** Focused on NYC metropolitan area

### Passenger Patterns

- **Single Passengers:** 69.2% of all rides
- **Two Passengers:** 14.7% of rides
- **Group Rides (3-6 passengers):** 16.1% of rides

### Fare Analysis

- **Average Fare:** $11.36
- **Median Fare:** $8.50
- **Fare Range:** $2.50 - $499.00
- **Most Common Fare:** $6.00 (25th percentile)

### Temporal Insights

- **Peak Activity:** Consistent patterns across weekdays
- **Seasonal Variations:** Data spans multiple years showing growth trends
- **Time Distribution:** Hourly patterns reveal commuting behaviors

## 🔧 Data Processing Pipeline

1. **Data Loading:** Import raw Uber dataset (200,000 records)
2. **Data Exploration:** Initial analysis of structure and quality
3. **Data Cleaning:**
   - Remove unnecessary columns (Unnamed: 0, key)
   - Handle missing values using median/mode imputation
   - Filter invalid coordinates and fare amounts
   - Remove outliers using IQR method
4. **Feature Engineering:**
   - Extract temporal features (hour, day of week)
   - Calculate trip distances using Haversine formula
   - Create passenger count categories
5. **Data Validation:** Ensure data quality and consistency

## 📊 Dashboard Features

The Power BI dashboard includes:

- **Geographic Visualization:** Interactive map showing pickup/dropoff locations
- **Temporal Analysis:** Time-series charts for ride patterns
- **Fare Distribution:** Histograms and box plots for fare analysis
- **Passenger Insights:** Breakdown by passenger count
- **Key Metrics:** Summary statistics and KPIs
- **Interactive Filters:** Date, location, and fare range filters

## 📸 Documentation Screenshots

All process documentation is available in the `Screenshots/` folder:

### **Data Processing Documentation:**

- **[Data Loading Process](./Screenshots/Data_loading.png)** - Initial data import and structure
- **[Data Cleaning Steps](./Screenshots/Cleaning_steps.png)** - Data preprocessing procedures
- **[Correlation Analysis](./Screenshots/Correlation.png)** - Statistical relationships and insights

### **Power BI Development Documentation:**

- **[DAX Measures](./Screenshots/DAX_measure.png)** - Custom calculations and formulas used
- **[Dashboard Stage 1](./Screenshots/Dashboard_before_slicers.png)** - Initial dashboard layout
- **[Dashboard Stage 2](./Screenshots/DAshboard_with_some_slicers.png)** - Dashboard with interactive filters
- **[Visualization Types](./Screenshots/Visualizations.png)** - Chart types and visual elements used

## 🎯 Business Recommendations

1. **Peak Hour Optimization:** Increase driver incentives during high-demand periods
2. **Geographic Expansion:** Focus on underserved areas with growth potential
3. **Pricing Strategy:** Implement dynamic pricing based on distance and demand
4. **Customer Segmentation:** Develop targeted services for different passenger groups
5. **Operational Efficiency:** Optimize routes based on historical patterns

## 🚀 How to Use This Repository

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Esther-ingabire/BigDataAssignment1.git
   cd BigDataAssignment1
   ```

2. **🎯 Access Power BI Dashboard (RECOMMENDED START):**

   - **Download:** `Esther_ingabire.pbix` file
   - **Install:** Power BI Desktop (free) if needed
   - **Open:** The .pbix file in Power BI Desktop
   - **Explore:** Interactive visualizations and filters

3. **Review Analysis:**

   - Open `load_uber_data.ipynb` in Jupyter Notebook
   - Run cells to reproduce the analysis
   - Read `ANALYTICAL_REPORT.md` for detailed findings

4. **Examine Documentation:**
   - Check `Screenshots/` folder for process documentation
   - Review data files for understanding the pipeline
   - Read `ANALYTICAL_REPORT.md` for comprehensive findings

## 📞 Contact Information

**Student:** Ingabire Esther  
**ID:** 27202  
**Email:** [charmingesther2@gmail.com]  
**Institution:** [AUCA]

---

_This project demonstrates proficiency in big data analytics, visualization, and business intelligence using industry-standard tools and methodologies._
