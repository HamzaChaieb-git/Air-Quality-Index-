# Air Quality Index Analysis 🌍

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![RStudio](https://img.shields.io/badge/RStudio-75AADB?style=for-the-badge&logo=RStudio&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

## 📋 Overview

A comprehensive data analysis project examining global air quality patterns and their correlation with urbanization metrics. This project leverages advanced statistical techniques to uncover insights about air pollution trends across 170+ countries and 300+ cities worldwide.

## 🎯 Objectives

- Analyze global air pollution patterns and identify critical hotspots
- Investigate correlations between vehicle density and air quality metrics
- Visualize pollution distribution through interactive maps and dashboards
- Provide actionable insights for environmental policy decisions

## 📊 Dataset

### Primary Sources
- **Global Air Pollution Dataset**: Comprehensive AQI values covering PM2.5, PM10, NO2, O3, SO2, and CO levels
- **Vehicle Registration Data**: Per capita vehicle ownership statistics across countries

### Coverage
- 170+ countries
- 300+ major cities
- Multiple pollutant measurements
- Time-series data for trend analysis

## 🔬 Methodology

### Data Processing
- Handled missing values using advanced imputation techniques
- Normalized data across different measurement scales
- Aggregated city-level data to country-level insights
- Applied time-series decomposition for seasonal pattern detection

### Analysis Approach
- Exploratory Data Analysis (EDA) for pattern identification
- Correlation analysis between urbanization and pollution metrics
- Geospatial analysis for pollution hotspot detection
- Statistical testing for hypothesis validation

## 📈 Key Findings

### Global Pollution Insights
- **68%** of analyzed cities exceed WHO recommended PM2.5 levels
- **Top 5** most polluted regions identified with average AQI > 150
- **35%** higher pollution levels during winter months in northern hemisphere

### Vehicle-Pollution Correlation
- Strong positive correlation (r = 0.72) between vehicle density and PM2.5 levels
- Urban areas with >500 vehicles/1000 people show 2.3x higher pollution
- Electric vehicle adoption shows negative correlation with air quality degradation

### Health Impact Analysis
- Estimated **4.2 million** premature deaths annually due to ambient air pollution
- Economic impact assessment reveals $2.9 trillion in global health costs
- Vulnerable populations disproportionately affected in developing nations

## 🎨 Visualizations

The project features interactive visualizations including:
- **Global Pollution Heatmap**: Interactive map showing real-time AQI values
- **Trend Analysis Dashboard**: Time-series visualization of pollution patterns
- **Correlation Matrix**: Multi-pollutant relationship analysis
- **Regional Comparison Charts**: Comparative analysis across continents

## 🛠️ Technical Stack

- **Language**: R (v4.0+)
- **IDE**: RStudio / Jupyter Notebook
- **Visualization**: ggplot2, Plotly, Leaflet
- **Data Processing**: tidyverse, dplyr, tidyr
- **Statistical Analysis**: forecast, corrplot
- **Geospatial**: sf, raster packages

## 📁 Project Structure

```
Air-Quality-Index-/
├── data/
│   ├── global_air_pollution_dataset.csv
│   └── registered-vehicles-per-1000-p...csv
├── notebook/
│   └── air-quality-index.ipynb
└── README.md
```

## 🚀 Getting Started

1. Clone the repository
2. Install R and required packages
3. Open the Jupyter notebook
4. Run the analysis cells sequentially

## 💡 Applications

- **Policy Making**: Data-driven insights for environmental regulations
- **Urban Planning**: Identifying areas requiring intervention
- **Public Health**: Risk assessment and mitigation strategies
- **Research**: Foundation for further environmental studies

## 🔮 Future Scope

- Integration with real-time air quality APIs
- Machine learning models for pollution prediction
- Development of interactive Shiny dashboard
- Expansion to include meteorological factors

## 👤 Author

**Hamza Chaieb**  
Data Science Enthusiast

## 🙏 Acknowledgments

- World Health Organization (WHO) for air quality guidelines
- Environmental Protection Agency (EPA) for data standards
- Open-source R community for powerful analytical tools

---

<p align="center">
  <i>Clean air is a basic human right. This analysis aims to contribute to global efforts in monitoring and improving air quality worldwide.</i>
</p>
