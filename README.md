# First API

## Initiliaze prjoject

- npm init -y

## watch for changes

### Node

- Add the "--watch" flag

```bash
node --watch index.js
```

### nodemon

```bash
npm install nodemon
nodemon index.js
```

### Add scripts to package.json

```json
"scripts": {
    "dev": "node --watch index.js",
    "start": "nodemon index.js"
  },
```

## Allow request

```js
res.setHeader("Access-Control-Allow-Origin", "*");
```

Allows us to send requests to the API from our frontend
