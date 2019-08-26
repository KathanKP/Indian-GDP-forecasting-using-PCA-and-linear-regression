# Indian-GDP-forecasting-using-PCA-and-linear-regression

Project done as a part of the Study Oriented Project during my undergraduate studies. The goal is to forecast the Indian GDP using variables like agricultural output, lending rates, stock market indices etc. Data has been extensively collected from RBI Handbook which extensively publishes economy data at different granularity levels and can be found here (https://www.rbi.org.in/Scripts/AnnualPublications.aspx?head=Handbook%20of%20Statistics%20on%20Indian%20Economy) and the EPWRF Indian time series data which can be found here (http://www.epwrfits.in/).

Principal Component Analysis was used to reduce dimension of the feature vector by taking the top 5 most important Principal Components. OLS Linear regression was then used to forecast the Indian GDP using these 5 Principal Components as the explanatroy variables.
