# Background

For this project, I created a VBA (Visual Basic) script to analyze some stock market data. 

The data is inside a Microsoft Excel workbook and includes stock data for three years (2014, 2015, and 2016). 

Each year is a different tab/sheet inside the workbook.

# About the Script

It loops through all the stocks for one year for each run and takes the following information:

-The ticker symbol.

-Yearly change from opening price at the beginning of a given year to the closing price at the end of that year.

-The percent change from opening price at the beginning of a given year to the closing price at the end of that year.

-The total stock volume of the stock.

-It applies conditional formatting by highlighting positive yearly change values in green and negative yearly change values in red.

-Finally, it return the stock with the greatest percent increase, greatest percent decrease, and greatest total volume.

