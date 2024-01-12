# Healthcare Trends Analysis and Predictive Modeling

## Overview
This project involves the analysis of healthcare trends and the development of predictive models for estimating total charges and costs associated with hospital discharges. The Python code provided here uses machine learning techniques, specifically the LightGBM library, to create models for forecasting financial implications related to medical care.

## Contents
- **Data Preparation:** The code extracts relevant columns from Hospital Inpatient Discharges (SPARCS De-Identified) from the year 2009 to 2021 listed in https://health.data.ny.gov/  and preprocesses them for regression analysis.
  
- **Model Building:** Utilizes LightGBM to create two distinct models - one for predicting 'Total Charges' and another for predicting 'Total Costs'.

- **Training and Evaluation:** Splits the dataset, trains the regression models, and evaluates their performance using Mean Squared Error (MSE) and R-squared metrics.

- **Predictive Analysis:** Demonstrates how to make predictions for future years based on the trained models, with a specific focus on a desired medical procedure code.

## Usage
1. Ensure you have the required Python libraries installed.
   
2. Run the Jupyter notebook containing the Python code.

3. Follow the step-by-step instructions and comments in the notebook to understand the data analysis and predictive modeling process.

## Future Scope
The project's future scope involves expanding the dataset to include more cities, incorporating additional variables for a more comprehensive analysis, and refining the predictive models to enhance accuracy.

## Contributions
Contributions are welcome! Feel free to fork this repository, make improvements, and submit pull requests.


