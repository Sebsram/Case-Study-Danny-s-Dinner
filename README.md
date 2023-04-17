# Case Study: Danny's Dinner

![Dan](https://user-images.githubusercontent.com/130475600/232505947-b41b9f66-ee22-4267-a0d5-f0aea79366fc.png)


# Problem Statement:
Danny wants to use the data to answer a few simple questions about his customers, especially about their visiting patterns, how much money they’ve spent and also which menu items are their favourite. Having this deeper connection with his customers will help him deliver a better and more personalised experience for his loyal customers.

He plans on using these insights to help him decide whether he should expand the existing customer loyalty program - additionally he needs help to generate some basic datasets so his team can easily inspect the data without needing to use SQL.

Danny has provided you with a sample of his overall customer data due to privacy issues - but he hopes that these examples are enough for you to write fully functioning SQL queries to help him answer his questions!

# Entity Relationship Diagram:

![Relationships](https://user-images.githubusercontent.com/130475600/232506459-855fa265-cda8-43a3-b47c-42c090d1fd65.png)

# Tables:

Table 1: sales
The sales table captures all customer_id level purchases with an corresponding order_date and product_id information for when and what menu items were ordered.

![t1](https://user-images.githubusercontent.com/130475600/232506893-b4ce506c-2daf-4c51-b14f-578437987ab0.PNG)

Table 2: menu
The menu table maps the product_id to the actual product_name and price of each menu item.

![t2](https://user-images.githubusercontent.com/130475600/232506956-d5e48085-d0d2-4d6b-ac82-24d1967c442f.PNG)

Table 3: members
The final members table captures the join_date when a customer_id joined the beta version of the Danny’s Diner loyalty program.

![t3](https://user-images.githubusercontent.com/130475600/232507027-1e0841ea-eb6f-4925-a7ff-3a230e9792dc.PNG)

# Case Study Questions:
1. What is the total amount each customer spent at the restaurant?
2. How many days has each customer visited the restaurant?
3. What was the first item from the menu purchased by each customer?
4. What is the most purchased item on the menu and how many times was it purchased by all customers?
5. Which item was the most popular for each customer?
6. Which item was purchased first by the customer after they became a member?
7. Which item was purchased just before the customer became a member?
8. What is the total items and amount spent for each member before they became a member?
9. If each $1 spent equates to 10 points and sushi has a 2x points multiplier - how many points would each customer have?
10.In the first week after a customer joins the program (including their join date) they earn 2x points on all items, not just sushi - how many points do customer A and B have at the end of January?
