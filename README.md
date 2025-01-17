# MarkitPlace-Day2--Hackathon


***PLaning Techinical Foundation Day2 Goal***

The Name of My Own Markit Place "Tech Warm"

***Front-End-(UI)***
NextJS Is the Power Full technology in Front-end More faster page Loads​
We using Some Libraries Like Tailwind CSS , ShadCN , and Responsive Design​
*Key Features About UI!*​
User Friendly Interface Browsing for All Products design Responsive Layouts  that work on  both mobile and desktop Devices ​

Essentail Pages : ​
Home , Product Listing , Product Details , Cart and Checkout, Order-Conformation 


**Sanity-(CMS) Back-End Purpose ? Why**
Sanity CMS Serves as the Back-end , providing a flexible and real time content management system​
Use Sanity To Manage The Product Data , Customer Records and Order information​
As the Primary Database for the E-Commerce Store​
Real time Updates to Reflects Stock Changes and order Processing ​
Real time Content Updates ​
Custom Schemas add On My own Choice ​



**Third Party (API)**

                                            ShipEngine :​

Tracks and Updates Shipment Details , Enables assigning tracking shipment zones​

                                          Payment Gateway:​

Processes Payments Securely, Support Cash On Delivery in Digital Plaforms Payments Like: (Stripe,EasyPaisa,JazzCash,etc)​

                           Notification Service /Order APIs:​

Use Services Like twillo or Firebase for SMS/Email notification about order Status​



**API Requirements​**
1)Product Management ​(API)​
Endpoint Name : /product​
Method : GET​
Description : Fetch all availble products for sanity ​
Response Example:​
[​
{"id":1,"name":"product1","price":1000}​
{"id":2,"name":"product2","price":2000}...​
]​

2))Order Management​ (API)​
Endpoint Name : /orders​
Method : POST​
Description : Create a New Order​
Response Example:​
{"order_id":332,"status":"Sucess","message":"​Order Created sucessfully"}​


3)Shipment Management (API)
Endpoint Name : /shipment​
Method : GET​
Description : Track The order Status  Via – A thrid Party (API)​
Response Example:​
{"shipment_id":832 ,"order_id":544 ,"status":"In Transit", ​"expected_delivery_date":"17-01-2025"}





