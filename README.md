# authentication-go

# API Authentication -

1. HTTP basic Authentication
2. API Key Authentication
3. JWT
4. OAuth


# Basic Auth - 
Sending credentials as user/password pairs
in an Authorization header field, where the credentials 
are encoded using base64.
![Basic Auth](/images/basic-auth.svg)

# API Key Authentication -
Is a unique identifier that an API provider issues
to registered users in order to control usage and monitor access. API Key should be sent in every request as part of request header, query string or as a cookie.
![API Key Authentication](/images/api-key.svg)

# JWT Authentication -
JSON Web Tokens, is a compact, stateless mechanism for API authentication. When a user logs into an application, the api server creates a digitally signed and encrypted JWT that includes the user's identity. Then the client includes JWT in every subsequent request, which the server deserializes and validates. The user's data is therefore not stored on the server's side, which improves scalablity.

![JWT Authenication](/images/jwt-auth.svg)

# OAuth Authentication -
OAuth is a token based authentication mechanism that enebales a user to grant third party access to their account without having to share their login credentials.
![OAuth Authenication](/images/oauth-diagram.svg)




