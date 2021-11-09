## **Access Control (ACL)**

### ***When is Basic Authorization used vs. Bearer Authorization?***

- The Basic and Digest authentication schemes are dedicated to the authentication using a username and a secret
- The Bearer authentication scheme is dedicated to the authentication using a token and is described

### What does the JSON Web Token package do?

- Defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

> Generates a token that we can use with authorization and information exchange.

### What considerations should we make when creating and storing a SECRET?

- Use encryption to store secrets within .git repositories
- Use environment variables
- Use “Secrets as a service” solutions

> don’t create a weak secret.

> don’t store it in a plain text.

> don’t share your secret with anyone.

> don’t use same secret for different accounts.

## **Terms**

- **encryption**: Encryption is a way of scrambling data so that only authorized parties can understand the information. In technical terms, it is the process of converting human-readable plaintext to incomprehensible text, also known as ciphertext. 

- **token**:  is a piece of a two-factor authentication security device that may be used to authorize the use of computer services.
it an encoded json, that we use in beare authorization to ensure if the user is authorized or not.


- **bearer**:  is a piece of a two-factor authentication security device that may be used to authorize the use of computer services.
> it an encoded json, that we use in beare authorization to ensure if the user is authorized or not.


- **secret**: the secret is a symmetric key that is known by both the sender and the receiver. 

- **JSON Web Token**: JSON Web Token (JWT) is an open standard  that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed.

## **RBAC**

### ***Role-Based Access Control `RBAC`***

- It is the idea of assigning system access to users based on their role in an organization. It's important to remember that not every employee needs a starring role.

### ***What is RBAC?***

- It's idea of assigning system access to users based on their role within an organization. 
- The system needs of a given workforce are analyzed, with users grouped into roles based on common job responsibilities and system access needs. Access is then assigned to each person based strictly on their role assignment.

### ***Benefits of RBAC?***

1.  it is much easier to audit user rights, and to correct any issues identified.
2. easy to implement

### ***RBAC vs. ABAC vs. ACL***

- Access control lists `ACL`: is a means of defining access rights by a given user or user group, to a specific object, such as a document.
- Attribute-based access control `ABAC`:sometimes known as policy-based access control, can use a variety of attributes, including user department, time of day, location of access,....


# Preview
### Which 3 things had you heard about previously and now have better clarity on?
JSON Web Token, Bearer,encryption

## Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
JWT./Bearer Authorization

## What are you most excited about trying to implement or see how it works?
more about access control
