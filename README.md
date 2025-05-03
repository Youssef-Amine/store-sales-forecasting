# store-sales-forecasting
This project aims to predict sales and inventory required at each store to avoid over-stocking and under-stocking with time series analysis.
Our data include daily sales for 1,115 Rossmann (drugstore compagny) stores and other features influencing sales and we will predict their daily sales for up to six weeks in advance.

## Objectives

- Analyze and preprocess features.
- perform a time series analysis and build an adapt time series model
- build XGBoost and LSTM models 
- Evaluate models with Root Mean Squared Error (RMSE) because the errors are squared before they are averaged, thus penalizing large errors. In our case, RMSE will give the prediction with minimum error (i.e penalize high errors) so that inventory can be managed properly.

---

## Project structure

```bash
store-sales-forecasting/
|
├── README. md # Project description
├── requirements.txt # Packages required
|
├── downloaddata.txt # Data link  
|
├── SalesPrediction.ipynb # Working notebook
|

---

---
```



## 🔖 Technologies used

- Python (pandas, numpy, matplotlib, seaborn, math, datetime)
- Sklearn (xgBoost, metrics)
- statsmodels
- pmdarima
- tensorflow

- 
## Results
Best ARIMA RMSE:  5845.057201792976
XGBoost RMSE : 2789.94
LSTM RMSE : 2389.38
We used the Root Mean Squared Error (RMSE) to evaluate and validate the performance of various models used. Let's see which model performed better.

We can see from the above result that LSTM performs the best followed by XGBoost and ARIMA.

Our final model is then LSTM and we'll predict the sales of the next 6 weeks for each store.

---


## 📚 References

- Kaggle dataset: [https://www.kaggle.com/datasets/udaymalviya/bank-loan-data](https://www.kaggle.com/c/rossmann-store-sales)

---

> Portfolio project developed in 2025 by Youssef SAWADOGO. If you have any questions, please contact me via wyoussef.sawadogo@gmail.com.
