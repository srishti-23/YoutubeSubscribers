# YoutubeSubscribers

<h1 align="center"> 
YOUTUBE SUBSCRIBERS
</h1>
<p align="center">Node.js application to get all details of youtube subscribers.</p>



## Table of Contents

- [Introduction ](#introduction)
- [Features ](#features)
- [Tech Stack ](#tech-stack)
- [Prerequisites ](#prerequisites)
- [Installation & Run](#installation-and-run)
- [API Reference ](#api-reference)


## Introduction
Get YouTube Subscribers is an Application that serves as a RESTful API created by using Mongodb in Node.js. It is designed to fetch all subscribers information related to YouTube channel subscribers. The primary technologies used to develop this application are Node.js and Express.js which are used to create API endpoint and manage HTTP request. Additionally, this application utilizes MongoDB as the database to store and manage subscribers data efficiently.



## Features
Some features of this application :
- *Seamless Data Retrieval:* Effortlessly fetch subscribers data from YouTube channels using API endpoints.
- *Structured JSON Output:* Present retrieved data in well-organized JSON format for easy interpretation.
- *Versatile API Endpoints:* Provide users with multiple API endpoints catering to various data retrieval needs.
- *Effective YouTube Data API Integration:* Interact seamlessly with the YouTube Data API for accurate data retrieval.
- *User-Friendly Setup:* Follow a straightforward setup process, enabling swift utilization of the tool.

## Tech Stack
Youtube-Subscriber is build using the following technologies:

- *Node.js:* A runtime environment that execute javaScript code on the server-side.
- *Express.js:* A node.js framework for building web application and RESTful API.
- *MongoDB:* Is NoSQL Database system that stores and manage data in JSON-like format.

## Prerequisites

To run this project locally, make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

## Installation and Run
1. Clone the repository from GitHub:
    
     git clone https://github.com/srishti-23/YoutubeSubscribers.git
    
2. Redirect to the project folder:
    
     cd Youtube-Subscribers
    
3. Install the required dependencies:
    
     npm install
    
4. Configure the application:
   - Create a .env file in the root directory of the project.
   - Add the following environment variables to the .env file:
      
       PORT=3000                             # The port on which the application will run
       DATABASE_URI= <your_uri_here>         # The MongoDB connection string
      
5. Create Database:
    - Inserting subscribers data into MongoDB.
        
         npm run createDB
        
6. Start server:
    
     npm start
    
    > [!NOTE]
    > Access the  application in your web browser at http://localhost:3000 (base URL)


## API Reference
Following API endpoints for retrieving subscribers information using the GET method. 

- /subscribers: Retrieve a list of all subscribers with their ID, name, subscribed channel and date.
- /subscribers/names: Obtain subscribers name along with the channel they are subscribed to.
- /subscribers/id: Access subscriber information based on their ID.





