# INTRODUCTION TO API'S

API (Application Programming Interface ) is a way for decoupled applications to communicate with each other.    
A decoupled application is an application whose components are developed, tested and deployed separately.   
The decoupling can be based done on a couple of factors:
 - Backend or frontend (the frontend and backend are developed and deployed separately)
 - Modularity (the applications modules (different logical aspects of an application) are developed separately i.e for a POS system the Sales, Inventory, User and other modules are developed and deployed separately)    

The API provides a gateway for the decoupled applications to communicate. 

![API Block Diagram](/api_BD.png)   

One application will send data the other and the other will consume the data via the API and Vice Versa.    

It's important to note that there 3 most notable types of API's.    
    - REST (Representational State Transfer)      
    - SOAP (Simple Object Access Protocol)   
    - RPC (Remote Procedure Call)   
Our focus will be on REST API's which is the most widely used but just to pique your curiosity the difference between the 3 lies in their architecture specification.  

Rest is a constraint based architecture for creating web API's and whose services communicate using the HTTP (Hypertext Transfer Protocol) protocol.    
The details concerning REST are beyond the scope of this lesson and in the interest of keeping things  simple we won't delve deep into it's architecture design and constraints but you can leverage the following resources to  learn more. 

[What Is A RESTful API? -AWS ](https://aws.amazon.com/what-is/restful-api/)  
[What is a REST API?](https://www.redhat.com/en/topics/api/what-is-a-rest-api)  

The most common way of implementing REST API's is via the use of HTTP (Hypertext Transfer Protocol). HTTP has 5 methods it uses to communicate to the server which correspond to the CRUD (CREATE, READ, UPDATE, DELETE)methods.

`GET` -READ -  retrieve data from the server     
`POST` -CREATE - add data to the server  
`PUT` -UPDATE -  full update of data on the server   
`PATCH` -UPDATE -  partial update of data on the server      
`DELETE` -DELETE -  delete data from the server 

When making HTTP request we usually target resources(web content). The resource's nature could be multimedia content, database, an HTML document, a file etc. 
These resources will live at a certain location on the server also known as a URI(uniform resource identifier). 

The diagram below depicts the structure of a URI

![STRUCTURE OF A URI](./URI_structure_BD.png)   
















