# Southwest U.S. Temperature & Precipitation Analysis

A comprehensive data analysis project examining temperature and precipitation patterns in the Southwest United States using Python, pandas, and matplotlib. This project analyzes historical climate data to understand regional weather patterns, temperature trends, and precipitation changes over time.

## 📊 Project Overview

This project provides an in-depth analysis of climate data for the Southwest United States, focusing on:
- **Geographic Analysis**: City distribution and regional classification across the U.S.
- **Temperature Analysis**: Historical temperature trends and extreme weather events
- **Precipitation Analysis**: Long-term precipitation patterns and drought analysis
- **Statistical Analysis**: Hypothesis testing for climate change impacts

## 🎯 Key Findings

### Temperature Analysis (Phoenix, AZ)
- **Average Temperatures**: 86°F (max), 59°F (min)
- **Extreme Weather**: 1,056 hot days (>110°F), 739 cold days (<32°F)
- **Temperature Range**: Largest daily range occurred on June 24, 2010 (113°F max, 79°F min)
- **Climate Change Impact**: August shows the largest temperature increase (5.97°F) between 1900-1960 and 2019-2021

### Precipitation Analysis (Southwest Region)
- **Historical Average**: 12 inches in 1960
- **Trend**: Decreasing precipitation over time
- **Drought Analysis**: 13 drought years identified (2002-2005, 2012-2020)
- **Statistical Significance**: P-value of 0.02 confirms drought years have significantly lower precipitation

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas**: Data manipulation and analysis
- **matplotlib**: Data visualization
- **numpy**: Numerical computations
- **Jupyter Notebook**: Interactive development environment

## 📁 Data Sources

The project utilizes three main datasets:
1. **`city_info.csv`**: Geographic data for 210 U.S. cities with coordinates and station information
2. **`phoenix.csv`**: Daily temperature and precipitation data for Phoenix, AZ (1896-2021)
3. **`southwest.csv`**: Regional precipitation data for the Southwest U.S.

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas matplotlib numpy jupyter
```

### Running the Analysis
1. Clone this repository
2. Ensure all CSV data files are in the project directory
3. Open `Southwest_U_S_Temperature_&_Precipitation_Project.ipynb` in Jupyter Notebook
4. Run all cells to reproduce the analysis

## 📈 Analysis Components

### 1. Geographic Analysis
- Scatter plots of U.S. cities by longitude and latitude
- Regional classification (Northeast, Northwest, Southeast, Southwest)
- Nearest neighbor analysis for cross-regional comparisons

### 2. Temperature Analysis
- Historical temperature trends (1900-2020)
- Monthly temperature variations
- Extreme weather event identification
- Climate change impact assessment

### 3. Precipitation Analysis
- Long-term precipitation trends
- Drought year identification and analysis
- Statistical hypothesis testing for precipitation differences

### 4. Statistical Analysis
- Monte Carlo simulation for hypothesis testing
- P-value calculation for drought impact significance
- Comparative analysis between drought and non-drought years

## 📊 Visualizations

The project generates several key visualizations:
- Geographic distribution of U.S. cities by region
- Temperature trend lines over time
- Precipitation histograms comparing drought vs. normal years
- Monthly temperature increase analysis

## 🔬 Statistical Methods

- **Monte Carlo Simulation**: 5,000 iterations for null hypothesis testing
- **Hypothesis Testing**: Comparing precipitation between drought and non-drought years
- **Trend Analysis**: Linear regression for temperature and precipitation trends
- **Descriptive Statistics**: Mean, median, and extreme value analysis

## 📋 Results Summary

| Metric | Value |
|--------|-------|
| Cities Analyzed | 210 |
| Temperature Data Range | 1896-2021 |
| Average Phoenix Temperature | 86°F (max), 59°F (min) |
| Drought Years Identified | 13 |
| Statistical Significance (P-value) | 0.02 |
| Largest Temperature Increase | August (5.97°F) |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request for any improvements or additional analyses.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

For questions or collaboration opportunities, please open an issue in this repository.

---

*This analysis provides valuable insights into climate patterns and trends in the Southwest United States, contributing to our understanding of regional climate change impacts.*
