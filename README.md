# Illinois Sales Tax Calculator
The price of goods and services changes base on where you purchase it.  The cost of living is artificial/relative. Your goal is to create a little calculator widget that will compute the total cost depending on where you buy your good/service and the amount of course.

This [tax link](https://www.taxjar.com/states/illinois-sales-tax-online/#do-you-have-sales-tax-nexus-in-illinois) has the information on various cities shipping tax rates.  Here is a short list of useful statistics from the website.
-  Illinois Tax Rate: 6.25%
-  Minimum Shipping Rate: 7.50%
-  Maximum Shipping Rate: 10.25%

## Total cost
It should be noted that the total cost of the item is found by taking the price of the item and multiplying by the sales tax.  If there is shipping, which we will assume happens in all cases, then you need to add the cost of shipping and handling multiplied by the shipping tax from its location.

## Shipping
Your shipping should be a function of two variables: the type and the location.  You should use the radio input type for the type of shipping variable and a text input for location.
-  type of shipping: standard = $2.99; priority = $4.99; express = $8.99
-  location: choose the name of the city.
## Your Program Goals
-  Make sure your widget has the correct number of input and types of input fields to grab the necessary data.
-  In the javascript, use query selectors to store the information in variables
-  Do some math with the variables to calculate the total cost
-  display the answer to your selection in the span element.
## Extra Challenge
If you get the price to display, enable a new feature which will also predict the expected date of delivery. This willl be based off of the shippingtype variable that you used in the previous example.

standard shipping will be delivered 5 days later
priority shipping will be delivered 3 days later
express shipping will be delivered 2 days later
To compelte this challenge you will need to add a new span element underneath the answer span. Follow the same process of selecting information and conditionally setting variables and updating html elements to produce the desired effect. It would probably be easiest to make additions to your code than invent a whole new function.

You will need to use the JavaScript Date Object to complete this easily. The most mathematics you will need is adding and multiplication. Read the code examples below how to get, set and update Dates!

Date.getTime()
Date.setTime()
