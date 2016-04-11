# Data-Products-Assignment

This is an interactive program which takes in 3 inputs from the user to calculate the BAC of an average male. Drinks consumed, weight, and elapsed time are inputs and are used to calculate BAC based on the Windmark algorithm. 

One drink is categorized as 12 ounces of regular beer, which is usually about 5% alcohol. 5 ounces of wine, which is typically about 12% alcohol, 1.5 ounces of distilled spirits, which is about 40% alcohol. Each drink contains roughly 14 grams of pure alcohol so that drinks consumed is multiplied by 14 to get total alcohol content consumed. Total alcohol content is displayed back to the user.

Weight is inputted in pounds and converted to grams for calculations and is displayed back to the user. The weight is then modified by 0.68, which is the gender coefficient for males. 

The total alcohol content consumed is then divided by the modified weight and multiplied by 100 to get BAC in a percentage form. This BAC is then adjusted for elapsed time. The resulting BAC value is then rendered back to the user.
