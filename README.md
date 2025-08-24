## CFG Degree Data Science Group Project
# Flight Delays Weather Data Analysis

## Contributors: 
- [Heather](https://github.com/hlmbrt)
- [Laura](https://github.com/Lanthanum89)
- [Danielle](https://github.com/daniellestewart2023)
- [Riya](https://github.com/RiyaAbraham9)
- [Maya](https://github.com/Maya-Does-Code)
- [Claire](https://github.com/SophiaClaire53)

## Summary
This project explores the relationship between flight delays and weather conditions using real-world flight and weather datasets. The analysis is performed in a Jupyter notebook and includes data cleaning, exploratory data analysis, and predictive modelling. 

## Project Structure
- **Data Project Notebook.ipynb**: Main notebook containing code which includes data exploration, merging of data sources (API), filtering to a manageable sized data set and predictive modelling. 
- **Data/**: Contains raw and processed datasets, including flight delay records and weather data.
- **Supplementary Notebooks/**: Additional notebooks for data exploration, cleaning, and modelling.


## Key Features
- Data cleaning and preprocessing for flight and weather datasets
- Exploratory data analysis (EDA) with visualisations
- Handling missing values and class imbalance
- Merging flight and weather data to call upon a weather API
- Predictive modeling using machine learning (Logistic Regression, Random Forest)
- Evaluation of model performance and discussion of results

## How to Use
1. Clone this repository to your local machine.
2. Install the required Python packages (see below).
3. Open `Data Project Notebook.ipynb` in Jupyter or any IDE of your choice.
4. Run the notebook cells in order to reproduce the analysis and results.

## Requirements
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- openmeteo-requests
- requests-cache
- retry-requests

Install requirements with:

```
pip install pandas numpy matplotlib seaborn scikit-learn openmeteo-requests requests-cache retry-requests
```

## Data Sources
- Bureau of Transport Statistics – flight delays data for January 2025 for internal flights in the USA (delays_by_flight.csv)
- Historical Weather API (open-meteo) – Daily weather data for origin and destination airports (https://open-meteo.com/en/docs/historical-weather-api)
- Kaggle – IATA airport codes and longitude and latitude values (airports.csv) 

## Results & Insights
- Florida is the State with the most flight delays for any cause, followed by Texas.
- Most flights are not delayed by weather, leading to class imbalance in the data.
- Models are highly accurate at predicting non-delayed flights, but less effective at identifying weather-related delays as a result of the imbalanced data.
- Further work is needed to improve predictions for rare but important weather delay events. This could include work on balancing our data set for predictive modelling or pivot to other reasons for flight delays.



