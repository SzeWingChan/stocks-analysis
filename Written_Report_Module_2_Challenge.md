# VBA of Wall Street

## Overview of Project
### Purpose
-   The purpose of the analysis is to compare stock performance in 2017 and 2018. By employing a marco, the entire dataset of different years could be analyzed in mere seconds.  And by refactoring the code, the script will become more efficient.

## Results
-   Stock performance in 2017 and 2018
    -   The prices of the majority of the stocks, except for TERP, increased in 2017.  The percentage increase ranged from the lowest 5.5% to the highest of 199.4%.

    -   In 2018, on the contrary, most of the stock prices dropped with the exception for ENPH and RUN.  DQ had the highest drop of 62.6%.

    - 	Based on the data of 2017 and 2018, ENPH and RUN outperformed the other stocks and ENPH would be a great investment choice.

-   Execution times of the original script and the refactored script
    -   The original script (see below) took around 1.30 and 1.27 seconds (rounded to the nearest hundredth), respectively, to generate the analysis for 2017 and 2018, respectively.  
        ![VBA_Challenge_2017_Original](https://github.com/SzeWingChan/stocks-analysis/blob/main/Resources/VBA_Challenge_2017_Original.png)
        ![VBA_Challenge_2018_Original](https://github.com/SzeWingChan/stocks-analysis/blob/main/Resources/VBA_Challenge_2018_Original.png)
    -   The refactored script took only 0.16 seconds (rounded to the nearest hundredth) to generate an analysis of 2017 and 2018, respectively, which is significantly faster than the original script.
        ![VBA_Challenge_2017](https://github.com/SzeWingChan/stocks-analysis/blob/main/Resources/VBA_Challenge_2017.png)
        ![VBA_Challenge_2018](https://github.com/SzeWingChan/stocks-analysis/blob/main/Resources/VBA_Challenge_2018.png)
        
## Summary

-   Advantages or of refactoring code
    -   By refactoring the VBA script, the code became more efficient and it took less steps to execute the code.

    -   Another advantage of refactoring is prompting data analysts to review the flow and logic of the code (e.g. conditions and for loops) and ensure everything is written appropriately.

-   Disadvantages or of refactoring code
    -   Refactoring the code takes time, especially if the code is written by another analyst, and a good understanding of the original code is required.

    -	The benefits of refactoring the code might be minimal as the functionality remains the same.  The beneifts will be more prominet for bigger or more complicated dataset.

- How do these pros and cons apply to refactoring the original VBA script?
    -   Instead of having to loop 12 times to collect the total volume and stock performance for each stock, the refactored code only loops through the data once.  The execution time of the script is significantly reduced by around 87%.

    -   The execution time has been significantly reduced in this analysis.  However, the real impact is close to zero as the original script took less than 1.5 seconds to run in the first place.  The benefit is being outweighed as the time taken to refactor the script is longer than the time saved.