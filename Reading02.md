# Reading Notes 02

## An introduction to NodeJS and Express

Explain middleware, answer as though I were a non-technical recruiter.
It connects 2 applications together so data and databases can be easily passed between the "pipe". Kinda like a plumber

Express the most popular node web framework.

Express is “un opinionated.” What does that mean?
You can insert almost any compatible middleware you like into the request handling chain, in almost any order you like. You can structure the app in one or multiple files, and using any directory structure.

What is a module and why is modularity useful to us as developers?
A module is a JS library/file that you can import into other code using Node's require() function. Express itself is a module, as are the middleware and database libraries that we use in our express applications. It can be messy and can be "callback hell" if we don't use a module. Module like async can make it better

## What is NPM?

What version of npm are you running on your machine?
8.19.1

What command would you type to install a library/package called ‘jshint’ into your node project?
npm install jshint

## What is TDD?

Explain why tests are important. Please explain as though I were your non technical elder.
It discovers defects or bugs before the delivery to the client , which guarantees the quality of the software. It makes the software more reliable and easy to use.

What are three expected benefits of testing
reduced defect rates
improves design qualities
reduced efforts in the projects final phases

Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
individual= forgetting to run test frequently and writing to many test at once
team= only a few developers on the team use TDD and never using or running test

## CI/CD

What are three benefits of Continuous Integration?
makes software easier. faster and less risky for developers

What is the difference between Continuos Delivery and Continuous Deployment?
Continuos Delivery = is the automation of steps to safely get changes into production
Continuous Deployment = focuses on the actual deployment 

Explain how GitHub fits into this process assuming the listener comes from a non-technical background.
