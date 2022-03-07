# Stock Anaylsis

# Overview of Project
    This procejet is the steve wantsus use VBA develop tool to anaylysis different kind of stock in 2017 and 2018. 
    And do the research include data from entire stock market between this few years.

# Results
    The data was huge and in order to run more faster to get the result. Use the 'Nested' loop as inner loop to 'for' loop to achieve the array. And I created the new variable 'tickerIndex' to access the correct index across another three output arrays: 'tickerVolumes', 'tickerStartingPrices' and 'tickerEndingPrices' to loop through the entire dataset. Therefore,refactoring the code can make the VBA script run faster than the orginal script.
    
## Difference bewteen orginal and refactored script
 In the refactor, there are no addition code assign for the script. We use the same code from the Marco year value analysis.
 Please see the different show up on below: 
 
![OrginalCode](https://github.com/JoJofia/Stock-Analysis/blob/83a89df743dd3f04e62f0ef1b0b6a60ca8a997b2/Resources/Orginial_Code.png)

![Refactored Code](https://github.com/JoJofia/Stock-Analysis/blob/83a89df743dd3f04e62f0ef1b0b6a60ca8a997b2/Resources/VBA_Refactored_Code.png)

In the refactored script, the 'tickerIndex' variable assign to the output arrays and redimsion the frame of script.

### The run times for original scripts for 2017 and 2018 as below:

![2017 Originial Run Time](https://github.com/JoJofia/Stock-Analysis/blob/83a89df743dd3f04e62f0ef1b0b6a60ca8a997b2/Resources/AllstockAnalysis_2017.png)

![2018 Originial Run Time](https://github.com/JoJofia/Stock-Analysis/blob/83a89df743dd3f04e62f0ef1b0b6a60ca8a997b2/Resources/AllstockAnalysis_2018.png)

### The run times for refactored scripts for 2017 and 2018 as below:

![2017 Analysis Run Time](https://github.com/JoJofia/Stock-Analysis/blob/83a89df743dd3f04e62f0ef1b0b6a60ca8a997b2/Resources/VBA_Challege_2017_Output.png)

![2018 Analysis Run Time](https://github.com/JoJofia/Stock-Analysis/blob/83a89df743dd3f04e62f0ef1b0b6a60ca8a997b2/Resources/VBA_Challege_2018_Output.png)

Comparate the speed from the picture, we can find out the refactored code runs 0.7 ~ 0.8 fater than the original code

# Summary
In the conclusion, the refactored code more advantage than orginial code. Because it make the code more efficent and can help debug the programming code and easier to interpret the code to make it run quickly.


