# Integration of JWT in Spring Boot Application
Introduction of JWT
---
> JWT stands JSON Web Token.</br>

> JWT is responsible for securly transmiting information between parties as JSON object.

> JWT Follows digital signature,that's why it is trusted and verified.

> JWT can be signed using secret key(With the HMAC algorithm) or public / private key pair using RSA or ECDSA.

> JWT can be encrypted to provide secrecy between parties.

> When token are signed using public/private key pairs , the signature also certifies that only the party who have the private key is valid party.

Why we use Json Web Token ?
---
> When we want Authorization 
  >>  Means After sign in onces ,there is no need to send sign in credential in every request.After sign in we use JWT to perform actions like save , update ,delete.
  >> With the help of JWT we can securly transfer data from one end other end.
