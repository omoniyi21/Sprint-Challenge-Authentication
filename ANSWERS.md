<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
-Middleware- is a layer of software that lies betwwen the operating system and the application running on the app. There are various types of middleware. We have specifically used helmet, morgan, and cors. These various form middleware provide things a connection between different databases. It is often referred to as plumbing as it connects the pipes. It is used as communication in almost all instances, but specifically in these processes security authentication, transaction management, message queues, applications servers, web servers, and directories.

-Sessions-is a place to store data that you want to access across requests. When a user goes to a website it has a unique session. This allows the application to store state. For example, based upon what the use did on page A, there will be a response showing a different page B. Sessions data can be storied in application memory, cookies, memory cache, and a database. 

-bcrypt- password hashing function 

-JWT- Json web token is an identifieer that allows for the user to access information on the database. This is secure information that can be transfered between two parties.


2.  What does bcrypt do in order to prevent attacks?

The passwords are protected by the hashing, and it would only render passwords as hashes.

3.  What are the three parts of the JSON Web Token?

-Header
-Payload
-Signature 
