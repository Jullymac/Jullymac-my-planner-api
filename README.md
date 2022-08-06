<h1 style="text-align:center">
  My planner API
</h1>

<p style="text-align:center">
  <img alt="GitHub package.json version (branch)" src="https://img.shields.io/github/package-json/v/Jullymac/my-planner-api">
    <img alt='Framework: AdonisJs' src="https://img.shields.io/badge/framework-adonisjs-green">
  <a href="https://semver.org/" target="_blank">
    <img alt='Semantic Versioning' src="https://img.shields.io/badge/%20%20%F0%9F%93%A6-semantic--versioning-e10079.svg">
  </a>
</p>

## Table of content

- [Table of content](#table-of-content)
- [Project board](#project-board)
- [Installation](#installation)
- [Configuration](#configuration)
- [Start](#start)
- [Libraries and frameworks](#libraries-and-frameworks)

## Project board

You can check the progress of the project on the board in [Trello](https://trello.com/b/TX2UdinO/my-planner).

## Installation

To install the application, you'll need **Git** and **Node.js >= v14**. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/Jullymac/my-planner-api.git

# Go into the repository
$ cd my-planner-api

# Install dependencies
$ npm install
```

## Configuration

Copy `.env.example` file to `.env` and fill up all environment variables, preferably with a postgres database.

## Start

You can start the application locally with the following command:

```bash
$ node ace serve --watch
```

It will run at http://localhost:3333

## Libraries and frameworks

The main libraries and frameworks used in this project are:

- [AdonisJs](https://adonisjs.com) - v5.8.1
- [Prettier](https://prettier.io) - v2.7.1
- [EsLint](https://eslint.org) - v8.21.0
