# Secrets App V2 - Level 2 Authentication

Welcome to the Secrets - Level 2 Authentication project! This project has been upgraded to level 2 authentication, incorporating advanced security measures such as password hashing and salting for enhanced security.

## Overview

This web application allows users to register and log in securely to access "secrets". It is built using Node.js, Express.js, EJS, and PostgreSQL. With the introduction of level 2 authentication, the system ensures a higher level of security for user credentials.

## Features

- User registration: Users can sign up with their email and password.
- User login: Registered users can log in to access the secrets page.
- Advanced authentication: The system now hashes and salts passwords before storing them in the database, enhancing security.
- PostgreSQL integration: Utilizes a PostgreSQL database to store user information securely.

## Stack Used

- **Node.js**: Runtime environment for JavaScript.
- **Express.js**: Web application framework for Node.js.
- **EJS**: Templating language for generating HTML markup.
- **PostgreSQL**: Relational database management system.
- **bcrypt**: Library for hashing and salting passwords.

## Getting Started

To run this project locally, follow these steps:

1. Clone this repository to your local machine.
2. Make sure you have Node.js and PostgreSQL installed.
3. Install project dependencies by running `npm install`.
4. Set up your PostgreSQL database and update the connection details in the code.
5. Run the application using `npm start`.
6. Access the application in your web browser at `http://localhost:3000`.

## Usage

- Navigate to the homepage to register or log in.
- Upon successful login, you will be redirected to the secrets page.
- If you're not registered, sign up first to access the secrets.

## Future Improvements

This project continues to evolve, and future enhancements may include:

- Implementation of more advanced authentication methods like JWT or OAuth for added security.
- Further enhancements to password hashing and salting techniques to stay up-to-date with best practices.
- Integration of additional security measures such as rate limiting and brute force protection.
- Continuous improvement of the user interface and overall user experience.

## Contributing

Contributions are welcome! If you have any suggestions or want to contribute to this project, feel free to fork the repository and submit a pull request.
