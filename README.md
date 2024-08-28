# Predict Fertilizer Demand
<br>

- **Tools** : Google Colabs, Canva, Github <br>
- **Programming Language** : Python <br>
- **Libraries** : Pandas, NumPy, Sklearn <br>
- **Visualization** : Matplotlib, Seaborn, yellow-brick <br>
- **Dataset** : Disediakan oleh Pengecer XYZ <br>
- **Skillset** :  Analytical Thinking, Business understanding, Python Data Preprocessing, Data Visualization<br>
- **Slide** : https://www.canva.com/design/DAGJGuAoJ44/a_tEdYWHmASTr6xXyeENuQ/edit?utm_content=DAGJGuAoJ44&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton <br>

<br>
<br>

----

## 📂 **Conclusion**
The instability in fertilizer demand by farmers in Sragen and Karanganyar from January 2022 to April 2024 has caused fluctuations in supply at the Dwi Putri retailer, ranging from 3 to 5 tons. This issue arises from the retailer not predicting ZA fertilizer demand using historical sales data to determine actual values and errors. Using the ARIMA algorithm, predictions were made by testing data stationarity (order d) and identifying the model by determining the number of lags, order p, order q, and forming the ARIMA model. The model's error levels were evaluated using RMSE. Based on the nlags formula, 32.06 was obtained from 1,606 data preparations, represented in the ACF plot, resulting in order p values of 12, 24, 4, 19, and 10. In the PACF plot, order q values of 4, 12, 1, 24, and 2 were identified. Overall, ARIMA models formed from orders p, d, and q produced 25 successful models. The best model was ARIMA (10, 0, 4) with an RMSE of 0.823334. Based on this evaluation, the predicted fertilizer demand from May 2024 to July 2025 was 43,236 kg, indicating a decline. This prediction shows a 29.63% decrease in demand for 2024 period.
