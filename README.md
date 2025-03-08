# 📊 Statistical Interactions in Significant Stock Price Changes Among Leading Electric Vehicle Manufacturers  

## 📌 Project Description  
This project analyzes the interaction of significant stock price changes among leading electric vehicle manufacturers such as **Tesla, BYD, NIO, and Rivian**.  
The study incorporates **Time Series Analysis, Machine Learning models, and Financial Data Analysis** to explore relationships between these companies' stock movements.  

## 🛠 Technologies  
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning**: Random Forest, SARIMA  
- **Time Series Analysis**: ADF Test, Granger Causality Test, VAR Model  
- **Financial Data Analysis**: Yahoo Finance API  

## 📊 Data Set  
- **Source**: Yahoo Finance API  
- **Time Interval**: Last **730 days**  
- **Features**:  
  - Opening, closing, highest, and lowest prices  
  - Trading volume  
  - Daily percentage changes  

## 📈 Methodology  
1. **Data Collection**: Fetch stock data using Yahoo Finance API  
2. **Exploratory Data Analysis (EDA)**: Visualizing stock price trends and correlations  
3. **Statistical Tests**: Applying **ADF Test** for stationarity and **Granger Causality Test** for interactions  
4. **Time Series Forecasting**: Implementing **VAR Model** and **SARIMA** for predictive analysis  
5. **Machine Learning**: Using **Random Forest** to analyze feature importance in stock movements  

## 📷 Screenshots  
![image](https://github.com/user-attachments/assets/c1073441-175d-4d24-a53a-1998ef18dd67)

This analysis shows that significant increases in Tesla's share price create a spillover effect to other companies in the electric vehicle sector. However, this effect is usually small and negative. When Tesla's price increases by more than 5%, BYDDY, NIO and RIVIAN shares show small negative changes. However, the magnitude of these negative changes is less than 1% and does not imply a general collapse in the sector. It can be said that Tesla's impact on these stocks remains limited.
In the control group analysis, it was found that during the periods when Tesla's price remained stable, other stocks also showed minimal movements. This confirms that Tesla is an important actor in the sector and its price movements create pressure on other stocks.
As a result, although Tesla's price movements have a certain impact on other EV manufacturers, this impact is usually small and short-lived. It can be argued that increases in Tesla's price affect the competitive environment in the industry, pushing other stocks down. However, these effects were generally not large enough to destabilise the market.





![image](https://github.com/user-attachments/assets/29de724c-4ab0-4c2c-9ed5-887e8fc4c678)

The data indicates that TSLA exerts a substantial causal influence on the percentage change in BYDDY, with a p-value of 0.040712. This indicates that Tesla's historical price fluctuations may be utilized to forecast the price trends of BYD.
Both TSLA and NIO exert substantial causal influences on the percentage change of RIVN. This suggests that the price fluctuations of RIVN may be forecasted based on the historical trends of Tesla and NIO. The p-value of BYDDY in relation to the NIO percentage change is significantly low (0.000032), suggesting that historical price fluctuations of BYDDY may affect future price trends of NIO. 



  

## 🚀 How to Run  
1. **Install required libraries:**  
   ```bash
   pip install -r requirements.txt
