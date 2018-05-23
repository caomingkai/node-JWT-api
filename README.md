## node-JWT-api

[https://scotch.io/tutorials/authenticate-a-node-js-api-with-json-web-tokens#what-well-be-building](https://scotch.io/tutorials/authenticate-a-node-js-api-with-json-web-tokens#what-well-be-building)

1. Build a quick API using Node and Express
2. Use POSTman to test it

## Workflow

1. Have unprotected and protected routes
2. A user will authenticate by passing in a name and a password and get back a token
3. The user will store this token on their client-side and send it for every request
4. We will validate this token, and if all is good, pass back information in JSON format
5. Our API will be built with:
    + normal routes (not authenticated)
    + route middleware to authenticate the token
    + route to authenticate a user and password and get a token
    + authenticated routes to get all users
