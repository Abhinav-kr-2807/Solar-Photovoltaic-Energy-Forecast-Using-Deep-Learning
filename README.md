# Enhanced Solar PV Energy Prediction Using Deep Learning Models

## Project Description

This repository presents a deep learning approach to enhance the prediction accuracy of solar photovoltaic (PV) energy generation. The project focuses on leveraging Recurrent Neural Networks (RNN), Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU) models with meticulous hyperparameter tuning.

The accurate prediction of solar PV energy is crucial for various applications including:
- Energy integration into the grid
- Economic decisions related to renewable energy investments
- Environmental impact assessment
- Ensuring energy security

### Model Performance Comparison

The models were evaluated both before and after applying Grid Search Cross-Validation. LSTM emerged as the best-performing algorithm, achieving an R2 score of 0.652 after hyperparameter optimization using Grid Search.

## Key Features

- **RNN, LSTM, GRU Models:** Implemented and compared for solar PV energy prediction.
- **Hyperparameter Tuning:** Utilized Grid Search CV to optimize model performance.
- **Data Analysis:** Explored insights into energy generation patterns and predictive accuracy.
- **Visualization:** Included visual representations of model performance and energy predictions.

## Dataset

The dataset used contains historical solar PV energy generation data, including meteorological and environmental factors that influence solar energy production.

## Project Structure

- `data/`: Contains datasets used for training and evaluation.
- `models/`: Python scripts for RNN, LSTM, and GRU models.
- `notebooks/`: Jupyter notebooks for data exploration, model training, and evaluation.
- `results/`: Output files, model performance metrics, and visualizations.
- `README.md`: This file, providing an overview of the project.

## Installation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/solar-pv-energy-prediction.git
   cd solar-pv-energy-prediction
