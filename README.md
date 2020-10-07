# Instagram Clone.....

Instagram Clone with Realtime Functionality and Offline Support with Service Workers.

### Prerequisites
- Git
- Node
- NPM / Yarn
- React
- GraphQL

### Install 
Clone the repository

```
$ git clone https://github.com/hobbs131/instagram-clone.git
```

Install dependecies for Frontend
```
$ cd instagram-clone
$ npm install
```

Install dependencies for GraphQL server
```
$ cd instagram-clone/server
$ npm install
```

**Using Pusher**
To add realtime functionality, you need Pusher. Head over to [Pusher](https://pusher.com) and create a new application.

> Note your application keys.

- Edit your `server/server.js` and add your application credentials
- Edit the `src/App.js` and add your application keys so you can connect to pusher.


### Run the application
- Start backend server
```
$ node server
```

[Development] 
- Run Frontend
```
$ npm start
```

[Production] 
- Build Frontend
```
$ npm run build
```

- Serve static files with `http-server`
```
$ npm install http-server
$ http-server build
```

> Ensure your backend server is running simultaneously

# Demo

<img src="demo/demo.png" alt="Instagram clone">

<img src="demo/demo1.gif" alt="Realtime Posts">

<img src="demo/demo2.png" alt="Offline Mode">

## Built With
- [React](https://reactjs.org) - A Javascript library for building user interfaces
- [Express](https://expressjs.com) - Node.js web application framework
- [GraphQL](https://graphql.org) - A Query language for APIs and a runtime for fulfilling those queries with your existing data.
- [ApolloClient](https://www.apollographql.com/client) - Apollo Client is the ultra-flexible, community-driven GraphQL client for React, JavaScript, and native platforms.
- [Pusher](https://pusher.com) - Leaders in realtime technologies. We empower all developers to create live features for web and mobile apps with our simple hosted API.


