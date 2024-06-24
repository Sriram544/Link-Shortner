```markdown
# Link Shortener

A simple URL shortener application built with Node.js, Express, and MongoDB.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This URL shortener application allows you to input a long URL and get a shortened version. The shortened URL can then be used to redirect to the original URL.

## Features

- Shorten a long URL
- Redirect from the shortened URL to the original URL
- Simple and clean user interface

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/Sriram544/Link-Shortner.git
    ```

2. Change into the project directory:

    ```sh
    cd url-shortener
    ```

3. Install the dependencies:

    ```sh
    npm install
    ```

4. Start the server:

    ```sh
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000`.

## Usage

1. Enter a long URL into the input field and click "Shorten".
2. The shortened URL will be displayed. You can click on it to be redirected to the original URL.

## Folder Structure

```
project-directory/
│
├── models/
│   └── urlSchema.js
├── public/
│   └── style.css
├── routes/
│   └── urlRout.js
├── views/
│   └── index.ejs
├── package-lock.json
├── package.json
└── server.js
```

- **models/urlSchema.js**: Mongoose schema for URLs.
- **public/style.css**: CSS file for styling the application.
- **routes/urlRout.js**: Express routes for handling URL shortening and redirection.
- **views/index.ejs**: EJS template for the main page.
- **server.js**: Main server file to set up and run the Express application.
- **package.json**: File to manage project dependencies and scripts.
- **package-lock.json**: Auto-generated file to lock the versions of dependencies.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements, bug fixes, or new features.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/fooBar`).
3. Commit your changes (`git commit -m 'Add some fooBar'`).
4. Push to the branch (`git push origin feature/fooBar`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
```
