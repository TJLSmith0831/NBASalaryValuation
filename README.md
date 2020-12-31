# NBASalaryValuation
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Bang for Your Buck: Analysis of NBA Salaries 2021"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Programmer: Tristan Smith"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Purpose\n",
    "Athletes in the NBA receive multi-million dollar contracts on a yearly basis. However, like in many sports, sometimes these contracts result in a lack of production and a loss of money. Other times, certain teams must make do with a limited cap due to past transgressions and current contracts. From these two situations, a valuable tool for NBA teams would be an analysis and predictive model evaluating player contracts and potential player contracts. This program has developed through Python to fill this need and it will explore current and past player contracts, assess factors that relate to these payments, and then build a machine learning models that will assign a contract value to each player's performance."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Resources"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#### Packages\n",
    "\n",
    "* Pandas\n",
    "* Numpy\n",
    "* CSV\n",
    "* Matplotlib\n",
    "* Sci-kit Learn\n",
    "\n",
    "#### Sources\n",
    "\n",
    "* NBAStats.net (www.nbastats.net)\n",
    "* Hoops Hype (www.hoopshype.com)\n",
    "* Chris Davis NBA Salaries (https://data.world/datadavis/nba-salaries)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Exploratory Graphs and Distributions"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![title](images/positionHist.png)\n",
    "![title](images/medSalaries.png)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![title](images/salGrowth2.png)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Model"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Correlation Chart"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![title](images/correlations.png)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Results"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![title](images/valuation.png)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Optimization Questions"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Question 1 - Which players have a fair-value contract?"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![title](images/fairvalued1.png)\n",
    "![title](images/fairvalued2.png)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Question 2 - Which players are overvalued? What are they worth?"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![title](images/overvalued1.png)\n",
    "![title](images/overvalued2.png)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Question 3 - Which players are undervalued? What are they worth?"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "![title](images/undervalued1.png)\n",
    "![title](images/undervalued2.png)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Comment for the first chart --> Either an error occured in the model or Josh Gray, Joe Chealey, and Cristiano Felicio should not have a contract"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}

