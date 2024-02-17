# NoSQL-Social-Network-API

## Table of Contents

[Description](#description)
<br>
[Technologies Used](#technologies-used)
<br>
[Usage](#usage)
<br>
[Credits](#credits)

## Description

This application is meant to be the back end for a social network web application where users can share their thoughts, react to friends' thoughts, and create a friend list.

You can a walkthrough for this application [here](https://drive.google.com/file/d/1Idmrbq83UIlsUOvAxT_Nnk_Gt-ZgV1qJ/view)

## Technologies Used

* Node.js
* Express.js for routing
* MongoDB database
* Mongoose ORM

## Usage

* When you enter the command to invoke the application, ``` node index.js ```, the server is started and the Mongoose models are synced to the MongoDB database

* When you open API GET routes in Insomnia for users and thoughts, the data for each of these routes is displayed in a formatted JSON

* When you test API POST, PUT, and DELETE routes in Insomnia, you are able to successfully create, update, and delete users and thoughts in the database

* When you test API POST and DELETE routes in Insomnia, you are able to successfully create and delete reactions to thoughts and add and remove friends to a user's friend list


## Credits

* Application written by Conner Martin aka Conartisttt