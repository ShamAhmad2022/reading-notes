# Bearer Authorization

It's really very important for me to know more about bearer Authentication so I can built more secured apps, and to protect the databse and the data

## Intro to JWT

1. What is a JSON Web Token (JWT)?

    A: JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.
    
2. When should we use JSON Web Tokens?

    A: we should we use JWT with Authorization and Information Exchange

3. Claims are expected in which structural component of a JWT?

    A: The Payload

## Are JWTs Secure?

1. If I get a JWT and I can decode the payload, how can we call that secure?
    
    A: having access to a token does not necessarily mean that the system or resources associated with that token are secure, and the security of the system or resources ultimately depends on the design and implementation of the token, as well as the policies and procedures surrounding its use.
    It's important to implement secure practices to use and store tokens, such as using appropriate encryption and access controls, ensuring that tokens are not stored in plain text, and regularly rotating tokens to minimize the harm in case of a breach

2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

    A: When a JWT is sent between a sender and a receiver they both must know the signing key used to create and decode the token in order for the authentication to be valid.

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

    A:  sending a package through the mail is a perfect example to simplify the process; The package has a sender's address (header), contents (payload), and a tracking number (signature). The sender securely packages the contents and attaches the tracking number before sending the package. The receiver, upon receiving the package, verifies the delivery address, checks the contents, and validates the tracking number to ensure that the package has not been tampered with.
    
## JWTs Explained

1. Why use JWT?

    A: to securely transfer information between any two bodies

2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

    A:  simply it's useful because it's faster because it's easy to sebd and handle, and it's saves behind the scene process by limiting the interactions with the database each time when using the app or the website

3. -What are the three components (the structure) of a JWT signature?

    A:  The encoded header, the encoded payload, a secret

## Reflection

1. What are your learning goals after reading and reviewing the class README?

    A:  use JWT in Authorization and to know more about the subject



