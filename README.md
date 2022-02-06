# Modelling-Country-Life-Expectancy
STA108 Final Project, Fall 2020, Professor Christiana Drake, Kevin Xu

A term project for my Linear Regression class in which I apply multiple-linear regression techniques to obtain an accurate and precise parsimonious model that describes the relationship between life expectancy on variables: land area, population, population living in rurality, government expenditure on healthcare, percentage population with access to internet, birth rate, percentage elderly population, CO2 emissions in metric tons per capita, GDP per capita, and cell phone subscriptions per 100 people, for 187 countries.

I assess multicollinearity using VIF of candidate predictor variables. I select predictors using a step-wise procedure with a $R^2_adj criterion and a t-test P-value inspection of each predictor variable. I apply remedial transformations to my model, and I evaluate my model through an F-test of overall signfiicance, inspection of coefficient of determination, and inspection of significance of predictor variables using t-tests. 

My final selected parsimonious model is 𝑌_𝑖^3 = 𝛽0 + 𝛽𝐻𝑒𝑎𝑙𝑡ℎ𝑋𝐻𝑒𝑎𝑙𝑡ℎ,𝑖 + 𝛽𝐵𝑖𝑟𝑡ℎ𝑅𝑎𝑡𝑒𝑋𝐵𝑖𝑟𝑡ℎ𝑅𝑎𝑡𝑒,𝑖 + 𝛽𝐺𝐷𝑃𝑋𝐺𝐷𝑃,𝑖 + 𝛽𝐶𝑒𝑙𝑙𝑋𝐶𝑒𝑙𝑙,𝑖 + 𝜀𝑖.
