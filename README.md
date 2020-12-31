# NBASalaryValuation
# Bang for Your Buck: Analysis of NBA Salaries 2021
Programmer: Tristan Smith

## Purpose
Athletes in the NBA receive multi-million dollar contracts on a yearly basis. However, like in many sports, sometimes these contracts result in a lack of production and a loss of money. Other times, certain teams must make do with a limited cap due to past transgressions and current contracts. From these two situations, a valuable tool for NBA teams would be an analysis and predictive model evaluating player contracts and potential player contracts. This program has developed through Python to fill this need and it will explore current and past player contracts, assess factors that relate to these payments, and then build a machine learning models that will assign a contract value to each player's performance.

## Resources
#### Packages

* Pandas
* Numpy
* CSV
* Matplotlib
* Sci-kit Learn

#### Sources

* NBAStats.net (www.nbastats.net)
* Hoops Hype (www.hoopshype.com)
* Chris Davis NBA Salaries (https://data.world/datadavis/nba-salaries)

## Exploratory Graphs and Distributions
![Positional Histogram](nbaSalaries/images/positionHist.png)
![Median Position Salary](nbaSalaries/images/medSalaries.png)
![Median Salary Growth](nbaSalaries/images/salGrowth2.png)

## Model
### Correlations
![Correlations](nbaSalaries/images/correlations.png)

### Results
![Results](nbaSalaries/images/valuation.png)

## Optimization Questions
### Question 1 - Which players have a fair-value contract?
![Fair1](nbaSalaries/images/fairvalued1.png)
![Fair2](nbaSalaries/images/fairvalued2.png)

## Question 2 - Which players are overpaid?
![Over1](nbaSalaries/images/overvalued1.png)
![Over2](nbaSalaries/images/overvalued2.png)

### Question 3 - Which players are undervalued? What are they worth?
![Under1](nbaSalaries/images/undervalued1.png)
![Under2](nbaSalaries/images/undervalued2.png)





