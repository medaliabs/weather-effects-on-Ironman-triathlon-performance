# The Effect of Weather Parameters on Triathlon Race Performance

A comprehensive analysis of how weather conditions influence triathlon performance, using data from Ironman and Ironman 70.3 races worldwide.

## Overview

This repository contains a study analyzing the relationship between various weather parameters and triathlon race performance. The study examines how factors such as elevation, temperature, humidity, wind speed, and other meteorological conditions affect athlete performance in endurance sports.

## Project Structure

```
├── data/                   # Dataset files
│   ├── README.md           # Data access information
│   ├── Full Ironman.csv    # Complete Ironman race data (72.43 MB)*
│   └── half Ironman 70.3.csv  # Ironman 70.3 race data (162.63 MB)*
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

## AI-Assisted Development

🤖 **Note**: This study utilized Large Language Models (LLMs) and AI coding agents to assist with:
- Code generation and optimization
- Data analysis workflow development
- Documentation and writing improvement
- Repository organization and structure

The core research methodology, data analysis, and scientific conclusions remain the work of the author, with AI tools serving as assistive technology for implementation and presentation.

## Getting Started

⚠️ **Data Access**: Due to file size limitations, the CSV datasets are not included in this repository. Please see [`data/README.md`](data/README.md) for information on accessing the datasets.

### Prerequisites

```bash
pip install -r requirements.txt
```

### Running the Analysis

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Contact [medalielabbassi@gmail.com](mailto:medalielabbassi@gmail.com) for dataset access
4. Place the CSV files in the `data/` directory
5. Navigate to the `notebooks/` directory
6. Start with `Ironman_Regression_Analysis.ipynb` for the main analysis

*Note: CSV files are not included due to size (72-163 MB each). See data/README.md for access information.

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

Master's Project in [AI and Data Science/ENSA/Sultan Moulay Sliman University]
[Mohamed Ali Elabbassi]
[2025]

## License

This project is for academic purposes. Please cite appropriately if using this work.
