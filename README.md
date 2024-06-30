# Postman-Opencart

A REST API testing project, simulating an end-user flow on an e-commerce page,   
(HTML test report inluded)  

1) where he logins, creating a session and a token (POST)  
   we test status code = 200 and  
   response message = Success: API session successfully started!
   (we save the created API token to a collection variable so we can use it for all other requests)
   
3) adds a product to the shopping cart, (POST)  
   we test status code = 200 and  
   response message = Success: You have modified your shopping cart!  
   
4) sees the contents of his cart, (GET)  
  we test status code = 200   

5) edits the quantity of the product of the cart and (POST)  
   we test status code = 200 and  
   response message = Success: You have modified your shopping cart!  
     
8) finally removes the product from the cart. (POST)  
   we test status code = 200 and  
   response message = Success: You have modified your shopping cart!  
   and we unset all saved collection variables
   
the Opencart application runs on a localhost  
