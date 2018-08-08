# Securing Electron Apps with Auth0

This repo is part of the _Securing Electron Apps with Auth0_ blog post. 

This sample uses the [Authorization Code OAuth 2.0 grant](https://auth0.com/docs/api-auth/grant/authorization-code) to authenticate users and retrieve `access_tokens`.

To use this sample, you will need to:

1. clone this repo to your environment;
2. create a file called `env-variables.json` in the project root (copy it from `env-variables.json.template`);
3. sign in to Auth0 (i.e. you will need at least a free Auth0 account);
4. create an Auth0 API:
  - set an identifier (e.g. `https://backend-api-url.com/`);
  - activate _Allow Offline Access_;
5. set the `auth0Domain` property on `env-variables.json` to your own Auth0 domain;

Then, to start the application, make sure you install all dependencies so you can run `start`:

```bash
# install dependencies
npm i

# start the Electron app
npm start
```
