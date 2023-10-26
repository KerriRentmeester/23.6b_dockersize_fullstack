# **Project Name**:

23.6b Dockerize a Full Stack Express App

# **Description**:

The application has two buttons. One button creates a new user and displays the user’s username and email address in the table below. The other button deletes all the users in the MongoDB database, so the table of accummulated data disappears.

The client (React) application was generated using CreateReactApp toolchain and then modified to contain additional functionality.

The server (Node.js) application is a simple express server with three main routes that either read or update data in a MongoDB database.

This project's purpose is to add and edit Dockerfiles in order to dockerize the entire application using Docker and MongoDB. Because of this purpose, this is more of an exercise than a project. 

This exercise highlights my capabilities in Javascript, React, Node.js, npm, Express, Docker, and a taste of MongoDB. This exercise demonstrates my beginning skills in employing Docker and MongoDB, and demonstrates my initial steps into full stack development. I worked on this particular exercise in October of 2023, during module 23 (after 23.6) from the MIT xPro via Emeritus bootcamp I was enrolled in called "Professional Certificate in Coding: Full Stack Development with MERN."

# **Dependencies**: 
The exercise relies on the following dependencies: React, Bootstrap, axios, cors, Express, faker, Mongoose, nodemon, Docker, MongoDB, and Node.js version 14.

# **Usage**:
To run my project on your machine, download the files onto your machine or clone the repo. 
* Download Docker and MongoDB.
* Type terminal command: nvm use 14.17.6
* Install the client and server dependencies by navigating inside each of their directories and running npm install. I opened one terminal for each folder and typed in each: npm install, but I don't think it was necessary to open two terminals.
* Type terminal command: npm start
* The browser window, http://localhost:3000, will automatically open. There will be two buttons displayed: Create User & Delete All Users.
* The exercise was to first create a Dockerfile in the Client folder. Then do the same in the Server folder. Second, in the root folder, create docker-compose.yml file. Third, in Server/src/database.js file, change the URL from localhost to mongo. And finally to type command: docker-compose up

# **Support**: 
Please contact me via email at krentmeester@uwalumni.com.

# **Roadmap**: 
I likely future improvement to this as a "project" would be to add functionality to the app.

# **License**: 
MIT License

Copyright (c) 2023 Kerri Rentmeester

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.