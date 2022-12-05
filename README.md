# Food_Prices_Time_Series_Forecast using ARIMA.
Using any of the box-Jenkins model(ARIMA) to predict the future prices of food stuff (rice and maize) with a defined PCA of 1, 0, 0

## Requirements: 
1. Pandas
2. numpy
3. matplotlib
4. ARIMA
5. Adfuller
6. seasonal_decompose
7. acf 
8. pacf

## Preview: Future prediction before and after decomposition (removal of noise) 


![rice_fut_comparison](https://user-images.githubusercontent.com/47100984/179356932-f54aedcf-3498-45df-9aa4-2fe3bb8f656f.png)


## Implementation
Using ARIMA model to predict the future prices of food:
1. Import the necessary library
2. explore the data
3. remove noise from the dataset
4. fit the data
5. predict future prices
6. compare the prices before and after decomposition (know your marginal error - RMSE)
