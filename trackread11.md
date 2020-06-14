## User Modeling
- User models that have sensitive data that should NEVER be sent to client applications. If your application requires that users be able to read each others personal information, create a second Profile model to hold that data and strictly limit access to the Profile model. Safely using a second model will ensure that no users will accidentally (or maliciously) get access to sensitive information.

## Cryptography

-  methods for encoding message
- key 

## Hash Algorithms
- is stored and comapaired to the users hash 

## Cypher Algorithms
- takes a key and incrupts it
- can be decripted by that same key

## Basic Authorization
- base64 encoded
- sends username and passwrd 
- https
- atob and btoa
- "HTTP Basic authentication (BA) implementation is the simplest technique for enforcing access controls to web resources because it does not require cookies, session identifiers, or login pages; rather, HTTP Basic authentication uses standard fields in the HTTP header" - wikapedea

## JSON Web Tokens
- open web standerd
-  HMAC algorithm) or a public/private key pair using RSA or ECDSA
- Authorization
- Information Exchange
- An example payload could be:
```
{
  "sub": "1234567890",
  "name": "John Doe",
  "admin": true
}
```

- Signature: in incorder header
```
HMACSHA256(
  base64UrlEncode(header) + "." +
  base64UrlEncode(payload),
  secret)
  ```

## bycrypt
- aplication to crate hash marks

