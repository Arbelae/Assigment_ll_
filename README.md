# Assigment_ll_
The script sets up several variables to hold data like the ticker name, open and close prices, yearly change, percent change, total stock volume, and variables to keep track of the greatest percent increase, decrease and total volume along with their corresponding tickers.

begins to loop through each worksheet in the workbook.

It sets up headers for the output table that will contain the ticker symbol, yearly change, percent change, and total stock volume. 

Looping through rows, then enters a loop where it goes through each row of the data on the current worksheet. For each row, it checks if the ticker symbol is the same as the next row. If they are different, it means the script has reached the end of the data for the current stock.

At the end of each stock's data, the script calculates the yearly change and percent change from the opening price at the beginning of the year to the closing price at the end of the year, and outputs these values to the summary table.
"Yearly Change" column based on whether the change is positive or negative. Then, it resets the total volume and the row number for the opening price for the next stock.

After going through all rows, the script then loops through the summary table to find the greatest percent increase, decrease, and total volume. It also records the ticker symbols for these stocks.

Finally, the script outputs the greatest values and their corresponding ticker symbols 
