# Taskk
# Tillo Technical Test
## PHP Task 1 - Answers in plain English![Screen Shot 2023-05-26 at 7 16 47 PM](https://github.com/Vikydaniella/Taskk/assets/122536315/d5fb3062-2361-4c11-8969-ac72419a3f81)



> :information_source: Edit this Markdown file and in plain English, briefly describe how you would:

1. Count the total number of orders?

> Answer: Since the data type of the order.json is a list of objects, so I will loop through to know the total number. 

2. Count the number of orders that were FREE?

> Answer: While going through each of the orders using a loop, I would check where the price property equals zero, then I will sum them up. 

3. Count the number of orders that were placed in GBP?

> Answer: While going through each of the orders using a loop, I would check where the currency property is GBP, then I will sum them up. 

4. Count the number of orders that were shipped to Essex?

> Answer: While going through each of the orders using a loop, I would check where the "county" property equals to Essex inside the shipping_address object which is inside the Customer object which is also inside the orders object.

5. Sum the cost of orders that were placed in GBP and were £100 or more?

> Answer: I will create a variable to hold the total sum, while going through each of the order using a loop, I would check where the currency property is GBP and where price is greater than or equals to 100, then I will add each of the price values that meets the necessary conditions using the variable.

6. Sum the cost of orders that were placed in GBP?

> Answer: I will create a variable to hold the total sum, while going through each of the orders using a loop, I would check where the currency property is GBP then I will add each of the price values that meets the necessary conditions using the variable.

7. Sum the cost of orders that were placed in GBP and were shipped to Essex?

> Answer: I will create a variable to hold the total sum, while going through each of the orders using a loop, I would check where the currency property is GBP and were shipped to Essex, then I will add each of the price values that meets the necessary conditions using the variable.
