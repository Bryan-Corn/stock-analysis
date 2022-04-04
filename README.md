# stock-analysis
VBA module for bootcamp
---
##Overview of Project

###Initial Request and subsequent ask
Steve asked for a way to help him evaluate stock so he can avise his parents on investing. After making him an analysis sheet that returns the total daily volume and return for several stocks for the years 2017 and 2018, the code has been refactored so that it is faster and will work with many more stocks than the 12 in the original workbook.
##Results
###Analysis of Code
To make the code more efficient, arrays were set up so nested loops aren't going through the dataset several times. The old code had a runtime of about .38 seconds for both 2017 and 2018 stock datasets. The refactored code had a runtime of about .046 seconds for both sets of data, about 8 times faster.
