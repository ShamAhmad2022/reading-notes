# Authentication

It's really very important for me to know more about ACL and RBAC in order to be able to build more secured websites

## Securing Passwords

1. Explain to a non-technical friend how you would safely hash and store a password.

    A: we can hash a password using different kinds of function and libraries, after hashing a password we then should store it in the database
    
2. What is Bcrypt?

    A: Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor

3. Why might you use something like Bcrypt?

    A: to protect the users information and accounts from steealing

## Basic Auth

1. What is Basic Authentication?
    
    A: technique for enforcing access controls to web resources because it does not require cookies, session identifiers, or login pages



2. What properties are necessary in the header of a Basic Auth request?

    A: username and password

3. How are username:password in Basic Auth encoded?

    A: encoded eith base-64
    
## OWASP auth cheatsheet

1. Define the authentication process to a non-technical recruiter.

    A: Authentication is the process of verifying the identity of a user. using the username and password. When you create an account on a website or app, you choose a username and password. When you try to log in later, you enter your username and password. The website or app then checks to see if your username and password match the ones that are stored on its servers. If they do, you’re allowed to log in.


2. How should your error messaging respond (both HTTP and HTML)? Why?

    A:  the application must respond with a generic error message regardless of whether:  The user ID or password was incorrect, The account does not exist, The account is locked or disabled.

## Additional Questions

1. Looking ahead at this module’s course schedule, What do you look forward to learning?

    A:  more techniques to secure the Database and the data


2. What are your learning goals after reading and reviewing the class README?
    
    A:  to implement everything I'll learn in my upcoming project, to make them more secure to use.