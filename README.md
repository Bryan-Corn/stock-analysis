# stock-analysis
VBA module for bootcamp
---
## Overview of Project

### Initial Request and Subsequent Ask
Steve asked for a way to help him evaluate stock so he can advise his parents on investing. After making him an analysis sheet that returns the total daily volume and return for several stocks for the years 2017 and 2018, the code has been refactored so that it is faster and will work with many more stocks than the 12 in the original workbook.
## Results
### Analysis of Code
To make the code more efficient, arrays were set up so nested loops aren't going through the dataset several times. The old code had a runtime of about .38 seconds for both 2017 and 2018 stock datasets:

![image](https://github.com/Bryan-Corn/stock-analysis/blob/main/Resources/VBA_Challenge_2017_Old_Code.png)

![image](https://github.com/Bryan-Corn/stock-analysis/blob/main/Resources/VBA_Challenge_2018_Old_Code.png)

The refactored code had a runtime of about .046 seconds for both sets of data, about 8 times faster:

![image](https://github.com/Bryan-Corn/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)

![image](https://github.com/Bryan-Corn/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)

## Conclusions

### General Advantages and Disadvantages of Refactoring Code

Going through your code and making changes for speed, efficiency, file size, and elegance is advantageous for obvious reasons such as making the code run faster and use less memory. What is less obvious is the fact that simplifying code and adding clear and thorough comments will save you time when you revisit the code for other uses or in further refactoring. Some future use will have a much easier time following your logic and understanding what each line in your code does. One disadvantage is the fact that your changes may break the functionality of the code or open up several 'cans of worms' revealing problems and insufficiencies that will need to be worked out.

One disadvantage of refactoring code is the time and effort it can take. Delivering a project on time with code that works but may not the best is much better than a late project with beautifule code. 

### Advantages and Disadvantages of Refactoring This Code

Specifically for the code in this project, that advantage of refactoring is the speed at which the code runs through the data. This increase in speed will allow the code to work with much larger data sets, greatly increasing its value as a tool for analysis. The original code is less advanced and easier to visualize as it loops through the data where arrays populate a table is way that is hard to mentally follow as a step-by-step process.
