# Mexico Real Estate Market & Price Analysis

# 📌 Project Overview
This project processes, cleans, and analyzes real estate market data across Mexico. It covers the full data pipeline: merging multi-source raw files, handling missing geographical coordinates, trimming pricing outliers, and generating visualizations to identify key price determinants.

## 🛠️ Tools & Technologies
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn, Plotly
- **Environment:** Jupyter Notebooks / WorldQuant University Lab

## 📂 Repository Contents
- `mexico_real_estate_analysis.ipynb`: Complete Python notebook containing data wrangling, cleaning pipelines, and visual analysis.
- `mexico-real-estate-combined-clean.csv`: Cleaned dataset containing 1,736 processed property records.

## 🔄 Project Workflow & Analysis

### 1. Data Cleaning & Pipeline
- Merged multi-source CSV records into a unified DataFrame.
- Imputed missing latitude/longitude coordinates and extracted state-level parameters.
- Trimmed price and surface area outliers to ensure statistical integrity.

### 2. Exploratory Data Analysis & Visualizations
- **Price vs. Area Correlation:** Built scatter plots to evaluate price per square meter ($m^2$).
- **Regional Distribution:** Generated box plots and bar charts comparing median property costs across top Mexican states (e.g., Estado de México, Nuevo León).
- **Location Impact:** Analyzed geolocation parameters to map price heatmaps.

## 📈 Key Insights & Business Findings
- Property surface area ($m^2$) showed a strong positive correlation with price, particularly in urban commercial hubs.
- Price variance was significantly driven by state-level locations, with state capital regions commanding higher premiums per $m^2$.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/em-mally/mexico-real-estate-analysis.git](https://github.com/your-username/mexico-real-estate-analysis.git)
