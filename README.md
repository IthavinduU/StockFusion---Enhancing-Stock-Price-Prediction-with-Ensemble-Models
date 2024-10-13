# Enhancing Stock Price Prediction with Ensemble Models

This project focuses on using ensemble learning techniques to improve the accuracy of stock price predictions. By combining the strengths of multiple machine learning models, ensemble methods provide a robust framework for forecasting future stock prices based on historical data, technical indicators, and market trends.

## Project Overview

Stock price prediction is inherently challenging due to the complex, dynamic nature of the market. Ensemble models such as Bagging, Boosting, and Stacking are employed in this project to combine the outputs of various machine learning models, thereby improving the overall predictive performance and reducing model variance.

### Key Features

- **Data Preprocessing**: 
  - Handling missing values and normalizing historical stock data.
  - Engineering technical indicators (e.g., Moving Averages, Relative Strength Index (RSI), MACD).
  
- **Ensemble Learning Techniques**:
  - **Bagging**: Leveraging Random Forest to create multiple versions of the model and aggregate their predictions.
  - **Boosting**: Using XGBoost and LightGBM to focus on correcting errors made by prior models.
  - **Stacking**: Combining diverse models like Decision Trees, LSTM, and SVM to produce a final, more accurate prediction.
  
- **Model Evaluation**:
  - Performance metrics include Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared to evaluate model accuracy.
  
- **Backtesting**:
  - Simulating the models’ performance on historical data to assess real-world accuracy before making predictions on future stock prices.
