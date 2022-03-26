# Ecart-app
Visit Ecart-app at :- http://apram-ecart.herokuapp.com/

It is a web-app built using SpringMVC, springboot and restTemplate

JSP and JSTL are used to dynamically prepare views for the application alongwith HTML and CSS.

Ecart-app is a client application in Microservices architehture that uses four REST APIs to access data from database 

Rest APIs used:-

1. AuhenticationService API:- This API provides endpoints for clients using which it can send username and password,and get response whether the username and password is valid or not on the basis of data present in database.

2. PrductCatalogService API :- It interacts with the productsDB and provide various endpoints that can be used to perform operations like adding product, deleting product and getting the products from db.

3. CartService API: It is the API which allows client to add, delete and retrieve various products to the cart, using the provided endpoints.

4. OrderService API :- Order service API provides endpoints to record the order for the items present in the cart, in the orderdb.

Application Flow :- 

The user needs to login first using the username and password, this validtion is done using AuthenticationServie API.

After login various products being sold are displayed and user can add them to cart using ADD TO CART button.

User can view the items added to the cart using VIEW CART button, and can delete the items from cart.

Afer viewing the items added in cart Place Oder button should be pressed to place the order for all the items present in the cart.

On pressing the button order is placed and amount that needs to be paid is calculated.


