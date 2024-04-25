# Financial-Frictions-Project
Estimating and forecastig potential downside risk of the GDP growth in European Union

As for now, only preliminary research has been done. Only the data for the EU as a whole (with rate proxies for Germany as a leading economy) were implemented in the code presented in the repository.

Recently the data on 8 countries (while it is expected that the data will include all the current members of EU) has been collected from the Bloomberg Terminal, Eurostat and Fred: Belgium, Italy, Luxembourg, Germany, France, Greece, Ireland, Denmark. The data includes the target variable - Real GDP, as well as supplementary contorl variables such as GDP Deflator and Credit-to-GDP ratio. 

Next step is to determine the factors that can potentially constiture the Financial Conditions Index, which was done based on the paper of  the ECB: https://www.imf.org/en/Publications/WP/Issues/2023/09/29/Financial-Conditions-in-Europe-Dynamics-Drivers-and-Macroeconomic-Implications-539653; As for now, the following indicators have been collected for each of the 8 countries:

1. ROE of the domestic banks
2. ROA of the domestic banks
3. Net Debt-Income Ratio after Taxes
4. Gross Return on Capital Employed before Taxes
5. Net Return on Equity after Taxes
6. Household Debt-Income Ratio
7. YoY% CPI Index
8. onsumer Debt-to-Income Ratio
9. Consumer Loans for Hose Purchases, EUR, millions
10. Consumption Loans, EUR, millions
11. Government Debt, EUR, millions
12. Rates on Outstanding Loans to Non-Financial Corporations
13. Mortgage interst rates (All maturities)
14. Interest rates on consumer loans (All maturities)
15. Effective exchange rate
16. House Prices (Normalized to 2005 year)
17. Bank interest rates on deposits from households
19. Bank interest rates on deposits from corporations
20. 10-year Government nond yield
21. 2-year Govenment bond yield (not every country has one)

Next step - forecast the GDP growth using VaR model with an implemented Kalman Filter to account for the interrelations of the varaibles

