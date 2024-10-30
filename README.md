# AI Models for Demand-Supply Forecasting in CE Marketplaces

This repository contains 11 Python scripts designed for demand-supply forecasting, resource management, and dynamic pricing within Circular Economy (CE) marketplaces. Each notebook demonstrates different AI models and techniques used for forecasting and optimization.

## Disclaimer

These scripts are base models intended for educational and experimental use. The quality of results is highly dependent on factors such as input data quality, feature engineering, and hyperparameter tuning. There is no guarantee of achieving specific outcomes, as these factors can significantly influence model performance. Additionally, these models come without support, and users are encouraged to customize and improve them as needed.

## Files

1. **01_inputdata_characterization.ipynb** - Characterizes and preprocesses input data for model training.
2. **02_ARIMA_model_simulation.ipynb** - Implements the ARIMA model for time-series forecasting.
3. **03_LinearRegression_model_simulation.ipynb** - Applies linear regression for demand-supply predictions.
4. **04_LSTM_model_simulation.ipynb** - Uses LSTM networks to model sequential dependencies in data.
5. **05_RandomForest_model_simulation.ipynb** - Leverages Random Forest for non-linear forecasting in CE marketplaces.
6. **06_Prophet_model_simulation.ipynb** - Utilizes the Prophet model to capture seasonality and trends.
7. **07_GBR_model_simulation.ipynb** - Implements Gradient Boosting Regressor for robust forecasting.
8. **08_NeuralNetwork_model_simulation.ipynb** - Trains a Neural Network model to handle complex interdependencies.
9. **09_Q_Learning_Pricing_Optimization.ipynb** - Uses Q-learning for dynamic pricing optimization.
10. **10_Deep_Q_Learning_Pricing_Optimization.ipynb** - Applies Deep Q-Learning for advanced pricing strategies.
11. **11_WasteGeneration_EconomicGrowth_Model.ipynb** - Analyzes waste generation and economic growth impacts in CE systems.

## Usage

Each notebook can be executed independently. Simply open the desired notebook and run the cells in order to reproduce the analysis or model results. Please note that significant improvements may require further tuning and domain-specific adjustments.

## Requirements

To run these notebooks, make sure you have installed the necessary Python libraries, such as `numpy`, `pandas`, `scikit-learn`, `tensorflow`, and `matplotlib`.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
