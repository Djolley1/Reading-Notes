# Class 15

What is OAuth?

- an open-standard authorization protocol or framework that enables third-party applications to obtain limited access to a web service, either on behalf of a resource owner (like a user) or with their explicit permission, without necessarily exposing their credentials (such as a username and password).

Give an example of what using OAuth would look like.

- User Opens PhotoViewer App: They want to see their Facebook photos.

- PhotoViewer Asks Permission: The app sends them to Facebook to log in.

- User Logs in to Facebook: They see a Facebook login page, enter their credentials.

- User Grants Permission: Facebook asks if the app can access their photos. User agrees.

- Facebook Sends Access Token: Back to PhotoViewer app.

- PhotoViewer Accesses Photos: Using the token, the app fetches and shows the user's photos from Facebook.

How does OAuth work? What are the steps that it takes to authenticate the user?

- OAuth works through a series of steps, often referred to as an OAuth flow or OAuth dance.
- OAuth enables secure authorization by allowing client applications to obtain access tokens from an authorization server after the user grants permission.

What is OpenID?

- OpenID is an open standard and decentralized authentication protocol that allows users to be authenticated by cooperating sites (known as relying parties or RP) using a third-party service, eliminating the need for webmasters to provide their own ad hoc login systems and allowing users to log in to multiple unrelated websites without having to have a separate identity and password for each.

What is the difference between authorization and authentication?

- authentication verifies the identity of a user or system, while authorization determines what actions that authenticated entity is allowed to perform. Authentication establishes trust in the claimed identity, while authorization governs the access rights and privileges associated with that identity.

What is Authorization Code Flow?

- The Authorization Code Flow is one of the OAuth 2.0 flows used for obtaining access tokens to securely access resources on behalf of a user.

What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

- The Authorization Code Flow with Proof Key for Code Exchange (PKCE) is an enhanced version of the standard OAuth 2.0 Authorization Code Flow, primarily designed to address security vulnerabilities inherent in mobile and native applications.

What is Implicit Flow with Form Post?

- The Implicit Flow with Form Post is an OAuth 2.0 flow designed for client-side web applications that cannot securely store client secrets.

What is Client Credentials Flow?

- The Client Credentials Flow is an OAuth 2.0 flow primarily used for server-to-server authentication, where the client application is a confidential client and can securely store and transmit client credentials (client ID and client secret).

What is Device Authorization Flow?

- The Device Authorization Flow, also known as the Device Grant Flow or the Device Code Flow, is an OAuth 2.0 flow designed for devices with limited input capabilities, such as smart TVs, streaming media players, and Internet of Things (IoT) devices.

What is Resource Owner Password Flow?

- The Resource Owner Password Credentials (ROPC) Grant, also known as the Resource Owner Password Flow, is an OAuth 2.0 flow that allows a client application to exchange a user's username and password for an access token directly.
