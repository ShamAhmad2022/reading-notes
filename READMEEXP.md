# Readings: Express, NPM, TDD, CI/CD

## An introduction to NodeJS and Express:
1.Explain middleware, answer as though I were a non-technical recruiter.

A: A middleware is something used to add additional 
functionality to the application.

2.Express the most popular __ __ ____

A: web framework

3.Express is “unopinionated.” What does that mean?

A: that means you can insert almost any compatible middleware you like into the request handling chain, in almost any order you like. 

4.What is a module and why is modularity useful to us as developers?

A: module is a JavaScript library/file that you can import into other code using Node's require() function, and it is useful because it allow us to add many things to our code, as you can also create your own modules.

## What is NPM?

1.What version of npm are you running on your machine?

A: 9.5.1

2.What command would you type to install a library/package called ‘jshint’ into your node project?

A: npm i jshint

## What is TDD?

1.Explain why tests are important. Please explain as though I were your non technical elder.

A: tests are important because in general they insure we have a reliable full-quality products.

2.What are three expected benefits of testing?

A: 
* many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort
* the same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases
* although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling

3.Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

A: 

1:
* forgetting to run tests frequently
* writing too many tests at once

2:
* poor maintenance of the test suite  
* partial adoption

## CI/CD

1.What are three benefits of Continuous Integration?

A:
* Faster iteration
* Improved transparency
* Better quality

2.What is the difference between Continuos Delivery and Continuous Deployment?

A: in Continuous delivery the team produce software in short cycles ensuring that the software can be reliably released at any time. but the Continuous deployment is an extension of continuous delivery that automatically deploys code changes to production.

3.Explain how GitHub fits into this process assuming the listener comes from a non-technical background.

A: it allow people to collaborate together and manage code changes over time