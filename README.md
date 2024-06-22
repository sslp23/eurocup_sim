# UEFA Euro 2024 Predictions

This project aims to predict the results of the UEFA Euro 2024 using Machine Learning (ML) models and the Poisson Distribution. The project generates two estimates of team goals using Regression ML models. These estimates are then used as the expected values for the Poisson Distribution to predict match outcomes.

## Data Sources

The data for this project can be obtained from the following sources:

- [FIFA World Ranking Dataset](https://www.kaggle.com/datasets/cashncarry/fifaworldranking?select=fifa_ranking-2024-04-04.csv): This dataset provides the FIFA rankings of national teams as of April 4, 2024.
- [Predicting FIFA 2022 World Cup with ML](https://www.kaggle.com/code/sslp23/predicting-fifa-2022-world-cup-with-ml#WC-Simulation): This dataset includes various features and predictions related to FIFA World Cup matches.

Please download these datasets and place them in a folder named `data` in the root directory of this project.

## Update
New version of the project uses an unified database to remove home/away bias in international game. I retrained the model using this structure.

## Project Structure

The project consists of five Jupyter Notebook files that should be run in the following order:

1. **db creator.ipynb**: Creates and sets up the initial database required for the project.
2. **feats eng.ipynb**: Performs feature engineering to prepare the data for analysis and modeling.
3. **new feats.ipynb**: Builds the unique database with away and home team in same dataframe
4. **ml model - one team.ipynb**: Builds and trains the Machine Learning models to estimate team goals.
6. **feats calculator.ipynb**: Calculates the features using the unique database.
5. **poisson model.ipynb**: Uses the estimates from the ML models as the Poisson Distribution expected values to predict match outcomes.

## Requirements

Ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Anaconda
