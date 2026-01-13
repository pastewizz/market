# Market Demand Prediction

This project uses Linear Regression to predict market demand based on advertising spend and competitor activity.

## Files
- `Prediction.ipynb`: Jupyter notebook containing the analysis and model.
- `marketdata.csv`: Dataset used for training and prediction.

## How it works
The model uses `AdSpend` and `CompetitorActivity` as features to predict `MarketDemand`. It utilizes the `scikit-learn` library for the linear regression model and `matplotlib` for visualization.

## Setup
1. Install dependencies:
   ```bash
   pip install pandas scikit-learn matplotlib
   ```
2. Run the notebook `Prediction.ipynb`.
