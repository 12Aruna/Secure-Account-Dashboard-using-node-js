<h1 align="center">
    <b>User Registration & Login systems in<br> Node.js using MongoDB </b> 
<br>
</h1>


<p align="center">
  <a href="/LICENSE"><img src="https://img.shields.io/github/license/guruhariharaun/Registration-and-Login-Form-in-Nodejs-and-MongoDB.svg?style=flat-square"></a>
</p>


## What is this for?
This is a Simple User Registration & Login systems app done with Node.js Framework using MongoDB(Atlas) as the data store, Express as the routing system, Body-parser as the parser for webpage, Express-session used  to track the user's session and of course Mongoose to make interacting with Mongo from Node easy.

## Getting Started

### Deployment
This Project is **[Live](https://reg-login-using-nodejs-mongodb.herokuapp.com/)** on: 🌍 **https://reg-login-using-nodejs-mongodb.herokuapp.com/**

## Running the tests

### •Registration Form:
Allows the user to register their account by filling their Email, Username, Password.

![registration](https://github.com/12Aruna/Secure-Account-Dashboard-using-node-js/assets/122152267/1f301473-3f2d-4620-ad62-e9250bc1d0a3)



### •Login Form:
If the user has been registered on the app, can login by passing the credentials.

![login](https://github.com/12Aruna/Secure-Account-Dashboard-using-node-js/assets/122152267/4b3c45b6-9044-43a3-82d8-c61cdb2b5c58)


### •User's Profile:
After the user logged in, a simple profile with the user's username and password <br>displayed with a session Logout button.

![data](https://github.com/12Aruna/Secure-Account-Dashboard-using-node-js/assets/122152267/1d37984c-049b-479c-9616-32479de4f972)


### •Password Reset:
If the user forget his/her password, can reset by entering the registered Email id <br>and reset the password.

![forgetpass](https://github.com/12Aruna/Secure-Account-Dashboard-using-node-js/assets/122152267/b99ce7f2-fc90-4bf1-a720-42526ff354b1)


### DataBase:
Here we use **[MongoDB Atlas(Cloud)](https://www.mongodb.com/cloud/atlas)** as the database. Here we have two collection created, named as:
- users.
- sessions.

A Collection(**Users**) is populated with the user's credentials.

![userdb](https://github.com/12Aruna/Secure-Account-Dashboard-using-node-js/assets/122152267/5fb33d16-4157-402e-8aa6-0ea1d700090e)


A Collection(**session**) is created which stores the users Logged session.

![sessiondb](https://github.com/12Aruna/Secure-Account-Dashboard-using-node-js/assets/122152267/b4a05c5d-0907-4761-9e3d-0b90d5e95da9)


<br>
<br>
<br>

## Prerequisites
Tools that we need to run this app:

- ***[Node.js](https://nodejs.org/en/)***
- ***[Node Package Manager](https://www.npmjs.com/get-npm)***
- ***[MongoDB (Atlas)](https://www.mongodb.com/cloud/atlas)***

## Installing
```
npm install
```
## Connection to DataBase Access
At line 11 on ```./server.js``` change ***```<DB_USERNAME>```*** with your DataBase UserName & ***```<DB_PASSWORD>```*** with your DataBase Password.

## To Run the App
```
node server.js
```

The server will start Running on
+ http://localhost:3000/


## Author

| Author                | Profile Link                                       |
| --------------------- | :------------------------------------------------- |
| **Arunasalam R** | **[Guru Roxz](https://github.com/12Aruna)** |




