# LLMs-for-time-series-forecasting

The project focuses on leveraging Large Language Models (LLMs) for time series
forecasting, a field crucial for predicting future trends based on historical data. Time series data
appears in various domains such as finance, healthcare, climate studies, and retail. Traditionally,
models like ARIMA, LSTMs, and XGBoost have been employed for forecasting. However,
LLMs, originally designed for natural language processing tasks, have shown potential in
addressing some challenges in time series forecasting.

The project highlights how LLMs can be adapted to work with numerical time series data by
converting it into a textual format, enabling models like GPT-4 and T5 to understand it better. It
also investigates how LLMs perform against traditional forecasting models and explores their
limitations, such as struggles with multi-seasonal patterns or resource-intensive training
requirements.

## Main Contribution

The primary contributions of this study include:

1. Dataset Utilization:

Employed historical financial data from 2015 to 2020.

Standardized the sequence length to 60 for all models.

Encoded numerical sequences into text format for LLM compatibility.


2. Exploration of Models:

Analyzed traditional models like ARIMA and XGBoost for baseline comparisons.

Trained LSTM networks to handle long-term dependencies in time series data.

Adapted transformer-based models, including T5 and GPT-2, for numerical sequence prediction.

3. Evaluation Metrics:

Used metrics such as Root Mean Square Error (RMSE) and Mean Absolute Percentage Error (MAPE) to compare model performance.

4. Experimental Insights:

Demonstrated the ability of LLMs to outperform traditional models in datasets with clear patterns.

Highlighted challenges in multi-period forecasting and areas for future improvement.
