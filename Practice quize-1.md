**Question 1**  
Background Information: You are provided below with an Excel Spreadsheet that gives one year’s daily continually compounded returns for two chemical company stocks, Dow and Dupont, and the S&P 500, a weighted index of 500 large company stocks.

Week 1 Practice Quiz Spreadsheet.xlsx
Excel Problem Type: Summing a column

Problem Information: Daily continuously compounded returns can be summed to obtain returns over longer time intervals. Sum the daily returns to calculate annual continuously compounded returns for 2010. Give each result in percent, rounded to two digits to the right of the decimal place – for example, 11.76%.

Solve:  
What is the Dow Chemical Annual return?  
* **23.23%**
* 20.51%  
* 26.15%  
* 18.65%  
(***Anwer:-  
=SUM(B3:B254) Gives you 23.23% which is Dow chemical annual returen***)  

**Question 2**  
The Excel spreadsheet provided at the beginning of this practice quiz, gives one year’s daily continually compounded returns for two chemical company stocks, Dow and Dupont, and the S&P 500, a weighted index of 500 large company stocks. Use this spreadsheet to answer the question.
Excel Problem Type: Calculating correlation for a two-column array
Question: What is the correlation between daily continuously compounded returns for Dow Chemical and for the S&P 500 Index? Round your answer two digits to the right of the decimal place - for example, .84    
* .78 
* **.79**  
* .48  
* .57
( **Answer:-  
=CORREL(B3:B254,D3:D254 Gives you ** )  

**Question 3**  
Excel Problem Type: Identifying the maximum value in a column and sorting multiple columns while preserving rows.  
Question: On what day in 2010 did Dow Chemical returns out perform S&P 500 Index returns the most?  
* February 1, 2010  
* February 9, 2010  
* **April 28, 2010**  
* October 25, 2010  
(***Answer:-  
Filter function sort data from higher data to lower for s&p 500 index***)  

**Question 4**  
Excel Problem Type: Using Excel “If” statements to determine how many days in 2010 Dow Chemical returns are higher than Dupont Returns.  
Problem Information: Assuming Dow Chemical Returns are in Column B and Dupont Returns in Column C, the “If” statements will be of the form =IF(B3>C3, 1, 0).  
Set up a column of “If” statements and then each day where Dow return > Dupont return will have a value of 1, otherwise 0.  
Question: How many days out of the 252 trading days in 2010 did Dow outperform Dupont?  
* 125  
* **124**  
* 128  
(***Answer:-  
=IF(B3>C3,1,0) then sum of that column (=IF(B3>C3,1,0)***)
* 122  

**Question 5**
Excel Problem Type: Sorting multiple columns while preserving rows  
Question: What was the fifth-worst performing day for the S&P 500 Index in 2010?  
* May 20, 2010  
* February 4, 2010  
* May 10, 2010  
* **June 29, 2010**  
(***Answer:-  
Sort the data of s&p 500 from lower to highest we get 6/29/2010***)  

**Question 6**    
Excel Problem Type: Defining the Sharpe Ratio  
Problem Information: A “Sharpe Ratio” is a way of measuring the performance of an investment asset that takes into account both returns and the standard deviation (also called the volatility) of returns over time. A stock’s Sharpe ratio is the difference between its returns and the return of a risk-free investment, such as a government bond, divided by the standard deviation of returns of the asset. For example, if a stock returns 15% per year, and the risk-free asset returns 3% per year, and the volatility of the stock is 18% per year, the Sharpe Ratio is 12%/18% = .67.  
Question: Assume a risk-free asset returns 2% per year, and the standard deviation of returns of Dupont stock is 20%. What is the Sharpe Ratio for Dupont stock for 2010? Give the answer to two digits to the right of the decimal place.  
* .84  
* **.83**  
* .88  
* .93  
(***Answer:-  
18/22=0.8181***)   


**Question 7**
Excel Problem Type: Optimization using the “Solver” plug-in  
Problem Information: Assume that at a particular gas station, the quantity of automobile fuel sold in a week is a function of the fuel’s retail price.  
The quantity of fuel sold in a week (in gallons) = (1,000 – 300x), where x is the price in dollars per gallon.  
The function f(x) for revenues from weekly sales, in dollars, will equal x*(1000 – 300x) = 1000x – 300x^2.  
Without using calculus or any other advanced math, the MS Solver plug-in can be used to find the input value for x that results in a maximum value for a function f(x). The price x is in the Solver “variable cell” and the function 1000x – 300x^2 is the Solver “objective.”  
Question: What is the price x that maximizes weekly revenues?  
* $14.50 per gallon  
* $1.45 per gallon  
* **$1.67 per gallon**  
* $16.67 per gallon    

**Question 8**   
The Excel spreadsheet provided at the beginning of this practice quiz, gives one year’s daily continually compounded returns for two chemical company stocks, Dow and Dupont, and the S&P 500, a weighted index of 500 large company stocks. Use this spreadsheet to answer the question.  
Excel Problem Type: Scatter plots and trend line options  
Solve: Generate a scatter plot that pairs the daily returns of Dow Chemical (y axis) “against” the S&P 500 returns (x axis). The slope of the regression line is also called “Beta.”  
Question: What is Beta for Dow Chemical? Give the answer rounded two digits to the right of the decimal place.   
* 1.00  
* **1.66**   
* 1.5  
* 1.62
