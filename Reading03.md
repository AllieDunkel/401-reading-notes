# Readings

## Review: ES6 Classes

Classes are a template for creating objects

Can a class declaration be hoisted?
Class expressions must be declared before they can be used

How would you describe a constructor and contextual “this” to a non-technical friend?
If there is a constructor present in the subclass, it needs to first call super() before using "this".

## Using Express Routing

Within Express, what does routing refer to?
Routing refers to how an application’s endpoints (URIs) respond to client requests.

What is the difference between a route path and a route method?
Route paths, in combination with a request method, define the endpoints at which requests can be made and A route method is derived from one of the HTTP methods, and is attached to an instance of the express class.

When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
 it is important to provide next as an argument to the callback function and then call next() within the body of the function to hand off control to the next callback.

## Express Routing

What is an Express Router?
 It is a mini express application without all the bells and whistles of an express application, just the routing stuff.

By what mean do we initialize express.Router() in an express server?
We will call an instance of the express.Router(), apply routes to it, and then tell our application to use those routes. We can now access the home page

What do we use route middleware for?
to log requests to the console