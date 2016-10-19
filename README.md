<img src=".asset/.banner.png" width="100%" />

### Tutorial 101: Client Server Scoping with API request

Hi! welcome to Tutorial 101..
in this tutorial we will learn about how to scoping / separating within client and server, then we will make simple API request from client to server.

We will use previous repositories as starter pack in this tutorial:

1. **Server side** : [Tutorial 101: Testing RESTful CRUD with Mocha Chai](https://github.com/digachandra/tutor101-restful-mocha-chai "Tutorial 101: Testing RESTful CRUD with Mocha Chai").
2. **Client side** : [Tutorial 101: Basic HTML CSS with Express JS & EJS Chai](https://github.com/digachandra/tutor101-basic-html-css-express-ejs "Tutorial 101: Basic HTML CSS with Express JS & EJS"), but we will setup without express, just HTML, CSS, JS.

#### 1. Build skeleton

```
├── client
│   ├── asset
│   │   ├── css
|   |   |   └── style.css
│   │   ├── image
|   |   |   └── favicon.png
│   │   └── js
|   |       └── core.js
|   └── index.html
└── server
    ├── config
    │   └── database.js
    ├── controllers
    │   └── fruits.js
    ├── models
    │   └── fruits.js
    ├── routes
    │   └── api.js
    ├── .gitignore
    └── index.js
```

#### 2. Init server side

Remember we need to install required modules first for the **server / api** side

```
cd server
npm install
```

#### 3. Run MongoDB

#### 4. Start server

We will use [Nodemon](http://nodemon.io/ "Nodemon website") to run server

```
nodemon index.js -w
```

#### 5. Init client side

Change directory to **client**

```
cd ../client
```

Refactoring until HTML, CSS & JS only

```
└── client
    ├── asset
    │   ├── css
    |   |   └── style.css
    │   ├── image
    |   |   └── favicon.png
    │   └── js
    |       └── core.js
    └── index.html
```

#### 6. Init index.html (client/index.html)

```

```
