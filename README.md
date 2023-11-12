# Micro Front Ends Demo

This is a demonstration of micro front ends using Webpack's ModuleFederationPlugin. It showcases how to create micro front ends and share a Redux state between applications.

## Table of Contents

- [Installation](#installation) 
- [Usage](#usage) 
- [Development](#development)
- [Build](#build)
- [Contributing](#contributing) 
- [License](#license)

## Installation

Before getting started, ensure you have Node.js and npm installed.

bashCopy code

`npm run install` 

This command installs dependencies for the host, store, and nav applications.

-   `npm run install:host`: Install host application dependencies.
-   `npm run install:store`: Install store application dependencies.
-   `npm run install:nav`: Install nav application dependencies.

## Usage

To run the applications in development mode:

bashCopy code

`npm start` 

This command starts the applications in parallel.

-   `npm run start:host`: Start the host application.
-   `npm run start:store`: Start the store application.
-   `npm run start:nav`: Start the nav application.

Visit [http://localhost:3000](http://localhost:3000/) to view the micro front ends in action.

## Development

During development, you can run each application separately:

bashCopy code

`npm run start:host
npm run start:store
npm run start:nav` 

This allows you to work on individual micro front ends independently.

## Build

When ready to build for production:

bashCopy code

`npm run build` 

This command builds the applications in parallel.

-   `npm run build:host`: Build the host application.
-   `npm run build:store`: Build the store application.
-   `npm run build:nav`: Build the nav application.

The production-ready files will be generated in the respective `build` folders.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

1.  Fork the repository.
2.  Create your feature branch: `git checkout -b feature/your-feature`.
3.  Commit your changes: `git commit -am 'Add some feature'`.
4.  Push to the branch: `git push origin feature/your-feature`.
5.  Open a pull request.

## License

This project is licensed under the [MIT License](https://chat.openai.com/c/LICENSE).
