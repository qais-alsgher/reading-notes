# APIs

# What does REST stand for?
REST is an acronym for REpresentational State

Transfer and an architectural style for distributed hypermedia systems.

Roy Fielding first presented it in 2000 in his famous dissertation.

Like other architectural styles, REST has its guiding principles and constraints.

These principles must be satisfied if a service interface needs to be referred to as RESTful.

# REST APIs are designed around resources. 

# What is an identifier of a resource? Give an example.

EST APIs are designed around resources, which are any kind of object, data, or service that 

can be accessed by the client. REST APIs use a uniform interface, which helps to decouple the client and service implementations

example, the URI for a particular customer order might be:

https://adventure-works.com/orders/1


# What are the most common HTTP verbs?

The primary or most commonly used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE.

# What should the URIs be based on?

based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP.

# Give an example of a good URI.
example.com/articles/3252
example.com/articles/how+to+design+good+uri
example.com/articles/3252/how+to+design+good+uri
example.com/good-uri-design
example.com/articles/good-uri-design
example.com/a/good-uri-design

# What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

chatty APIs are considered poor quality is because requiring multiple network calls will slow down an application.

This is because each call contains data overhead 


# What status code does a successful GET request return?

200 (OK)

# What status code does an unsuccessful GET request return?

404 (Not Found)

# What status code does a successful POST request return?

201 (Created)

# What status code does a successful DELETE request return?

204 (No Content)
 
 
