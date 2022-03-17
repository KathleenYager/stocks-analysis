# Challenge 2 - An Analysis of Stock Volumes for Years 2017 and 2018

## Overview of the Project
Stock analysis conducted for this project provide a total volume and rate of return by ticker for  years 2017 and 2018. 

## Purpose of the Project
Beyond comparing volume and return rates by year, the analysis compares execution times by year to determine the most efficient process for processing data results. 

### Rate of Return Results by Year
Overall, rate of returns were higher for 2017 than 2018. In 2017, 11 of 12 index rates resulted in a positive rate of return compared to 2018 when 10 of 12 ticker indexes resulted in negative returns. This is an indicator that volumes by ticker volumes dropped in 2018 compared to 2017. 

### Execution Results 
Refactoring the code provided the same results for the original module and the refactored code. Time results on the refactored code for 2018 were slightly improved by a 10th of a second. Time results for the refactored code for 2017 showed it took longer to process the code by almost 5 secs. Because of the difference it takes to process the 2017 refactored code, using the original code would seem most efficient. 

Images below provide visuals of the two styles of code written. VBA_Challenge images show results for refactored code. The All_Stocks_Analysis images showcase results for the original code design. In both instances timer results are shown.  

![VBA_Challenge_2017](https://github.com/KathleenYager/stocks-analysis/blob/main/Resources/VBA_Challenge_2017.png) 

![VBA_Challenge_2018](https://github.com/KathleenYager/stocks-analysis/blob/main/Resources/VBA_Challenge_2018.png) 

![2017_All_Stocks_Analysis(ModuleExercise)](https://github.com/KathleenYager/stocks-analysis/blob/main/2017_All_Stocks_Analysis(ModuleExercise).png

![2018_All_Stocks_Analysis(ModuleExercise)](https://github.com/KathleenYager/stocks-analysis/blob/main/2018_All_Stocks_Analysis(ModuleExercise).png)

## Summary
Refactoring is often used to improve code design and/or improve run time. Refactoring this code allowed the data analyst information on the fastest run times. 

Considering the run times using the orginal code and the refactored code for the stock analysis project, it is recommended to continue using the original code to process the data, as the refactored code indicates it takes longer to run 2017 data. 
