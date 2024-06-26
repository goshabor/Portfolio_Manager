# Portfolio_Manager

June 3rd, 2024:
Hello, here, one will be able to find the results of my summer project "Portfolio Manager" which will build and (passively) manage my investments in mostly stocks. This project is merely for the sake of fun and I will use the knowledge I have gained from diverse courses at NTNU such as Empirical and Quantitative Methods in Finance (TIØ4317), Optimisation 1 (TMA4180), Stochastic Modelling (TMA4265), Linear Statistical Models (TMA4267), Finance Markets (SØK2005), Macroeconomics (SØK1012), and so on. I will start on the project when I have time and will post the results here. 

June 7th, 2024:
Started on analysis of SMI (Swiss Market Index). Using weekly data from 01/01/2001 through 31/12/2019. Data from 01/01/2020 and onwards will be used to test the model. Main finding: Weekly returns of SMI are non-normal with a much higher kurtosis and a bit lower skewness than the normal distribution. Jarque-Bera fails. ACF and PACF show linear and non-linear dependencies. Further analysis is required to establish an order for a time-series model. Need to check for volatility clustering. 

June 9th, 2024:
Found an appropriate model to forecast: ARMA(1,1), and the constant term in the ARMA-model is insignificant at 5%-level. Remains to find an appropriate GARCH model. GARCH model needs to incorporate bad news as well as some macroeconomic events. Reading now Analysis of Financial Time Series (Tsay) and Quantitative Finance with Python (Chris Kelliher). 
