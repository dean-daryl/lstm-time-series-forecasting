# Beijing Air Quality Forecasting

Time series forecasting of PM2.5 concentrations using LSTM neural networks.

## Dataset
- **Input**: Meteorological data (temperature, pressure, wind, humidity)
- **Output**: PM2.5 air pollution levels
- **Period**: 2010-2013 hourly measurements

## Usage
1. Open `Air Quality Forecasting Starter Code.ipynb`
2. Run cells to train LSTM model
3. Generate predictions on test set

## Requirements
```bash
pip install pandas numpy matplotlib tensorflow scikit-learn
```

## Files
- `data/train.csv` - Training data with PM2.5 targets
- `data/test.csv` - Test data for predictions
- `Air Quality Forecasting Starter Code.ipynb` - Main notebook