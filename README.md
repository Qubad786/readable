# Readable

Readable is a Blog. Users are able to post content to predefined categories,
they can comment on posts, vote on posts and comments. They can also edit/delete
posts and comments.

## Running the App

To run, test and develop Readable on your local computer:

# Fork, clone or download this repository

# Install and start back-end server.

   # `cd api-server`
   # `npm install`
   # `node server`

# In another terminal window, do the following to start and run the
readable app.

   # `cd frontend`
   # `npm install`
   # `npm start`

1. A browser window should open automatically, or you can load the app at
   http://localhost:3000

## Technical Implementation Details

The Readable user interface is built using [React](https://reactjs.org/) while
state management is handled by [Redux](https://redux.js.org/). Other
tools/frameworks used in the project include:

* [React Router](https://reacttraining.com/react-router/) for routing
* [Semantic UI React](https://react.semantic-ui.com/introduction) for UI
  components
* [Redux Thunk](https://github.com/gaearon/redux-thunk) for asynchronous Redux
  actions
* [uuid](https://github.com/kelektiv/node-uuid) for generating post and comment
  IDs
* [Moment.js](https://momentjs.com/) for formatting and displaying timestamps
* [Prettier](https://prettier.io/) for code formatting

## API Server

Information about the API server and how to use it can be found in its
[README file](api-server/README.md).
