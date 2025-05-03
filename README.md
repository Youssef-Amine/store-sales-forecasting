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
bank-loan-repayment/
|
├── README. md # Project description
├── requirements.txt # Packages required
|
├── Data folder  
|
├── SalesPrediction.ipynb # Working notebook
|

---

---

## 🔖 Technologies used

- Python (pandas, numpy, matplotlib, seaborn, math, datetime)
- Sklearn (xgBoost, metrics)
- statsmodels
- pmdarima
- tensorflow


---


## 📚 References

- Kaggle dataset: [https://www.kaggle.com/datasets/udaymalviya/bank-loan-data](https://www.kaggle.com/c/rossmann-store-sales)

---

> Portfolio project developed in 2025 by Youssef SAWADOGO. If you have any questions, please contact me via wyoussef.sawadogo@gmail.com.
