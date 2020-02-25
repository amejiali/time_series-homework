# Yen Futures - Model Fitting Analysis

During this assignment, the following models were applied to see which one is the best to predict the Yen future behaviour accordingly:

    - ARMA
    - ARIMA
    - GARCH
    - Linear Regression
---

## ARMA

The following DataFrame was used to run the ARMA Model Analysis:

![DF](Images/Yen_df.png)

Based on that DF, the Settle Price was Decomposed into Trend and Noise accordingly for the whole analysis:

![Settle](Images/Yen_Futures_Settle.png)

![PriceTrend](Images/Price_vs_Trend.png)

![Noise](Images/Noise.png)

The Correlation and PArtial Correlation were calculated to run the ARMA Model:

![Autocorrelation](Images/Autocorrelation.png)

![PartialAutocorrelation](Images/Partial_Autocorrelation.png)

After running ARMA with p=2 and q=1 Parameters, here the resuts and the 5-Days forecasting:

![ARMA_Results](Images/ARMA_Results.png)

![FiveDaysARMA](Images/Five_Day_Returns.png)

### Question: Based on the p-value, is the model a good fit?

### Answer: I think ARMA model is not good for this case. As seen in the results, p>|z| is always >0.05, so the model is not accurate enough!

---

## ARIMA

---

## GARCH

---

## Linear Regression

---

## Final Conclussions
