# Evolving Interpretable Fuzzy Rule-Based Systems with Genetic Programming for Predictive Maintenance

## Project Overview

This project implements an evolving interpretable fuzzy rule-based system using genetic programming for predictive maintenance. The system is designed to predict the Remaining Useful Life (RUL) of turbofan engines using sensor data and operational settings.

## Dataset

The project uses the NASA Turbofan Engine Degradation Simulation Dataset, which includes:

- Training datasets (FD001 - FD004)
- Testing datasets (FD001 - FD004)
- RUL (Remaining Useful Life) values for each dataset

## Features

- Data preprocessing and normalization
- Feature engineering (lag features, window statistics, Fourier transform features)
- PCA and t-SNE visualization
- Fuzzy rule-based system implementation
- Genetic programming for evolving fuzzy rules

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-fuzzy
- Scikit-learn
- SciPy

## Installation

1. Clone this repository:
git clone https://github.com/fesarikaya/GP-Fuzzy.git

2. Install the required packages:
pip install numpy pandas matplotlib seaborn scikit-fuzzy scikit-learn scipy

## Usage

1. Ensure your data files are in the `Data` directory.
2. Run the preprocessing script: GP_Fuzzy_Project.ipynb

## Project Structure

- `GP_Fuzzy_Project.py`: Main script containing data preprocessing, feature engineering, and fuzzy system implementation
- `Data/`: Directory containing the dataset files

## Methodology

1. Data Preprocessing
2. Feature Engineering
3. Fuzzy Rule-Based System Implementation
4. Genetic Programming for Rule Evolution
5. Model Evaluation

## Author

Ferhat Sarikaya
