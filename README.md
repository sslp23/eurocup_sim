# UEFA Euro 2024 Predictions

This project aims to predict the results of the UEFA Euro 2024 using Machine Learning (ML) models and the Poisson Distribution. The project generates two estimates of team goals using Regression ML models. These estimates are then used as the expected values for the Poisson Distribution to predict match outcomes.

## Project Structure

The project consists of five Jupyter Notebook files that should be run in the following order:

1. **db creator.ipynb**: Creates and sets up the initial database required for the project.
2. **feats eng.ipynb**: Performs feature engineering to prepare the data for analysis and modeling.
3. **data analysis.ipynb**: Conducts exploratory data analysis to understand the data and derive insights.
4. **model.ipynb**: Builds and trains the Machine Learning models to estimate team goals.
5. **poisson model.ipynb**: Uses the estimates from the ML models as the Poisson Distribution expected values to predict match outcomes.

## Requirements

Ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Anaconda
