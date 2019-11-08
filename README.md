# teamIT
[![Build Status](https://travis-ci.com/Mastersam07/teamIT.svg?branch=develop)](https://travis-ci.com/Mastersam07/teamIT)
[![Coverage Status](https://coveralls.io/repos/github/Mastersam07/teamIT/badge.svg?branch=develop)](https://coveralls.io/github/Mastersam07/teamIT?branch=develop)
[![Maintainability](https://api.codeclimate.com/v1/badges/a99a88d28ad37a79dbf6/maintainability)](https://codeclimate.com/github/codeclimate/codeclimate/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/a99a88d28ad37a79dbf6/test_coverage)](https://codeclimate.com/github/codeclimate/codeclimate/test_coverage)

# Description
teamIT is the repo for project Teamwork. Teamwork is an internal social network for organizations’ employees. The goal of this application is to facilitate more interaction between colleagues and facilitate team bonding.

# Setup
- You need to have `git`, `NodeJS` and `nmp` installed on your local environment.
- Clone the application with `git clone` command.
- `npm install` to install all the dependencies in local environment.
- `cp .env.example .env` to have env setup
- Add values in `.env` file

# Getting Started
Starting application run the following npm scripts
* `npm run migrate` for migrating tables.
* `npm start` for starting the server.

# Testing
When you need to test the application and view test coverage run:
* `npm test` for running the tests, and getting coverage summary.

# API
* POST `/api/v1/auth/signup` Create account.
* POST `/api/v1/auth/signin` Sign in.

  **Require authentication**
  
* GET `/api/v1/feeds` Retrieve all articles posted
* GET `/api/v1/feeds/:tagId/tags` Retrieve articles by tag
* GET `/api/v1/articles/:articleId` Fetch single article by its ID
* GET `/api/v1/author/articles/:authorId` Fetch all articles by author ID
* POST `/api/v1/articles` Create new article
* POST `/api/v1/:articleId/comments` Add comment to an article
* PATCH `/api/v1/articles/:articleId` Update an article
* DELETE `/api/v1/articles/:articleId` Delete an article

# Heroku 
Access link

# Swagger API Documentation
Access link

# Github-page
GitHub page (gh-page) of this project accessed using this link [Teamwork](https://mastersam07.github.io/teamIT/UI).