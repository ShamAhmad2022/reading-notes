# Express REST API

Express and the REST API are a really important topics to know more about since I wanna be a fullstack developer, and since i specifically want to focus on working on the MERN stack.

## ES6 Classes

1. Classes are a template for creating ____.
    
    A: objects

2. Can a class declaration be hoisted?

    A: no they are not hoisted

3. How would you describe a constructor and contextual “this” to a non-technical friend?

    A: a constructor is like a template to shape the input however we want, for example if we have a chocolate vactory, and in that chocolate vactory there are chocolate machines to make the final shape from the liquid chocolate. consider the input is the liquid chocolate that we can shape as we wish (ex: we cam shape it as tablets or as spheres etc..), and we can achive that by the chocolate machines, so in this case the chocolate machines are the constructors, the liquid chocolate is the data before passing it to the constructor, and the sahped choclate is the data coming out from the constructor, and finally each choclate peice that enters the chocolate machine we can consider it 'this' at some point


## Using Express Routing

1. Within Express, what does routing refer to?
    
    A: Routing refers to how an application’s endpoints respond to client requests.

2. What is the difference between a route path and a route method?

    A: route paths: are the endpoints at which requests can be made to (URls or part of them), route methods: are the HTTP methods
3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

    A: we should only add next as a parameter when we want the next function to be excuted. If next has been passed as a parameter, then it must be called at the end 

## Express Routing

1. What is an Express Router?
    
    A: It is a mini express application 

2. By what mean do we initialize express.Router() in an express server?

    A: to keep our application modular

3. What do we use route middleware for?

    A: to do something before a request is processed

## Things I want to know more about

All the topics related to Express