# swiggy_delivery_pbl

Swiggy has a bold vision to elevate the quality of life of urban customers by offering and aiming at assigning the right delivery partners to the right set of orders at the right time
Here delivery partners have the option to reject an order which increases the delivery time for the customer and hence we want to avoid rejects.
Business Objective : To find the patterns which leads to rejection of order by delivery partners.
Additional Details – Every 2 mins, all non assigned orders are input to the assignment module, for each order, a set of Des are evaluated and order finally assigned to  one of the DEs. Delivery partners are allowed one reject per day beyond which they are penalized, No payout is made to DE for rejection of order and every instance of DE reject is stored in production table.
Input: Two csv files : Assignment and Delivery partners data

There is a presentation which explains the whole process to solve the problem and ipynb notebook file to view the code.
