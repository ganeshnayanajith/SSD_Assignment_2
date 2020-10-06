# SSD_Assignment_2

## Getting started

### 1. Install

clone or download the sample application. and run

```npm install```

to install all related dependencies.

### 2. Create a new app in google developer console and get client id and secret. Add callback URL as follows

```
const KEYS = {
    'googleOauth': {
        'clientID': "......",
        'clientSecret': ".....",
        'callback': '/auth/google/redirect'
    },
    "session_key": "secret123"
};

```

### 3. Run

```
npm start
```
or
```
nodemon index.js
```


