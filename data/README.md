# Dataset Information

This directory contains the datasets used in the triathlon weather analysis project.

## Files

### Main Datasets
- **`Full Ironman.csv`** (72.43 MB) - Complete Ironman race data with weather parameters
- **`half Ironman 70.3.csv`** (162.63 MB) - Ironman 70.3 race data with weather parameters

## Data Access

⚠️ **Note**: Due to GitHub's file size limitations, the CSV files are not stored in this repository.

### How to Obtain the Data

1. **Contact the Author**: Email [medalielabbassi@gmail.com](mailto:medalielabbassi@gmail.com) to request access to the datasets
2. **Academic Use**: These datasets are available for academic research purposes
3. **Data Privacy**: All data has been anonymized and aggregated for research use

### Data Structure

Both datasets contain the following key columns:
- Race information (location, date, distance)
- Weather parameters (temperature, humidity, wind speed, etc.)
- Performance metrics (race times, splits)
- Environmental factors (elevation, water temperature, WBGT)

### Data Processing Scripts

The notebooks in this repository show how the data was processed and analyzed:
- `weather_data_retreive_ironman.ipynb` - Weather data collection
- `add_elevations_final.ipynb` - Elevation data processing  
- `concatenation.ipynb` - Data merging and preparation

## Citation

If you use this data in your research, please cite:
```
Elabbassi, M. A. (2025). The Effect of Weather Parameters on Triathlon Race Performance. 
Master's Project, AI and Data Science, ENSA, Sultan Moulay Sliman University.
```

## License

This data is provided for academic research purposes. Please ensure proper attribution when using.
