# The Effect of Weather Parameters on Triathlon Race Performance

A comprehensive analysis of how weather conditions influence triathlon performance, using data from Ironman and Ironman 70.3 races worldwide.

## Overview

This repository contains my Master's project analyzing the relationship between various weather parameters and triathlon race performance. The study examines how factors such as temperature, humidity, wind speed, and other meteorological conditions affect athlete performance in endurance sports.

## Project Structure

```
├── data/                   # Dataset files
│   ├── Full Ironman.csv    # Complete Ironman race data
│   └── half Ironman 70.3.csv  # Ironman 70.3 race data
├── notebooks/              # Jupyter notebooks for analysis
│   ├── Ironman_Regression_Analysis.ipynb         # Main regression analysis
│   ├── Half_Ironman_Quantile_Regression_Analysis.ipynb  # Quantile regression
│   ├── Ironman_DecisionTree_Analysis.ipynb       # Decision tree modeling
│   ├── weather_data_retreive_ironman.ipynb       # Weather data collection
│   ├── add_elevations_final.ipynb                # Elevation data processing
│   ├── water_temperature_estimation.ipynb        # Water temperature analysis
│   ├── wbgt.ipynb                                # Wet Bulb Globe Temperature
│   ├── quantile_regression.ipynb                 # Additional quantile analysis
│   ├── statical analysis.ipynb                   # Statistical analysis
│   ├── concatenation.ipynb                       # Data concatenation
│   └── Events_scrap.ipynb                        # Event data scraping
├── docs/                   # Documentation and reports
│   ├── project_report_The_Effect_of_Weather_Parameters_on_Triathlon_Race_Performance.docx
│   └── Scientific_Paper_The_Effect_of_Weather_Parameters_on_Triathlon_Race_Performance.docx
└── src/                    # Source code (future Python modules)
```

## Key Findings

This research examines the impact of weather conditions on triathlon performance through:

- **Regression Analysis**: Linear and multiple regression models to quantify weather effects
- **Quantile Regression**: Understanding performance impacts across different athlete ability levels
- **Decision Tree Analysis**: Non-linear relationship discovery
- **Statistical Analysis**: Comprehensive statistical testing and validation

## Methodology

1. **Data Collection**: Gathered race data from Ironman events worldwide
2. **Weather Data Integration**: Retrieved historical weather data for race locations and dates
3. **Feature Engineering**: Created derived weather metrics (WBGT, heat index, etc.)
4. **Statistical Modeling**: Applied various machine learning and statistical techniques
5. **Performance Analysis**: Analyzed effects across different race distances and conditions

## Technologies Used

- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **Scikit-learn**: Machine learning models
- **Matplotlib/Seaborn**: Data visualization
- **NumPy**: Numerical computations
- **Jupyter Notebooks**: Interactive analysis environment

## Getting Started

### Prerequisites

```bash
pip install -r requirements.txt
```

### Running the Analysis

1. Clone the repository
2. Install dependencies
3. Navigate to the `notebooks/` directory
4. Start with `Ironman_Regression_Analysis.ipynb` for the main analysis

## Results

The analysis reveals significant relationships between weather parameters and triathlon performance, with implications for:
- Race planning and scheduling
- Athlete preparation and strategy
- Performance prediction models
- Safety considerations for race organizers

## Documentation

Detailed findings and methodology are available in:
- **Project Report**: Comprehensive analysis and results
- **Scientific Paper**: Academic presentation of findings

## Author

Master's Project in [Your Program/University]
[Your Name]
[Year]

## License

This project is for academic purposes. Please cite appropriately if using this work.
