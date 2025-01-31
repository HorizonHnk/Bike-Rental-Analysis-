# Python Bike Rental Analysis 🚲

## Overview
This repository contains a Jupyter notebook for analyzing Seoul's bike-sharing system data. The analysis explores rental patterns, weather impacts, and seasonal trends in bike usage.

## Dependencies
The analysis requires the following Python packages:
- pandas
- datetime
- plotly.express

## Data
The analysis uses the `seoul_bike_data_renamed.csv` dataset containing the following information:
- Rental dates and times
- Number of rented bikes
- Weather conditions (temperature, humidity, etc.)
- Holiday information
- Functioning status of the system

## Analysis Sections

### 1. Data Preprocessing
- Loading and cleaning the dataset
- Converting date formats
- Handling boolean columns (holidays and system functioning status)

### 2. Time Series Analysis
The notebook includes visualizations of:
- Hourly bike rental patterns
- Daily rental totals
- Seasonal trends in usage

### 3. Weather Impact Analysis
Exploration of relationships between:
- Temperature and rental numbers
- Other weather parameters and usage patterns
- Visualization through scatter plots with trend lines

### 4. Usage Patterns
Investigation of:
- Average hourly usage patterns
- Seasonal variations in daily patterns
- Special event analysis (New Year's Eve)

## Structure
```
.
├── README.md
├── data/
│   └── seoul_bike_data_renamed.csv
└── notebooks/
    └── notebook_template.ipynb
```

## Getting Started

1. Clone this repository:
```bash
git clone https://github.com/your-username/seoul-bike-rental-analysis.git
```

2. Install required packages:
```bash
pip install pandas datetime plotly
```

3. Run the Jupyter notebook:
```bash
jupyter notebook notebooks/notebook_template.ipynb
```

## Contributing
Feel free to fork this repository and submit pull requests for any improvements.

## License
This project is open source and available under the [MIT License](LICENSE).

---
> **Note**: Make sure you have the dataset `seoul_bike_data_renamed.csv` in the `data/` directory before running the analysis.
