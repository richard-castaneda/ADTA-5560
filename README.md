# ADTA 5560: LSTM with Time-Series Data Project

## Project Overview
This project delves into the use of a Long Short Term Memory (LSTM) neural network model to predict Tesla stock prices using time-series data. The model's architecture includes a hidden layer for complex data representation and feature extraction, and an output layer for predictions.

### Core Concepts
- **LSTM Architecture:** Utilizes a hidden layer and an output layer for efficient feature extraction and prediction making.
- **Memory Cells:** These are integral in retaining previous states and current outputs, updated through complex mathematical operations during training.
- **Normalization Techniques:** Implemented using a MinMaxScaler for data preparation and ensuring effective model training.

## Data Analysis
- **Data Utilized:** 5 years of historical Tesla stock data.
- **Data Preparation:** Includes normalization, transformation, and formatting into a time series array.
- **Exploratory Analysis:** Visual examination to ensure accuracy of the closing price data from Yahoo Finance.

## Modeling and Predictions
- **Sequence Length:** An input sequence of 60 days to capture long-term dependencies.
- **Batch Size Optimization:** Employing a batch size of 32 for efficient data processing.
- **Model Structure:** Incorporates LSTM cells, dropout layers, and 'relu' activation functions.

## Results and Insights
- **Forecast Accuracy:** Analysis of the model’s prediction against actual Tesla stock trends.
- **Parameter Adjustments:** Exploration of various parameter settings to enhance prediction accuracy.
- **Future Predictions:** Predicted an upward trend in Tesla stock, contrasted with actual downward trend observed.

## Redesign and Improvement
- **Model Redesign:** Adjusting parameters like test percentage, neurons count, and dropout rates to refine the LSTM network.
- **Comparative Analysis:** Evaluating changes in model performance with different parameter configurations.

## Conclusion
The project highlights the intricacies of using LSTM neural networks for stock price prediction, emphasizing the importance of parameter tuning and the potential impact of various external factors on market trends.

---

### Note
This project is part of the Advanced Data Analytics and Time Series Analysis course (ADTA 5560), focusing on practical applications of LSTM neural networks in financial data analysis.

---

For more details on methodology and specific code implementations, please refer to the Jupyter notebooks and scripts included in this repository.
