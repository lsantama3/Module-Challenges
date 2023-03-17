# Module-Challenges

For this challenge I used the logic we used in the credit card example. I loop through all the rows.

I set variables for everything I needed.
Total stock volume was set to zero and price row was set to 2 so I could get the the open price for ticker.

The ticker nmes and Total SV are printed in Row I and L

Yearly_Change = the recorded open price and close price

Nested if was placed for the percent change. If open price is 0 then percent chnage is 0 so there's no error. If not then the percent formula goes through.

Yearly Change and Percent Change is recorded in their repective columns.

For the colors I did an if to check the value and based on the value it will make the row green or red. The condition is >=0.

Summary Total Row and Price Row is added by one to add the info in each row.
The Total Volume is reset to 0 to get the volume for the following ticker.
