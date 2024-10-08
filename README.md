# NodeJs-Auth

-   [Overview]
-   [Project Setup](#project-setup)
-   [DataBase Modeling](#database-modeling)
-   [Postman Collection](#postman-collection)
-   [Registration Api](#registration-api)
-   [Confirmation Api](#confirmation-api)
-   [Login Api](#login-api)
-   [Self Identification Api](#self-identification-api)
-   [Logout Api](#logout-api)
-   [Refresh Token Api](#refresh-token-api)
-   [Forgot Password Api](#forgot-password-api)
-   [Reset Password Api](#reset-password-api)
-   [Change Password Api](#change-password-api)
-   [Improvements](#improvements)

## Overview

## Project Setup

### About

Clone from the Nodejs Production setup or you can setup the Production for this project

You can set up the database according to your preference. Here are a few common options

Ensure that your chosen database is installed and running. Update the database connection string in your environment configuration file (usually .env).

After setting up the database, navigate to the project directory and install the required Node.js packages:

```bash
npm install
```

You need to install the following packages for authentication, password hashing, and phone number handling:

-   jsonwebtoken
-   bcrypt
-   libphonenumber-js

#### Why We Use These Packages

-   jsonwebtoken:
    This package is used to implement JSON Web Token (JWT) authentication. JWTs are a compact and self-contained way to securely transmit information between parties as a JSON object. They are commonly used for user authentication in web applications, ensuring that only authenticated users can access protected resources.

-   bcrypt:
    bcrypt is used for hashing passwords. When a user creates an account or changes their password, bcrypt is used to securely hash the password before storing it in the database. This ensures that even if the database is compromised, the passwords are not easily readable by an attacker.

-   libphonenumber-js:
    This package is used for parsing, validating, formatting, and working with phone numbers in JavaScript. It's especially useful for projects that require handling international phone numbers with various formats and country codes. It ensures that phone numbers are stored and displayed in a consistent format, improving the user experience and data reliability.

## DataBase Modeling

### About

Data modeling is the process of designing how data will be structured and stored in the backend. It is one of the first and most important steps in backend development.

![Data Modeling Diagram](./Datamodling.png)

## Postman Collection

### About

This Postman collection is designed for testing the API according to your requirements. You can find the link to the collection below:

[Postman Collection Link](https://sasd00.postman.co/workspace/Rishabh-Personal~95659fec-f278-4cf5-8d40-f35a4eb12a89/collection/38046842-833a65e7-d9c1-4807-b6ab-a188b3f62689?action=share&creator=38046842&active-environment=38046842-d69e6bf0-e57f-41f4-8a95-09e9460ae861)

## Registration Api

## Confirmation Api

## Login Api

## Self Identification Api

## Logout Api

## Refresh Token Api

## Forgot Password Api

## Reset Password Api

## Change Password Api

## Improvements
