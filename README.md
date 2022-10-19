# Stock Analysis

## Overview of Project

### We are assisting Steve in the analysis of the performance of twelve Wall Street stocks in order to make informed investment recommendations to his parents. We analyzed the total daily volume and the return of the aforementioned stocks for the years 2017 and 2018. Additionally, we are helping Steve run his stock analysis in a more efficient way. To achieve this, we refactored the original script we used at the beginning of this analysis. We reduced repetition and memory space within the lines of code resulting in faster script run time. We are pleased to share our findings and investment recommendations below.

## Stock Performance and Macro Run Time Analysis

### 2017 and 2018 Stock Performance

### 2017
### As seen in the table below, the majority of stocks (11/12) performed well and had a strong dividend yield in 2017. Steve parents are interested in investing in DQ stock, which outperformed the rest of the stocks for 2017, with a dividend yield of $199.4%.  

### ![All_Stocks_2017](https://github.com/fabeza/stock-analysis/blob/245e733ccbfe6ad3d9739ae9e608a929f9c4f941/Resources/All_Stocks_2017.png)  

### 2018
### As for 2018, the table below shows the opposite, the majority of stocks (10/12) had negative returns. Only ENPH and RUN continued to perform well and DQ’s return fell to -62.6%. 

### ![All_Stocks_2018](https://github.com/fabeza/stock-analysis/blob/245e733ccbfe6ad3d9739ae9e608a929f9c4f941/Resources/All_Stocks_2018.png)

### You can find the complete data set used for this chart in the "2017” and “2018” sheets in our [VBA_Challenge](https://github.com/fabeza/stock-analysis/blob/245e733ccbfe6ad3d9739ae9e608a929f9c4f941/VBA_Challenge.xlsm) file. 

### Investment Recommendation
### Our stock of interest, DQ, had a strong performance in 2017 but did not do well in 2018. This means DQ might not be the best option for a long-term investment. Instead, Steve’s parents could consider investing in ENPH and RUN stocks as both had positive returns in two consecutive years. 

### Improving Macro Efficiency 
### The recorded run times below prove we successfully improved the macro’s efficiency by refactoring the code to reduce repetition and run time. We reduced macro run time by more than half, this improvement will help Steve analyze his current and other larger stock data sets in the future faster.  

### Original macro run time
### ![Original_run_time_2018](https://github.com/fabeza/stock-analysis/blob/245e733ccbfe6ad3d9739ae9e608a929f9c4f941/Resources/Original_run_time_2018.png)

### Refactored macro run time
### ![VBA_Challenge_2018](https://github.com/fabeza/stock-analysis/blob/245e733ccbfe6ad3d9739ae9e608a929f9c4f941/Resources/VBA_Challenge_2018.png)

## Summary

### Advantages and Disadvantages of Refactoring Code
### The major disadvantage of refactoring code is that it can be time consuming. Refactoring code requires hours of work maintaining code logic and readability, and testing and debugging. Nevertheless, refactoring code results in important advantages such as reducing memory space and repetition of certain lines of code, improving code readability and replication, and shortening script run time.

### Refactoring the Original All_Stock_Analysis VBA Script
### All the pros and cons mentioned above applied to the refactoring of the original VBA script. Refactoring this script was time consuming, a bit frustrating and repetitive. It took many hours of programming research, testing, and debugging. However, all of this hard work ultimately made the code easier to read and follow, and shortened the run time by more than half of what it originally took to get the same results (see the images below.)

### ![Original_run_time_2017](https://github.com/fabeza/stock-analysis/blob/245e733ccbfe6ad3d9739ae9e608a929f9c4f941/Resources/Original_run_time_2017.png)
### ![VBA_Challenge_2017](https://github.com/fabeza/stock-analysis/blob/245e733ccbfe6ad3d9739ae9e608a929f9c4f941/Resources/VBA_Challenge_2017.png)

### ![Original_run_time_2018](https://github.com/fabeza/stock-analysis/blob/245e733ccbfe6ad3d9739ae9e608a929f9c4f941/Resources/Original_run_time_2018.png)
### ![VBA_Challenge_2018](https://github.com/fabeza/stock-analysis/blob/245e733ccbfe6ad3d9739ae9e608a929f9c4f941/Resources/VBA_Challenge_2018.png)
