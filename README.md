Created basic JavaScript application configured with OAuth and Authorization PKCE enhanced code (Configured Kyecloak server with public key)

In the HTML page, implemented JS script to first:
1) generating Random State Value
2) generating code verifier
3) generating code challenge value
4) Requesting PKCE Enhanced authorizaiton code
5) Creating Auth Code reader HTML page for the redirectURI
6) Reading authoirzation code from redirectURI
7) Validating state request parameter
8) Exchange code for Access Token (and also finding refresh token and ID Token with Inspect html page)
9) Configure CORS Access on API Gateway
10) And finally get the content of GetMapping from the resource server

