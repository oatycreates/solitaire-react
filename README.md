# solitaire-react
Learning React + Rails development through creating a simple Solitaire browser game.

## Running the project
Foreman is used to synchronise the execution of the Rails and React Webpack servers.

Execute this command from the base project directory to start the React Webpack server on port 3000 and the Rails server on port 3001:

`foreman start -f Procfile.dev -p 3000`

## References & Acknowledgements
The React component of this project was created using a base of Facebook's [create-react-app](https://github.com/facebookincubator/create-react-app).

The Rails <=> React interop was build with reference to the [fullstackreact.com](https://www.fullstackreact.com) article titled [How to get "create-react-app" to work with your Rails API](https://www.fullstackreact.com/articles/how-to-get-create-react-app-to-work-with-your-rails-api/).
