# **REST API Concept and Example**
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
