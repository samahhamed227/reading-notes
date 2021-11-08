# Bearer Authorization


### 1- Write the following steps in the correct order:

- Receive access token
- Redirect to a third party authentication endpoint
- Register your application to get a client_id and client_secret
- Make a request to a third-party API endpoint
- Ask the client if they want to sign in via a third party
- Receive authorization code
- Make a request to the access token endpoint

#### 2- What can you do with an authorization code?
An authorization code is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space.

#### 3- What can you do with an access token?
Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user’s data.
### 4- What’s a benefit of using OAuth instead of your own basic authentication?***

- It enables apps to obtain limited access (scopes) to a user’s data without giving away a user’s password. It decouples authentication from authorization and supports multiple use cases addressing different device capabilities. It supports server-to-server apps, browser-based apps, mobile/native apps, and consoles/TVs.

-----------------------------------------------

## **JWT**

### ***What is JSON Web Token?***

- JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. 
#
## ***When should you use JSON Web Tokens?***

1. Authorization: 
2. Information Exchange:

### ***What is the JSON Web Token structure?***

1. Header
2. Payload
3. Signature


### ***Why should we use JSON Web Tokens?***

- Security-wise, SWT can only be symmetrically signed by a shared secret using the HMAC algorithm. 
## Terms 

- Client ID :

The client_id is a public identifier for apps. Is used to identify the application.
    - It must also be unique across all clients that the authorization server handles.
    -  it’s best that it isn’t guessable by third parties

- Client Secret :The client_secret is a secret known only to the application and the authorization server.
- Authentication Endpoint** Use the authentication endpoint to specify an endpoint that is called to obtain an access token which can then be used in the subsequent password update .

- Access Token Endpoint** is used by a client to obtain an ID token, access token, and refresh token.
- API Endpoint** an endpoint can include a URL of a server or service. Each endpoint is the location from which APIs can access the resources they need to carry out their function 

- Authorization Code : The EPP code, which other registrars may refer to as the Authorization or Auth code, is essentially a unique password for the domain, made up of letters, numbers, and special characters. It’s used to prove your ownership of the domain and authorize a domain transfer.

- Access Token : An access token is an object that describes the security context of a process or thread. The information in a token includes the identity and privileges of the user account associated with the process or thread. When a user logs on, the system verifies the user’s password by comparing it with information stored in a security database.
