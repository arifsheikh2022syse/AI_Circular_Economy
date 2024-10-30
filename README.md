# AI Models for Demand-Supply Forecasting in Circular Economy Marketplaces

This repository contains Python notebooks designed for implementing and simulating various AI models for forecasting demand, predicting supply, and optimizing pricing in a Circular Economy (CE) marketplace. The models range from time-series forecasting to reinforcement learning approaches, offering a flexible base for developing demand-supply forecasting systems in CE applications.

> **Note**: These scripts serve as foundational models and are intended for educational and initial development purposes. The quality of results will depend on data quality, hyperparameter tuning, and model adjustments according to specific use cases. These scripts are provided "as is" without support or guarantee of optimized results.

---

## Files in this Repository

1. **`001_Input_Data_Generation.ipynb`**  
   Script for generating initial synthetic data, tailored to simulate realistic input data for CE marketplaces.

2. **`001_Inputdata_characterization.ipynb`**  
   Provides data characterization for understanding and preparing the input data before model training.

3. **`02_ARIMA_model_simulation.ipynb`**  
   Implements the ARIMA model for time-series forecasting of demand and supply in CE systems.

4. **`03_LinearRegression_model_simulation.ipynb`**  
   Linear Regression model for basic trend analysis in demand-supply forecasting.

5. **`04_LSTM_model_simulation.ipynb`**  
   Long Short-Term Memory (LSTM) network for sequential data analysis, capturing long-term dependencies in demand and supply fluctuations.

6. **`05_RandomForest_model_simulation.ipynb`**  
   Random Forest model for handling non-linear relationships in demand-supply forecasting.

7. **`06_Prophet_model_simulation.ipynb`**  
   Prophet model for capturing seasonality and trend dynamics in CE marketplaces.

8. **`07_GBR_model_simulation.ipynb`**  
   Gradient Boosting Regressor model, suitable for complex non-linear demand-supply interactions.

9. **`08_NeuralNetwork_model_simulation.ipynb`**  
   Neural Network model for managing intricate relationships within CE variables.

10. **`09_Q_Learning_Pricing_Optimization.ipynb`**  
    Q-Learning model for dynamic pricing optimization based on real-time market conditions.

11. **`10_Deep_Q_Learning_Pricing_Optimization.ipynb`**  
    Deep Q-Learning model for enhanced pricing optimization with reinforcement learning.

12. **`11_WasteGeneration_EconomicGrowth_Model.ipynb`**  
    Model analyzing the impact of waste generation and economic growth on CE marketplace dynamics.

---

## Important Notes

- **Input and Output Paths**: Customize paths in each script to match your storage structure. Example placeholders in the scripts include:
  - `input_file_path = r'/path/to/your/inputdata.csv'`
  - `output_plot_path = r'/path/to/your/output/plots/'`
  - Adjust these paths as necessary to reflect your local or cloud storage environment.
  
- **Model Customization**: These models are starting points. Effective results will depend on tuning hyperparameters, modifying model architectures, and optimizing based on specific data and use cases.

---

## License

This repository is released without any guarantee of support. Users are encouraged to adapt and modify the code as needed to suit their applications.
