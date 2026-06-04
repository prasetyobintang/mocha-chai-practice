# API Automation Testing with Mocha, Chai, Axios

Simple API automation project using DummyJSON API.

## Tech Stack

- Mocha
- Chai
- Axios
- NYC

## Test Coverage

### Login API

- Successful login
- Login with wrong password
- Login with wrong username
- Login with empty credentials
- Verify access token

### Protected Endpoint

- Access endpoint with valid token
- Access endpoint without token
- Access endpoint with invalid token

## Installation

```bash
npm install
```

## Run Test

```bash
npm test
```

## Generate Coverage Report

```bash
npx nyc mocha
```

## API Used

https://dummyjson.com

## Project Structure

```text
.
├── test
│   └── login.test.js
├── package.json
├── package-lock.json
└── .gitignore
```

## Sample Result

```text
8 passing
```

![Mocha](https://img.shields.io/badge/Test-Mocha-brown)
![Chai](https://img.shields.io/badge/Assertion-Chai-red)
![Axios](https://img.shields.io/badge/HTTP-Axios-blue)