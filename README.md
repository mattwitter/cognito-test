## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Lints and fixes files
```
npm run lint
```

### AWS Setup
```
.env file ->
VUE_APP_COGNITO_REDIRECT_URI=http://localhost:8080/login/oauth2/code/cognito
VUE_APP_COGNITO_REDIRECT_URI_SIGNOUT=http://localhost:8080/logout
VUE_APP_APP_URL=http://localhost:808

.env.local file ->
VUE_APP_COGNITO_USERPOOL_ID= whatever you name the userpool in Cognito in AWS Console

VUE_APP_COGNITO_APP_DOMAIN= App Domain without Https:// App Domain listed under "Domain Name" in Cognito Left Nav Bar

VUE_APP_COGNITO_CLIENT_ID= Cognito Client ID String located at the top of the "App Client Settings" page selected from Cognito Left Nav Bar
```