# Grocery List App
![](https://file%2B.vscode-resource.vscode-cdn.net/Users/sounisaa/Desktop/Screenshot%202023-03-31%20at%205.37.28%20PM.png?version%3D1680309476791)

Grocery List App is a simple grocery list tracker app that allows you to make a grocery list, check off the items you get, edit the items if they're spelled wrong, and delete items you do not need. 

## Features

- Add items to your grocery list
- Check off items when you get them
- Edit items if they're spelled wrong
- Delete items you do not need

## Dependencies

The app uses the following dependencies:

- react: A JavaScript library for building user interfaces.
- react-dom: A package that provides DOM-specific methods for working with React.
- react-icons: A package that provides a collection of icons for React.
- cors: A package that enables cross-origin resource sharing (CORS) for APIs built with Express.
- dotenv: A package that loads environment variables from a .env file into process.env.
- express: A fast, unopinionated, minimalist web framework for Node.js.
- nodemon: A development utility that automatically restarts the Node.js server when changes are made to the codebase.
- path: A module that provides utilities for working with file and directory paths.
- pg: A PostgreSQL client for Node.js.

## Getting Started

To run the app, follow these steps:

1. Clone this repository.
2. Install dependencies with `npm install` in both the root directory and the backend directory.
3. Run the app with `npm start` in the root directory.
4. Create your own postgresSQL Database and seed the migration and seed files in the sql directory.
5. Run the back-end Express server with `npm run start` in the backend directory.

## Usage

To use the app, simply follow these steps:

1. Add items to your grocery list using the input field.
2. Check off items when you get them by clicking the checkbox next to the item.
3. Edit items if they're spelled wrong by clicking the edit button next to the item.
4. Delete items you do not need by clicking the delete button next to the item.

<!-- ## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repo
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make your changes
4. Commit your changes (`git commit -m "Add some feature"`)
5. Push to the branch (`git push origin feature/your-feature-name`)
6. Create a new pull request -->