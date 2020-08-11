Using python, I calculate a week's worth of revenue made at a salon so they can plan out how to operate for the next couple of months.

I first calculate the average price of a haircut is at the salon based on the type of hairstyle in order to promote their low prices.  So I did a for loop to iterate through an array of prices for each hairstyle to determine the total price.
Then I calculate the average price using the total price number and divide it by number of different hairstyles.  The average price came out to be $31.87

Determined to lower prices after seeing the average price for a haircut, I performed another for loop to iterate through the array of current prices and subtracted each by $5 under the variable 'new prices'

Before making a change of the prices, we want to see if the salon is profitable.  So we went ahead and calculated the total revenue from last week. I used a for loop to iterate through the range of the hairstyles and multiplied it by the number of people who got the varioius haircuts under the variable 'last week'.  Right after I calculate the average daily revenue by dividing total revenue by 7(days in a week).

Lastly, to promote our haircuts under $30, I create a variable called "cuts_under_30", I iterate through the hairstyles in which the "new prices" are under $30 under the variable "cuts_under_30"



