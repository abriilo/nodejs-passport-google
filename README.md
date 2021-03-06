# User Account Register and Login Using Jsonwebtoken
> simple user account registering and login app using GOOGLE-ACCOUNT and authentication using json web token.
> Nodejs App (MVC) and MongoDb

## Prerequisite:
- [x] npm latest version (node.js)

## Technologies used:
### 1. Backend
- Nodejs
- ExpressJs
- MongoDb

### 2. Frontend
- Jquery
- Mdbootstrap
- Bootstrap

## Dependency install
```
npm install --save
```
Dependencies are:
> express, bcrypt, cors, jsonwebtoken, passport, passport-google-oauth2, mongoose, cookie-parser, bootstrap, mdbootstrap, jquery, express-session, helmet

## Dev Dependency install
```
npm install --save-dev
```
Dev Dependency is:
> nodemon, dotenv

## Add .env file then write:
```
PORT=?
DATABASE_URI=?
GOOGLE_CLIENT_ID=?
GOOGLE_CLIENT_SECRET=?
GOOGLE_CALLBACK_URL=?
SECRET_ACCESS_TOKEN=?
SECRET_REFRESH_TOKEN=?
```

## To get your google information:
> go to https://console.developers.google.com/
> add project, create credential then add your api endpoints then retreive your google api informations.

## To generate tokens using CRYPTO write and run in your terminal:
```bash
node
require('crypto').randomBytes(64).toString('hex')
```

## Run Project
```
npm run devStart
```
Or
```
nodemon app.js
```

