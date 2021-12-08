## Food Delivery System

For this task we are going to create a pizza ordering system using python. It will consists of various classes and various features like adding and dropping of toppings or pizzas after selection etc. Here I will given in detail the classes I would be creating and using for this pizza ordering system.

#### Key features-
1. In this we are going to deal with a chain of franchise and this code will work successfully for all of them.
2. Customer can select pizzas based on the recommendation of nearby pizza store based on zip code
3. Facility to drop the selection after making it.
4. Ability to access the employee register and add/ delete employees as per owners convinience.

##### I will create a class named PizzaOrder which contains the following methods
•	Method to Add and Remove pizza from an order
•	Method to specify the store to which order is made
•	Method which helps to apply special promotion code to the order if valid
•	Method to check the order status like order delivered, in preparation , order accepted, order not accepted, order being delivered, order completed.
•	Method to get the customer information based on the order and able to sort the order by order date and order amount.
##### Second we will create a class called Pizza which contains information regarding the pizza add ons
•	Method to add and remove toppings.
•	Method to retrieve price after add ons
•	Method to select the crust type
##### Next we will create a Class Store 
•	Method to store the list of employees where we can add remove the employees as per requirement 
•	Method to store employee address including zip code
•	Method to store phone 	number
##### Next is Employee Class
•	Stores employee first name and last name 
##### Customer class 
•	Method  to store list of first name and last name of the customer and sort and search based on their names
•	Method to store the phone number of customer 
•	Method to store the zip code of customer.
