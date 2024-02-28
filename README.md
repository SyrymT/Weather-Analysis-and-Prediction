Description

This project focuses on the analysis and prediction of Rome's climate changes over the last four decades, specifically examining temperature-related aspects such as annual average temperature and the number of fog days. Due to unreliable rain precipitation data, this aspect will not be considered in the analysis. The project aims to provide insights into the historical climate trends in Rome and predict future climate conditions based on the observed data.
Installation Instructions

Before running the analysis, ensure you have Python installed on your system. Then, install the necessary libraries using the following commands:

bash

pip install pandas matplotlib seaborn requests numpy scikit-learn

Usage

To perform the analysis, follow these steps:

    Configuration: Set up your analysis parameters, including the city name, start year/month, and end year/month.

    Data Mining & Cleaning: Extract weather data from the specified source (www.ilmeteo.it), clean the data to remove any inconsistencies, and prepare it for analysis.

    Exploratory Analysis: Analyze the cleaned dataset to identify correlations between variables and visualize how temperature and fog days have changed over time.

    Modeling: Utilize machine learning models to predict future temperature changes in Rome. Test different models and choose the best performing one based on cross-validation scores.

    Prediction: Use the selected model to make predictions about future climate conditions, specifically the average temperature for the year 2050.

Features

    Comprehensive Climate Analysis: Analyzes over four decades of climate data for Rome, focusing on temperature and fog days.
    Data Cleaning: Includes a detailed process for cleaning and preparing weather data for analysis.
    Exploratory Data Analysis (EDA): Utilizes statistical analysis and visualization to explore climate trends and patterns.
    Predictive Modeling: Employs machine learning techniques to predict future climate conditions in Rome.
    Insights into Climate Change: Provides valuable insights into how Rome's climate has changed historically and what future conditions might look like.

This project is intended for climate researchers, data scientists, and anyone interested in understanding and predicting climate changes in Rome.
