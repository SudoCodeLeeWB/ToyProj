# ToyProj
toy proj for python backend, api, cloud server 


"""

FRONTEND HOSTING WITH DJANGO /apache does not matters whatever. 
prior to TODO:
the server must own a single webpage with front end pages. 

"""
"""
TODO TODO
metadata for program 
1. the user has own user obj class. this data is stored in DB server with mysql. 
2. when the user logs in to the webpage, the own user data is stored into it .  
3. the user has own payment method list, which is saved in user data 
4. when the user selects the payment mehtod, user enters the password to use the payment method. 
5. the payment detail datas are shown with "receipt data". 


KEYPOINTS
the user's data should be saved 
user database must be required
=> how to manage the data sheet clearly 
(sql relational diagram should be used.)

=> each part of program should be connected via api
1. the backend side for main webpage. (sends the card data when proceed button clicked)
2. the backend side for DATABASE for User's data.
3. the backend side for purchasing the card data (which actually gets the data from main webpage server and returns the result of payment) 
=> the payment side server returns the result of payment. (if the user enters the proper data for purchase) 
the database also holds the "proper data for the payment"
in the real world, it is hold by the different server, database. but in this small case, just use the same DBMS but seperate them. 

draw the diagram of the actual world(building blocks of this program)

point is to "connect each side with restful api". 
++ python backend program skills 
++ server/ cloud/ docker using skills



++it is good to add
1. the well designed algorithem for the cases. 
2. the python-alike code style
3. the authentication method, how to secretly communicate with the server 
4. real world alike authentication method.  


"""
