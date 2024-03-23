# Chat Application

This is a real-time chat application built with Node.js, Express, Apollo Server, GraphQL, and React.

## Technology Stack

### GraphQL

[GraphQL](https://graphql.org/) is a powerful query language for APIs and a runtime for executing those queries with your existing data. It provides a more efficient, powerful and flexible alternative to REST.

In this project, GraphQL is used for:

- **Strong Typing**: GraphQL queries return predictable results and servers can guarantee what data they are capable of providing.
- **Efficient Data Loading**: With GraphQL, clients can specify exactly what data they need, which avoids fetching more information than necessary.
- **Real-time Updates with Subscriptions**: GraphQL includes built-in support for real-time updates with its subscription system.
- **Single Request, Multiple Resources**: GraphQL queries access not just the properties of one resource but also smoothly follow references between them.

The GraphQL server in this project is built using [Apollo Server](https://www.apollographql.com/docs/apollo-server/), a community-driven, open-source GraphQL server that works with any GraphQL schema. Apollo Server is well-regarded for its performance and feature set.

On the frontend, [Apollo Client](https://www.apollographql.com/docs/react/) is used to manage both local and remote data with GraphQL. It allows you to fetch, cache, and modify application data, all while automatically updating your UI.

### Backend

- [Node.js](https://nodejs.org/): JavaScript runtime built on Chrome's V8 JavaScript engine.
- [Express](https://expressjs.com/): Fast, unopinionated, minimalist web framework for Node.js.
- [Apollo Server](https://www.apollographql.com/docs/apollo-server/): A community-driven, open-source GraphQL server.
- [GraphQL](https://graphql.org/): A query language for APIs and a runtime for executing those queries with your existing data.
- [SQLite](https://www.sqlite.org/index.html): A C library that provides a lightweight disk-based database.

### Frontend

- [React](https://reactjs.org/): A JavaScript library for building user interfaces.
- [Apollo Client](https://www.apollographql.com/docs/react/): A comprehensive state management library for JavaScript that enables you to manage both local and remote data with GraphQL.

## Getting Started

To get started with this project:

1. Clone the repository.
2. Navigate to the `server` directory and run `npm install` to install the server dependencies.
3. Run `npm start` to start the server.
4. Navigate to the `client` directory and run `npm install` to install the client dependencies.
5. Run `npm start` to start the client.

You should now be able to access the application at `http://localhost:3000`.

## Features

- User authentication.
- Real-time chat functionality.
- Ability to send and receive messages.
