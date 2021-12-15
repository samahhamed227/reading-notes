## **API Integration**

### ***How do bearer tokens work?***

- `Bearer Token` A security token with the property that any party in possession of the token (a `bearer`) can use the token in any way that any other party in possession of it can. Using a bearer token does not require a bearer to prove possession of cryptographic key material (proof-of-possession).

### ***Describe express middleware***

- `Express middleware` are functions that execute during the lifecycle of a request to the Express server. Each middleware has access to the HTTP `request` and `response` for each route (or path) it’s attached to.
- This `chaining` of middleware allows you to compartmentalize your code and create reusable middleware.

### ***What is a JWT?***

- `JSON Web Token (JWT)` is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

-------------------------------------------------------------


## **Terms**

**role based access control**: `Role-based access control (RBAC)` restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

**http cookies**: An HTTP cookie (web cookie, browser cookie) is a small piece of data that a server sends to the user's web browser. The browser may store it and send it back with later requests to the same server. Typically, it is used to tell if two requests came from the same browser — keeping a user logged-in, for example. It remembers stateful information for the stateless HTTP protocol.

- Cookies are mainly used for three purposes:

  1. Session management
     - Logins, shopping carts, game scores, or anything else the server should remember

   2. Personalization
      - User preferences, themes, and other settings

   3. Tracking
       - Recording and analyzing user behavior

