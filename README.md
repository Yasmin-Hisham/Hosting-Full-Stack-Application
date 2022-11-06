# Hosting a Full-Stack Application

## Table of Contents

* [Description](#description)
* [Installation](#installation)
* [Built With](#built-with)

## Description

This udagram application is a simple application that includes all the major components of a Full-Stack web application and I deployed it to a cloud service provider so that it is available to customers.

### Installation

- Use the AWS console to start and configure the services that the application needs

- Use RDS service to run a postgres database that will store information

- Use s3 bucket service for hosting the uploaded files

- Create .env file to export the environment variables needed

- Install dependencies for udagram-api by running `npm run api:install`

- Install dependencies for udagram-frontent by running `npm run frontend:install`

### Link of the frontend app

http://myudagrambucket.s3-website.us-east-2.amazonaws.com/

### Link of the backend API

http://udagram-api-env.eba-3pccaeg5.us-east-1.elasticbeanstalk.com/

### Link of the CircleCI

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/Yasmin-Hisham/Hosting-Full-Stack-Application/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/Yasmin-Hisham/Hosting-Full-Stack-Application/tree/main)

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework