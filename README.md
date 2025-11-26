# Advanced Time Series Forecasting Using LSTM With Self-Attention

This project implements a complete end-to-end deep learning pipeline for multivariate time-series forecasting, combining LSTM networks with a custom Self-Attention mechanism. The model is built in PyTorch, performs hyperparameter tuning, trains both Attention-LSTM and Baseline LSTM models, compares their performance, and visualizes predictions, losses, and attention weights.

## Features
- End-to-end automated pipeline
- Custom Self-Attention + LSTM model
- Baseline LSTM comparison
- Hyperparameter tuning
- Evaluation metrics (RMSE, MAE, MAPE, MSE)
- Visualizations: predictions, losses, residuals, attention weights

## Dataset
Uses California Housing dataset and converts it into a synthetic multivariate time series with:
- Time index features
- Sine/cosine time encodings
- Lag features
- Rolling statistics

## Model Architectures
### Baseline LSTM
- 2-layer LSTM
- Dropout
- Fully connected regression

### Attention-LSTM
- LSTM encoder
- Custom Self-Attention layer
- Dense regression layers

## How to Run
1. Install dependencies:

2. Run script:

## Outputs
- Actual vs predicted plots
- Loss curves
- Residual histograms
- Attention visualizations
- Full performance report

## Hyperparameter Tuning
The script scans:
- Learning rates: 0.001, 0.0005, 0.0001
- Hidden dims: 64, 128, 256
- Batch sizes: 32, 64, 128

## Notes about file types / Gitingest
Gitingest and repo preview tools cannot show the contents of binary files like `.docx`. Always keep a `README.md` (plain Markdown) in your repo so it displays correctly across tools.

## Future Improvements
- Multi-head attention
- Transformer-based model
- Model saving/loading
- Streamlit/FastAPI deployment


