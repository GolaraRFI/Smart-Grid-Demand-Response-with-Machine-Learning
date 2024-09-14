## Smart Grid Demand Response with Machine Learning
This project implements a demand response system that leverages machine learning to predict electricity load and make real-time adjustments to grid supply. The system is designed to enhance grid stability and efficiency by responding to varying load conditions.

### Objective

Develop a machine learning-based demand response system that automatically adjusts electricity load based on real-time grid conditions.

### Dataset

The dataset electricity_load/LD2011_2014.txt is part of the UCI Machine Learning Repository's Electricity Load Diagrams dataset. It contains electricity consumption data from 2011 to 2014 for 370 clients (or areas) across different time periods.

This is the dataset link: [Electricity Load Diagrams 2011-2014 Dataset](https://archive.ics.uci.edu/static/public/321/electricityloaddiagrams20112014.zip)

### Overview of the Dataset

- Dataset name: Electricity Load Diagrams 2011-2014
- File name: LD2011_2014.txt
- Content: It includes power consumption measurements for various clients. The columns in the dataset represent different clients, and the rows correspond to half-hourly electricity consumption values for each client.
- Time period covered: The dataset spans from 2011 to 2014, with measurements taken every 30 minutes.
- Columns: The first column is typically the timestamp, and the subsequent columns correspond to the electricity load (in kilowatts) for different clients/areas (often represented by MT_001, MT_002, etc.).

### Python Libraries Used

- Pandas: Data manipulation and analysis.
- NumPy: Numerical computing and array operations.
- Matplotlib: Data visualization through static, animated, and interactive plots.
- Scikit-learn: For model selection, preprocessing, linear regression, and performance evaluation.
- Seaborn: High-level data visualization library based on Matplotlib.
- Statsmodels: Time series analysis using ARIMA for forecasting.
- Prophet: Forecasting tool for time series data, particularly useful for trend detection and seasonality.
- Zipfile: Standard Python library for handling ZIP archives.

### Project Description

The primary goal of this project is to implement a demand response strategy by predicting periods of high electricity load and adjusting the grid’s supply in real-time. The machine learning models used in this project, including linear regression and time series forecasting, help anticipate high-demand periods and optimize energy distribution accordingly. This approach can significantly enhance energy efficiency, reduce operational costs, and prevent grid overloads during peak times.
