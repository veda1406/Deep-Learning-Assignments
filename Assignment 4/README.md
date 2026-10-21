# Assignment 4: LSTM-Based Sales Forecasting

## Objective
Develop an LSTM-based model to forecast time-series sales data.

## Dataset
Sales Forecasting dataset downloaded from Kaggle using KaggleHub: `rohitsahoo/sales-forecasting`. The notebook reads `train.csv`, converts `Order Date` to datetime, and aggregates sales by month.

## Implementation
- Download and load the sales dataset.
- Convert order dates to datetime format.
- Aggregate sales into monthly totals and visualize the trend.
- Split the time series chronologically into training and testing data.
- Normalize sales values using Min-Max scaling.
- Create sequences from the previous 12 time steps.
- Build and train an LSTM model.
- Generate predictions and inverse-transform them to the original sales scale.
- Evaluate forecasting performance using RMSE.
- Plot actual versus predicted sales.

## Technologies
- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- KaggleHub

## Run
Open `DL_A4.ipynb` in Google Colab. Run the cells in order and allow KaggleHub to download the dataset. An internet connection is required for the initial download.

## Files
- `DL_A4.ipynb` — implementation notebook
- `Vedanti Raut_CSEAI_E_38_A4.pdf` — practical record / exported report
