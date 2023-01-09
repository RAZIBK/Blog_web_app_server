# Blog Web app

## Table of contents

- [Introduction](#introduction)
- [Run](#run)
- [Technology](#technology)
- [Features](#features)
- [License](#license)

## Introduction

It’s a complete blog application where people share their technical knowlodge and it is a stage for people to discuss about modern technologies.

NOTE: Please read the RUN section before opening an issue.


## Run

To run this application, you have to set your own environmental variables. For security reasons, some variables have been hidden from view and used as environmental variables with the help of dotenv package. Below are the variables that you need to set in order to run the application:


- MONGODB_URL: This is the Mongodb Url (string).

- JWT_KEY:  This is the Jwt key_Secret (string).

- CLOUDINARY_CLOUD_NAME: This is the Cloudinary name(string).

- CLOUDINARY_API_KEY: This is the Cloudinary api key (string).

- CLOUDINARY_SECURITY_KEY: This is the Cloudinary securty key (string).


After you've set these environmental variables in the .env file at the root of the project, and intsall node modules using  `npm install`

Now you can run `npm start` in the terminal and the application should work.

## Technology

The application is built with:

- node.js
- Express
- Mongodb

## Features

It’s a complete blog application where people share their technical knowlodge and it is a stage for people to discuss about modern technologies..

Modules can do the following:

- User authentication using JWT and password.
- Users can create and edit posts .
- Users can like and unlike posts created by other users.
- Users can comment on posts created by other users.
- Users can follow and unfollow other users.
- Users can chat with other users.
- Admin can view and manage users.
- Admin can view and manage posts.
- Admin can view and manage category.
 

## License

[![License](https://img.shields.io/:License-MIT-blue.svg?style=flat-square)](http://badges.mit-license.org)

- MIT License
- Copyright 2022 © [Muhammed Razi BK](https://github.com/RAZIBK/)
