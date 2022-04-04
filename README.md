# Auth0 Cruise0 application



## Project setup

Use `npm` to install the project dependencies:

```bash
npm install
```

## Configuration


### Configure credentials

The project needs to be configured with your Auth0 domain and client ID in order for the authentication flow to work.

```json
{
  "domain": "{YOUR AUTH0 DOMAIN}",
  "clientId": "{YOUR AUTH0 CLIENT ID}",
  "audience": "{YOUR AUTH0 API_IDENTIFIER}",
}
```

## Run the sample

### Compile and hot-reload for development

This compiles and serves the React app and starts the backend API server on port 3001.

```bash
npm run dev
```

