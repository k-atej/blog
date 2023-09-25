---
layout: post
title: "Reflections on Lab 6"
---
Prompt:
"Your local grocery store would like your help in creating an online grocery shopping web application. The owner of the store will be able to list items for sale, where the items have a name, price, description, quantity available, and a manufacturer. Customers will be able to go to the site and register to create an account, entering in their name, address, and phone number. Once registered, customers will be able to start an order for pickup or delivery. The customer can select from the food items the store has for sale. When an item is selected, the customer will note the quantity desired, any special instructions, and if this item can be substituted if the store is out of stock. Finally, when the customer finalizes their order, they will be able to choose a time and date for their order to be fulfilled. Finalized orders can no longer be changed by the customer."

For this assignment, I first converted the description into an ERD. I had a hard time trying to figure out the best way to represent the relationships between Items, Orders, and Customers. For whatever reason, it was helpful to finish the SQL chart and then go back to my ERD and revise it. For me, it's easier to think about the data in the tables, rather than by relationship. The only assumption I made (that I can think of at the moment) is that the substitution is made with a text box, where you can type in a comment about how to go about substitutions.

"insert ERD here"
<img id="ERD" src="_site/ERD.png">

"insert SQL chart here"
<img id="SQL" src="_site/Vertabello.png">


I am fairly satisfied with my data representation. I'm sure there are a few things in my charts that are out of wack, but they make sense to me at the moment. Particularly with the SQL chart, I feel like the tables could be broken apart more, but the variables seem to be dependent on the primary key. 

One part of this model that might be difficult to implement is the items within each order. I can see how it would easily become complicated and confusing to categorize items and order items separately. It might also be complicated to dictate available actions based on whether an order is editable or not. 