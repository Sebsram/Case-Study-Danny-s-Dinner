# Case Study - Danny's Dinner. 
**1. What is the total amount each customer spent at the restaurant?**

![a1](https://user-images.githubusercontent.com/130475600/232515065-52996013-e017-4819-ae3d-ed0b24dd24b6.PNG)

| customer_id | total |
| ----------- | ----- |
| A           | 76    |
| B           | 74    |
| C           | 36    |


**2. How many days has each customer visited the restaurant?**

![a2](https://user-images.githubusercontent.com/130475600/232522776-0fb3e5f2-a255-496c-8b2c-62329e9bf1c4.PNG)


| customer_id | total_visits |
| ----------- | ----- |
| A           | 4    |
| B           | 6    |
| C           | 2   |

**3. What was the first item from the menu purchased by each customer?**

![a3](https://user-images.githubusercontent.com/130475600/232528286-5ada29cc-0291-48f6-ad60-c104a7d129a9.PNG)

We used the RANK() function to assign a rank to each row based on the order_date column allowing us to see which one was purchase first by each customer. 

| customer_id | product_name |
| ----------- | ------------ |
| A           | curry        |
| A           | sushi        |
| B           | curry        |
| C           | ramen        |

**4. What is the most purchased item on the menu and how many times was it purchased by all customers?**

![a4](https://user-images.githubusercontent.com/130475600/232539364-d660a950-94b5-4681-9847-a1534b3e9f58.PNG)

| product_name | most_purchased |
| ------------ | -------------- |
| ramen        | 8              |
| curry        | 4              |
| sushi        | 3              |

**5. Which item was the most popular for each customer?**

![a5](https://user-images.githubusercontent.com/130475600/232545380-593781cb-5984-4c0a-81cd-97a366cc9fa3.PNG)

| customer_id | product_name | total_orders |
| ----------- | ------------ | ------------ |
| A           | ramen        | 3            |
| B           | ramen        | 2            |
| B           | curry        | 2            |
| B           | sushi        | 2            |
| C           | ramen        | 3            |

**6. Which item was purchased first by the customer after they became a member?**

![a6](https://user-images.githubusercontent.com/130475600/232549744-017de31c-eba9-463a-b06c-35cb8d422865.PNG)

| customer_id | order_date               | product_name |
| ----------- | ------------------------ | ------------ |
| B           | 2021-01-11T00:00:00.000Z | sushi        |
| A           | 2021-01-07T00:00:00.000Z | curry        |


