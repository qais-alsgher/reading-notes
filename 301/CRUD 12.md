# [RUD](https://github.com/qais-alsgher/reading-notes/new/main)

# In your own words, describe what each group of status code represents:

100’s =Continue
200’s =ok
300’s =Multiple Choices
400’s =Bad request 
500’s =Internal server error

# What is a status code 202?

Accepted

# What is a status code 308?

Premaent Redirect

# What code would you use if an update didn’t return data to a client?

status 204

# What code would you use if a resource used to exist but no longer does?

status 410

# What is the ‘Forbidden’ status code?

The HTTP 403 Forbidden response status code indicates that the server understands

the request but refuses to authorize it.

# Why do we need to pull our MongoDB database string out of our server and put it into our .env?

because when we deploy our application give data security

# What is middleware?

Middleware is software that provides common services and capabilities to applications outside of

what’s offered by the operating system

# What does app.use(express.json()) do?

The app.use() function adds a new middleware to the app. Essentially, whenever a request hits your backend, Express will execute the

functions you passed to app.use() in order.

express.json() the give limit option allows you to specify the size of the request body. Whether you input a string or a number, it will be interpreted as

the maximum size of the payload in bytes.


# What does the /:id mean in a route?
Route parameters are named URL segments that are used to capture the values specified at their position in the URL. The captured values are populated in the req.params object,

with the name of the route parameter specified in the path as their respective keys.

# What is the difference between PUT and PATCH?

PUT HTTP Request: PUT is a method of modifying resources where the client sends data that updates the entire resource. PUT is similar to POST in that it can create resources, but it does

so when there is a defined URL wherein PUT replaces the entire resource if it exists or creates new if it does not exist.


PATCH HTTP Request: Unlike PUT Request, PATCH does partial update e.g. Fields that need to be updated by the client, only that field is updated without modifying the other field.

# How do you make a default value in a schema?

Your schemas can define default values for certain paths. If you create a new document without that path set,

the default will kick in.

# What does a 500 error status code mean?

The client application gets an HTTP status code of 500 with the message "Internal Server Error" as a response for API calls. The 500 Internal Server error could be caused by an error

during the execution of any policy within Edge or by an error on the target/backend server.

# What is the difference between a status 200 and a status 201?

200 - OK

The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed.

201 - Created

A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page).



if you need more useful information inside my repo( [press here](https://github.com/qais-alsgher/reading-notes)).




