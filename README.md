# Bitcoin Forecast 

In this project, we conducted a forecast of the closing price of Bitcoin using skforecast and the LGBM regressor. To assess the accuracy of our predictions, we compared them with the actual Bitcoin prices. We follow the guide from [1]. 

During the analysis, we recognized the importance of incorporating exogenous variables to enhance the accuracy of our forecasts. Specifically, we considered the change in the reward for mining Bitcoin. Notably, the reward reduces by half after a certain number of Bitcoin blocks are mined, leading to a significant impact on the price of Bitcoin.

By taking these exogenous variables into account, we aim to refine our forecasts and achieve a more precise estimation of Bitcoin's closing price.

Created by: **PhyData Research Group**

References

[1] Bitcoin price prediction with Python, when the past does not repeat itself by Joaquín Amat Rodrigo and Javier Escobar Ortiz, available under a Attribution 4.0 International (CC BY 4.0) at https://www.cienciadedatos.net/documentos/py41-forecasting-cryptocurrency-bitcoin-machine-learning-python.html
