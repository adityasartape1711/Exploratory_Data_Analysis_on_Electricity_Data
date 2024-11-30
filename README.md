
# Power Consumption Analysis - Delhi Regions

## Overview

This project analyzes power consumption data for various regions of Delhi. The dataset contains power consumption information for multiple power distribution companies, categorized by different timeslots and months. The analysis focuses on visualizing trends, seasonal patterns, and identifying potential outliers and anomalies in power usage over time. This project uses various Exploratory Data Analysis (EDA) techniques to extract meaningful insights from the data.

## Project Description

The goal of this project is to explore and analyze the power consumption data of Delhi's regions, namely DELHI, BRPL, BYPL, NDPL, and NDMC, and identify trends, patterns, and potential anomalies in power usage over different times and seasons. The data is collected across different months and is represented for various timeslots throughout the day.

The analysis includes:
- **Trend Analysis**: Visualizing how power consumption changes over time.
- **Seasonal Patterns**: Identifying seasonal trends in power consumption for different regions.
- **Cumulative Power Consumption**: Understanding the cumulative impact of power usage over time.
- **Outlier Detection**: Identifying regions and timeslots with anomalous power consumption.
- **Time-Series Decomposition**: Breaking down the data into seasonal, trend, and residual components for better understanding.

## Key Features

- **Trend Analysis**: Visualize the trend of power consumption across multiple regions and timeslots.
- **Seasonal Trends**: Map months to seasons and visualize how power consumption varies by season.
- **Rolling Mean**: Smoothing power consumption data to identify long-term trends.
- **Outlier Detection**: Boxplots to detect any power consumption outliers.
- **Time-Series Decomposition**: Decompose time-series data to observe seasonality, trend, and residuals.
- **Power Consumption Heatmap**: Visualize power consumption across different months and timeslots using a heatmap.
- **Cumulative Consumption**: Track cumulative power usage for a better understanding of overall consumption over time.

## Technologies Used

- **Python**: Core language used for the analysis.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Plotting graphs and visualizations.
- **Seaborn**: Statistical data visualization and advanced plots.
- **Statsmodels**: For time-series decomposition.
- **Jupyter Notebook**: Environment for performing and sharing analysis.

## Project Structure

```
Power-Consumption-Analysis-Delhi-Regions/
│
├── data/
│   └── combined_delhi_data_2022.csv  # The main dataset used for analysis
│
├── notebooks/
│   └── EDA_Power_Consumption_Analysis.ipynb  # Jupyter notebook for the analysis
│
├── results/
│   └── output_graphs/                  # Folder containing visualizations
│
├── README.md                           # Project description

## How to Run the Project

To run this project locally, follow the steps below:

### Prerequisites

- Python 3.6 or higher
- Jupyter Notebook (or any other Python environment like VS Code)

### Steps to Run the Project

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/Power-Consumption-Analysis-Delhi-Regions.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Power-Consumption-Analysis-Delhi-Regions
    ```
3. Open the `EDA_Power_Consumption_Analysis.ipynb` notebook and run the cells to perform the analysis and visualize the results.

## Results

The following insights were gained from the analysis:

1. **Power Consumption Trends**: Power consumption fluctuates over time and is influenced by both seasonal factors and regional demand.
2. **Seasonal Patterns**: Summer months generally see higher power consumption, especially in regions like NDPL and BRPL.
3. **Cumulative Consumption**: Cumulative power consumption reveals significant growth over the months, indicating an increase in power demand.
4. **Outliers**: Certain months and timeslots exhibited significant deviations in power consumption, which might require further investigation.
5. **Time-Series Decomposition**: The decomposition revealed clear seasonal patterns with a steady upward trend in power consumption, particularly in the summer months.

## Future Improvements

1. **Predictive Modeling**: Implement machine learning models to predict future power consumption based on historical data.
2. **Anomaly Detection**: Apply advanced anomaly detection techniques such as Isolation Forest or Autoencoders to detect unusual consumption patterns.
3. **Real-Time Data Analysis**: Integrate real-time power consumption data to provide live monitoring and analysis.
4. **Optimization**: Analyze power consumption data at a granular level (e.g., per region or per timeslot) to optimize power distribution strategies.
5. **More Complex Visualizations**: Incorporate more advanced visualizations such as interactive dashboards using tools like Plotly or Dash.

---
