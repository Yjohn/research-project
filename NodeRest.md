# **REST API**
**The word **API stands for****
    A: -Application, 
    P: - Programming 
    I: - Interface 
That allows ***one piece of software to talk to another*** and there is a lot of different kinds of API’s 
But if we talk about Tweeter API or Google API what actually talking about is a REST API. 

**WHAT IS REST**

its stands for 
    RE: - Representational 
    S: - state 
    T: - Transfer (It is sometimes spelled "ReST".)
    
As the name implies, it has to do with client and server relationship and how a state is stored. 
Rest API works pretty much the same way a website does 
You make a call from a client to a server and you get back over the HTTP protocol
A REST Server simply provides access to resources and REST client accesses and modifies the resources using HTTP protocol.

REST is an architecture style for designing networked applications. The idea is that, rather than using complex mechanisms 
such as CORBA, RPC or SOAP to connect between machines, simple HTTP is used to make calls between machines.

The rest parameter syntax allows us to represent an indefinite number of arguments as an array.

**Example**

             function f(a, b, ...theArgs) {
                   // ...
              }
              
**HTTP methods**

RESTful applications use HTTP requests to post data (create and/or update), read data (e.g., make queries), and delete data. 
Thus, REST uses HTTP for all four CRUD (Create/Read/Update/Delete) (Post, Get, Put, Delete) operations.
Following four HTTP methods are commonly used in REST based architecture.

- **GET** - This is used to provide a read only access to a resource.

- **PUT** - This is used to create a new resource.
 
- **DELETE** - This is used to remove a resource.

- **POST** - This is used to update an existing resource or create a new resource.


The concept of REST is that the client passes to the server everything that the server needs to perform the action 
And then the server does it, returns to the client with the action complete, and that’s it. It’s a process that is complete.

Despite being simple, REST is fully-featured; there's basically nothing you can do in Web Services that can't be done with a RESTful architecture.

**GET**

GET is the simplest type of HTTP request method; the one that browsers use each time you click a link or type a URL into the address bar. It instructs the server to transmit the data identified by the URL to the client. Data should never be modified on the server side as a result of a GET request. In this sense, a GET request is read-only, but of course, once the client receives the data, it is free to do any operation with it on its own side - for instance, format it for display.

**PUT**

A PUT request is used when you wish to create or update the resource identified by the URL. For example,

_PUT /clients/robin_

**DELETE**

DELETE should perform the contrary of PUT; it should be used when you want to delete the resource identified by the URL of the request.

**POST**

POST is used when the processing you wish to happen on the server should be repeated, if the POST request is repeated (that is, they are not idempotent; more on that below). In addition, POST requests should cause processing of the request body as a subordinate of the URL you are posting to.
PUT requests are used easily instead of POST requests, and vice versa. Some systems use only one, some use POST for create operations, and PUT for update operations (since with a PUT request you always supply the complete URL), some even use POST for updates and PUT for creates.
