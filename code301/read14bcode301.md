# Readings: Authentication

## [What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

1. **What is OAuth?**  
"OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization."

2. **Give an example of what using OAuth would look like.**  
A simple and common example is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon.

 3.**How does OAuth work? What are the steps that it takes to authenticate the user?**

1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.

2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.

3. The first site gives this token and secret to the initiating user’s client software.

4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).

5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.

6. The user approves (or their software silently approves) a particular transaction type at the first website.

7. The user is given an approved access token (notice it’s no longer a request token).

8. The user gives the approved access token to the first website.

9. The first website gives the access token to the second website as proof of authentication on behalf of the user.

10. The second website lets the first website access their site on behalf of the user.

11. The user sees a successfully completed transaction occurring.

12. OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. 
 succeeded with adoption rates where previous attempts failed (for various reasons).


4. **What is OpenID?**  
 OpenID would serve as a single sign-in, that allows the user to sign in multiple websites using the same account, ex: *sign up in instgram via facebook directly*.

-The answer are exact same for the article-


## Authorization and Authentication flows
1. **What is the difference between authorization and authentication?**

|Authentication	|Authorization|
|----|-----|
| Determines whether users are who they claim to be |  Determines what users can and cannot access  |
| Challenges the user to validate credentials (for example, through passwords, answers to security questions, or facial recognition) |  Verifies whether access is allowed through policies and rules  |
| Usually done before authorization |  Generally, transmits info through an Access Token  |
| Generally governed by the OpenID Connect (OIDC) protocol |  Generally governed by the OAuth 2.0 framework  |
| Example: Employees in a company are required to authenticate through the network before accessing their company email |  Example: After an employee successfully authenticates, the system determines what information the employees are allowed to access  |

2. **What is Authorization Code Flow?**  
The Authorization Code Flow, exchanges an Authorization Code for a token.
as a source code is not exposed ->
- when user request the user's authorization it redirect the request back with an authorization code(Exchange authorization code for tokens) to website.
- Call API: Use the retrieved Access Token to call your API.
- Refresh tokens: Use a Refresh Token to request new tokens when the existing ones expire.

3.  ***What is Authorization Code Flow with Proof Key for Code Exchange `PKCE`?***

- The Authorization Code Flow `PKCE` is an `OpenId` Connect flow specifically designed to authenticate native or mobile application users.


4. **What is Implicit Flow with Form Post?**  

As an alternative to the Authorization Code Flow, OAuth 2.0 provides the Implicit Flow, which is intended for Public Clients, or applications which are unable to securely store Client Secrets. 
While this is no longer considered a best practice for requesting Access Tokens, when used with Form Post response mode, it does offer a streamlined workflow if the application needs only an ID token to perform user authentication.


5. ***What is Client Credentials Flow?***

- The `Client Credentials flow` is a server to server flow. There is no user authentication involved in the process. 
 
 6. **What is Device Authorization Flow?**  
The device asks the user to go to a link on their computer or smartphone and authorize the device. 

7. **What is Resource Owner Password Flow ?**

__* highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials (username and password), typically using an interactive form. The Resource Owner Password Flow should only be used when redirect-based flows cannot be used.*