<h1 align="center">Welcome to One Dionys - Authentication Tokens Management! 👋 </h1>

<p align="center">Functions to store, retrieve, and update authentication tokens in web applications. 💖 </p>

<p align="center">
<img src="https://img.shields.io/github/contributors/onedionys/onedionys-authentication-tokens-management?style=flat-square">
<img src="https://img.shields.io/github/issues/onedionys/onedionys-authentication-tokens-management?style=flat-square">
<img src="https://img.shields.io/github/stars/onedionys/onedionys-authentication-tokens-management?style=flat-square"> 
<img src="https://img.shields.io/github/forks/onedionys/onedionys-authentication-tokens-management?style=flat-square">
<img src="https://img.shields.io/github/last-commit/onedionys/onedionys-authentication-tokens-management.svg?style=flat-square">
<img src="https://img.shields.io/github/languages/code-size/onedionys/onedionys-authentication-tokens-management?style=flat-square">
<img src="https://img.shields.io/github/license/onedionys/onedionys-authentication-tokens-management?style=flat-square">
</p>

## 💾 Requirements

* `Web Browser` - Can be used as an emulator to build applications. Example [Chrome, Firefox, Safari & Opera].
* `Internet` - Because many use CDN and to make it easier to find solutions to all problems.

## 🎯 How To Use

#### Example Syntax

```javascript
const AuthenticationTokensManager = require('authentication-tokens-management');

const tokensManager = new AuthenticationTokensManager();

// Generate token for user
const token = tokensManager.generateToken(user);

// Verify token
const isValid = tokensManager.verifyToken(token);

// Refresh tokens
tokensManager.refreshTokens();
```

#### Explanation

* This package provides a simple implementation for managing authentication tokens in a web application. It includes methods for generating tokens, verifying token validity, and refreshing expired tokens.

#### Return Value

* `generateToken(user)`: Returns a valid authentication token for the specified user.
* `verifyToken(token)`: Returns true if the token is valid, false otherwise.
* `refreshTokens()`: Refreshes expired tokens.

## 📆 Release Date

* v1.0.0 : 08 March 2024
* v1.0.1 : 11 March 2024
* v4.0.0 : 11 March 2024
* v4.0.1 : 12 March 2024
* v4.0.2 : 18 March 2024

## 🧑 Author

* Facebook : <a href="https://www.facebook.com/theonedionys"> Oned Ionys</a>
* Instagram : <a href="https://www.instagram.com/onedionys/"> @onedionys</a>
* Twitter : <a href="https://twitter.com/onedionys"> @onedionys</a>
* LinkedIn :  <a href="https://www.linkedin.com/in/onedionys/"> @onedionys</a>

## 📝 License

* Copyright © 2024 One Dionys
* **One Dionys - Authentication Tokens Management is an open source project licensed under the MIT license**

## ☕️ Suppport & Donation

Love One Dionys - Authentication Tokens Management? Support this project by donating or sharing with others in need.

<a href="https://www.buymeacoffee.com/onedionys"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black"/> </a>

**Made with ❤️ One Dionys**
