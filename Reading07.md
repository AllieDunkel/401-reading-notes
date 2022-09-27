# Reading 07

## Intro to JWT

What is a JSON Web Token (JWT)?
is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

When should we use JSON Web Tokens?
When you need authorization that someone is them ot when you need to exchange information

Claims are expected in which structural component of a JWT?
Payload

## Are JWTs Secure?

If I get a JWT and I can decode the payload, how can we call that secure?
JWTs can be either signed, encrypted or both. If a token is signed, but not encrypted, everyone can read its contents, but when you don't know the private key, you can't change it. Otherwise, the receiver will notice that the signature won't match anymore.

If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
Shared Secret

Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
Hash(content + secret)

## JWTs Explained

Why use JWT?
It securely transfers information between to bodies and information is verified and trusted

JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
JWT is compact which means that JWT can be sent as a URL. Self contained means that JWT itself contains the information about the user, it will be faster and more and more effective the more they use it.

What are the three components (the structure) of a JWT signature?
Header- contains alg (algorithm) and typ (type of JWT Token)
Payload- claims (are user details)
Signature- or secret - provides more security
