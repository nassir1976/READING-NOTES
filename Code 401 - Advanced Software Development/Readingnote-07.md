[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-07


#### Reading: Bearer Authorization
1- Write the following steps in the correct order
- Register your application to get a client_id and client_secret
- Ask the client if they want to sign in via a third party
- Redirect to a third party authentication endpoint
- Make a request to a third-party API endpoint
- Receive authorization code
- Make a request to a third-party API endpoint
- Receive authorization code
2. What can you do with an authorization code?
- For Authorization Code grant type, the first step is to issue an auth code to the client. The client will then get back with the auth code and client credentials to request for a token.
3. What can you do with an access token?
- Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user's data. Access tokens must be kept confidential in transit and in storage.
What’s a benefit of using OAuth instead of your own basic authentication?
While the OAuth password grant type is a more complex interaction than Basic authentication, the implementation of access tokens is worth it. Managing an API program without access tokens can provide you with less control, and there is zero chance of implementing an access token strategy with Basic authentication.
#### Document the following Vocabulary Terms
#### Client ID
- The id read-only property of the Client interface returns the universally unique identifier of the Client object.
#### Client Secret
- A client secret is a secret known only to your application and the authorization server. It protects your resources by only granting tokens to authorized requestors. Protect your client secrets and never include them in mobile or browser-based apps.
#### Authentication Endpoint
- Endpoint authentication is a security mechanism designed to ensure that only authorized devices can connect to a given network, site or service. The approach is also known as device authentication. ... Authenticating both the user and the device can provide two-factor authentication
#### Access Token Endpoint
- A token endpoint is an HTTP endpoint that micropub clients can use to obtain an access token given an authorization code.
#### API Endpoint
- API endpoint is the point of entry in a communication channel when two systems are interacting. It refers to touchpoints of the communication between an API and a server.
#### Authorization Code
- An authorization code is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space.
#### Access Token
- Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user’s data.

source : https://www.oauth.com/oauth2-servers/access-tokens/