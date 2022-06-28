# the back-end of our e-commerce site running on node.js

add `"type":"module",` to `package.json` to use import method

```javascript
"name": "server",
  "type": "module",
  "version": "1.0.0",
```

add `"start": "nodemon app.js",` to `package.json` to auto run nodemon

```javascript
"scripts": {
    "start": "nodemon app.js",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
```
