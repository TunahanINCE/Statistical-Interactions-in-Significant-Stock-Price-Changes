# 📊 Statistical Interactions in Significant Stock Price Changes Among Leading Electric Vehicle Manufacturers

## 📌 Project Description

This project examines the interaction of significant changes in the stock prices of leading electric vehicle manufacturers such as **Tesla, BYD, NIO, and Rivian**. Various **time series analysis** and **machine learning** techniques are used to explore dependencies and correlations between stock price movements.

## 🛠 Technologies Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Machine Learning** (Random Forest, SARIMA)
- **Time Series Analysis** (ADF Test, Granger Causality Test, VAR Model)
- **Financial Data Analysis** (Yahoo Finance API)

## 📂 Data Set

- **Source**: Yahoo Finance API
- **Time Interval**: Last **730 days**
- **Features**:
  - Opening, closing, highest, and lowest prices
  - Trading volume
  - Daily percentage changes

## 🔍 Methodology

1. **Data Collection:** Historical stock price data for Tesla, BYD, NIO, and Rivian is collected using Yahoo Finance API.
2. **Data Preprocessing:** Handling missing values, normalizing data, and performing exploratory data analysis (EDA).
3. **Feature Engineering:** Creating relevant financial indicators and preparing datasets for model training.
4. **Statistical Analysis:** Applying **ADF Test** to check stationarity and **Granger Causality Test** to determine causality relationships.
5. **Model Training:** Implementing **SARIMA** for forecasting and **Random Forest** for pattern recognition.
6. **Results Interpretation:** Visualizing insights and evaluating the interaction among stock price changes.

## 🚀 How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/TunahanINCE/Statistical-Interactions-in-Significant-Stock-Price-Changes.git
   ```
2. **Navigate to the project folder:**
   ```bash
   cd Statistical-Interactions-in-Significant-Stock-Price-Changes
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the analysis script:**
   ```bash
   python analysis.py
   ```

## 📈 Results & Insights

- The statistical tests revealed key interactions between certain stock price movements.
- Machine learning models provided predictive insights into future price changes.
- Further refinements in feature engineering and model selection could enhance accuracy.


![image](https://github.com/user-attachments/assets/5b9366b8-8ffa-4a55-a3b7-f55cf0627744)

This analysis shows that significant increases in Tesla's share price create a spillover effect to other companies in the electric vehicle sector. However, this effect is usually small and negative. When Tesla's price increases by more than 5%, BYDDY, NIO and RIVIAN shares show small negative changes. However, the magnitude of these negative changes is less than 1% and does not imply a general collapse in the sector. It can be said that Tesla's impact on these stocks remains limited.
In the control group analysis, it was found that during the periods when Tesla's price remained stable, other stocks also showed minimal movements. This confirms that Tesla is an important actor in the sector and its price movements create pressure on other stocks.
As a result, although Tesla's price movements have a certain impact on other EV manufacturers, this impact is usually small and short-lived. It can be argued that increases in Tesla's price affect the competitive environment in the industry, pushing other stocks down. However, these effects were generally not large enough to destabilise the market.


![image](https://github.com/user-attachments/assets/38b36c73-47d6-4350-a367-e3a06f410959)

The data indicates that TSLA exerts a substantial causal influence on the percentage change in BYDDY, with a p-value of 0.040712. This indicates that Tesla's historical price fluctuations may be utilized to forecast the price trends of BYD.
Both TSLA and NIO exert substantial causal influences on the percentage change of RIVN. This suggests that the price fluctuations of RIVN may be forecasted based on the historical trends of Tesla and NIO. The p-value of BYDDY in relation to the NIO percentage change is significantly low (0.000032), suggesting that historical price fluctuations of BYDDY may affect future price trends of NIO. 


## 📬 Contact

For any questions or collaborations, feel free to reach out!\
📧 Email: [incetunahan@hotmail.com](mailto\:incetunahan@hotmail.com)\
🔗 LinkedIn: [Tunahanince](https://www.linkedin.com/in/tunahanince/)

