# Stellar Luminosity Regression

This project studies the relationship between stellar mass and luminosity using linear and polynomial regression implemented from first principles. It compares how both models fit a small instructional dataset and discusses the limits of interpolation and extrapolation.

## Requirements

- Python 3
- NumPy
- Matplotlib

## How to run

1. Install the required libraries: `pip install numpy matplotlib`.
2. Open `stellar_luminosity_hands_on.ipynb` in Jupyter Notebook or VS Code.
3. Select a Python kernel and run all cells from top to bottom.

## Main result

The polynomial representation using mass and mass squared produces a lower training error than the linear model for this nonlinear instructional dataset. This improves the fit within the observed range, but it does not by itself justify trusting predictions far outside that range.
