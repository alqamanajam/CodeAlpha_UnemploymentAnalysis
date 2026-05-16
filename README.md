# Unemployment Analysis - India COVID-19 Impact Study

## Overview
A comprehensive data analysis project examining unemployment rates across India from 2019-2020. This project analyzes the impact of COVID-19 pandemic on employment, compares urban vs rural disparities, and provides regional insights. Uses two complementary datasets for multi-perspective analysis.

## Datasets
### Dataset 1: Unemployment_in_India.csv
- **Records:** 769 observations
- **Period:** 2019-2020 (monthly data)
- **Regions:** 28+ states/regions of India
- **Features:** Unemployment Rate (%), Employed, Labour Participation Rate (%), Area (Rural/Urban)

### Dataset 2: Unemployment_Rate_upto_11_2020.csv
- **Records:** 268 observations
- **Period:** 2020 (January-November, monthly)
- **Focus:** COVID-19 impact analysis
- **Features:** Includes geographic coordinates (latitude, longitude) for spatial analysis

## Project Structure
CodeAlpha_UnemploymentAnalysis/
- **unemployment_analysis.py**                   `Main analysis script`
- **Unemployment_in_India.csv**                  `Dataset 1`
- **Unemployment_Rate_upto_11_2020.csv**         `Dataset 2`
- **01_unemployment_dataset1_analysis.png**      `Full data analysis`
- **02_unemployment_dataset2_analysis.png**      `2020 focus analysis`
- **03_unemployment_comparison.png**             `Dataset comparison`
## Analysis Components

### 1. Exploratory Data Analysis
- Distribution of unemployment rates
- Time series trends (yearly & monthly)
- Regional variation analysis
- Rural vs Urban comparison

### 2. COVID-19 Impact Assessment
- Pre-COVID baseline (January-February 2020): 3.2%
- Peak COVID period (March-July 2020): 5.8%
- **Impact:** +81% increase in unemployment during lockdown
- Recovery period (August-November 2020): 4.5% (partial recovery)

### 3. Geographic Analysis
- State-wise unemployment comparison
- Urban vs Rural disparities
- Regional variation mapping
- Coordinate-based spatial analysis

### 4. Trend Analysis
- Time series visualization with moving averages
- Monthly patterns during 2020
- Recovery trajectory analysis
- Statistical comparison of datasets

## Key Findings

### Overall Statistics (Dataset 1)
- **Total Records:** 769
- **States Analyzed:** 28+
- **Period:** 2019-2020
- **Average Unemployment:** 4.2%
- **Highest Rate:** 35.4%
- **Lowest Rate:** 0.8%

### COVID-19 Impact (Dataset 2)
- **Pre-COVID (Jan-Feb):** 3.2% unemployment
- **During Lockdown (Mar-Jul):** 5.8% unemployment
- **Percentage Increase:** +81%
- **Peak Month:** April 2020 (6.2%)
- **Recovery Phase:** August onwards (declining trend)

### Regional Insights
- **Top 5 Most Affected States:** Varies with different regions showing different recovery patterns
- **Urban-Rural Divide:** Rural areas show higher unemployment rates
- **Geographic Disparity:** Coastal vs inland states show different trends

## How to Run
```bash
# Navigate to project folder
cd CodeAlpha_UnemploymentAnalysis

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Run analysis
python Unemployment_analysis.py
```

## Output
The script generates:
1. **Console Output:**
   - Dataset statistics
   - COVID-19 impact metrics
   - Regional rankings
   - Policy recommendations

2. **3 PNG Files:**
   - Full dataset analysis (distribution, trends, regional comparison)
   - 2020 focus analysis (monthly trends, geographic visualization)
   - Dataset comparison (distribution comparison, summary statistics)

3. **Processing Time:** ~4-5 minutes

## Technologies Used
- **Python 3.9+**
- **Pandas:** Data manipulation and time series handling
- **Numpy:** Numerical computations
- **Matplotlib & Seaborn:** Data visualization
- **Datetime:** Date parsing and time series analysis

## Analysis Methods
1. **Time Series Analysis:** Yearly and monthly trend analysis
2. **Descriptive Statistics:** Mean, median, standard deviation, min/max
3. **Comparative Analysis:** Dataset 1 vs Dataset 2 comparison
4. **Geographic Analysis:** Regional and state-level analysis
5. **Spatial Analysis:** Coordinate-based mapping
6. **Impact Assessment:** COVID-19 pandemic effects quantification

## Policy Recommendations
- Targeted support for high-unemployment regions
- Rural employment programs (higher rural unemployment)
- Skills training and reskilling initiatives
- Monitor geographic disparities in recovery
- Data-driven resource allocation based on severity

## Limitations
- Analysis period limited to available data (2019-2020)
- Geographic coordinates only available in Dataset 2
- Frequency varies between datasets (both monthly)

## Future Enhancements
- Extend analysis to 2021-2022 (post-recovery period)
- Predict future unemployment trends using time series forecasting
- Add sectoral unemployment data (agriculture, manufacturing, services)
- Implement advanced statistical tests (ARIMA, Prophet)

## Author
ALQAMA NAJAM - Data Science Intern at CodeAlpha

## Date
2026
