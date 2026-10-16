# Gauteng COVID-19 SEIHR Physics-Informed Neural Network

This repository contains the Python implementation and modelling dataset for the Honours research project **Physics-Informed Neural Network Modelling of COVID-19 Dynamics in South Africa using an SEIHR Model**.

The study uses a physics-informed neural network (PINN) to reconstruct COVID-19 hospital admissions in Gauteng and evaluate forecasting performance.

## Repository contents

- `Gauteng_PINN_DONE.ipynb` — PINN implementation, training, evaluation, figures and physics-consistency audits.
- `Gauteng_DATCOV_weekly_modelling_data.csv` — Weekly Gauteng hospital-admission modelling dataset.

## Requirements

Python 3 with NumPy, pandas, Matplotlib, SciPy and PyTorch.

## Running the notebook

1. Download the notebook and CSV from this repository.
2. Open the notebook in Google Colab.
3. Upload the CSV into the Colab session, keeping its original filename.
4. Run the notebook cells sequentially, starting from the first cell.
5. Allow the Adam and L-BFGS training stages to complete before evaluating the results.

## Reproducibility

The implementation includes fixed random seeds. Small numerical differences may occur across software versions and hardware environments.

The notebook contains the full-data 146-week experiment and the 100-week training experiment with a 46-week forecasting evaluation.
