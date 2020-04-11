# Online-Food-
A web application for Online Food Management system using Xampp server.

How To Install -
---------

1. Create Database food.
2. Run food.sql script provided in sql folder.
3. Go to login.php and try out the application. Sample user credentials can be found in users & wallet_details table.

Note -
---------
1. The username and password of sample users are stored in table `users`.
2. Only Customers with "Verified" status can place orders using "Cash on Delivery" option.
3. By default a new customer gets 2000 coins in Wallet on signing up, and a fake Credit card number & CVV number is generated and stored in SQL Table "wallet_details" with corresponding new customer's ID.
4. Use that Card Number & CVV while placing an order, else order won't be successful or use "Cash on delivery" option.
5. What's lacking? Dynamic payment(real payment system) and error reporting lacks in this project. And also one might wish for showing corresponding food item's photo and all that stuff.
