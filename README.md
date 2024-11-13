
# Calgary Crime Data Analysis and Prediction

## Project Overview
This project analyzes and predicts crime trends in Calgary using monthly crime data (2018-2024) from the City of Calgary's data portal. The goal is to identify patterns in crime occurrences and develop an LSTM neural network model to forecast future crime levels.

## Approach
1. **Data Preparation**: Import, clean, and preprocess data for consistency.
2. **Exploratory Data Analysis (EDA)**: Identify patterns in crime distribution by community, type, and time.
3. **Modeling**: Build and train an LSTM neural network, ideal for time series predictions, to forecast future crimes.

## Key Findings
- **Community Insights**: Beltline and Forest Lawn have the highest crime rates, while communities like 13M and 02K report the least.
- **Crime Types**: Theft from Vehicle, Theft of Vehicle, and Break & Enter - Commercial are the most frequent crimes.
- **Temporal Trends**: Crime peaks were observed in 2019, with seasonal variations indicating monthly crime trends.

## Prediction Model
An LSTM model was developed with 50 units, dropout layers to prevent overfitting, and MSE loss. Trained over 100 epochs, the model achieved good predictive performance, with decreasing validation loss indicating generalizability on unseen data.

## Conclusion
This project provided valuable insights into crime patterns in Calgary and demonstrated the potential of predictive modeling for proactive crime prevention and resource allocation.
