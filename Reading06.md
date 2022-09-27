# Readings 06

## Securing Passwords

Explain to a non-technical friend how you would safely hash and store a password.
Hashing is the greatest way for protecting passwords and considered to be pretty safe for ensuring the integrity of data or password. The benefit of hashing is that if someone steals the database with hashed passwords, they only make off with the hashes and not the actual plaintext passwords.

What is Bcrypt?
Bcrypt (a password-hashing function) is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.

Why might you use something like Bcrypt?
allows us to build a password security platform that scales with computation power and always hashes every password with a salt.

## Basic Auth

What is Basic Authentication?
Is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request.

What properties are necessary in the header of a Basic Auth request?
a request contains a header field in the form of Authorization: Basic < credentials >, where credentials is the Base64 encoding of ID and password joined by a single colon :.

How are username:password in Basic Auth encoded?
The Basic Auth mechanism does not provide confidentiality protection for the transmitted credentials. They are merely encoded with Base64 in transit and not encrypted or hashed in any way. Therefore, basic authentication is typically used in conjunction with HTTPS to provide confidentiality.

## OWASP auth cheatsheet

Define the authentication process to a non-technical recruiter.
Authentication is the process of verifying that an individual is who they claim to be

How should your error messaging respond (both HTTP and HTML)? Why?
The application may return a different HTTP Error code depending on the authentication attempt response. It may respond with a 200 for a positive result and a 403 for a negative result. Even though a generic error page is shown to a user, the HTTP response code may differ which can leak information about whether the account is valid or not. It is important because the wrong error code can confuse the user and my it not user friendly

