# MLE-Assignment

# MLE Assignment: DON Concentration Prediction

This repository contains a Google Colab notebook to predict DON concentration in corn using hyperspectral data from `MLE-Assignment.csv`.

## Setup
1. Upload `MLE-Assignment.csv` to Google Drive.
2. Open the notebook in [Google Colab](https://colab.research.google.com/drive/15GGdIPmKkvpsyj8wmWwu_tZktaBu9AAO?usp=sharing).
3. Run all cells (dependencies auto-installed).

## Usage
- **Pipeline**: Preprocesses data, visualizes it, trains a neural network, evaluates it, and explains predictions with SHAP.
- **Outputs**: Saves model (`don_prediction_model.h5`), scaler (`scaler.pkl`), and plots to Google Drive.
- **Prediction**: Use `predict_new_data(sample_data)` with 448 spectral values.

## Repository
- `MLE-Assignment.csv`: Dataset
- `MLE-Assignment.ipynb`: Full pipeline
- Outputs: Model, scaler, and PNGs (after running)
