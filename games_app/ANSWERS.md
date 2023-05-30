1. What is responsible for defining the routes of the games resource?

The GamesContainer is responsible for defining the routes

2. What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?

The folder structure is separated into Frontend and Backend. The client is responsible for the Frontend and files associated with the Frontend. The server is responsible for the Backend.

3. What are the the responsibilities of server.js?

server.js is responsible for:

    1. Establishing a connection to the MongoDB
    2. Storing information in the Database
    3. Giving an error if it can't connect to the Database


4. What are the responsibilities of the gamesRouter?

The gamesRouter is responsible for performing CRUD actions on the games in the Database

5. What process does the the client (front-end) use to communicate with the server?

The client uses fetch to get the games from the database

6. What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs

It also takes in the init options object. Method is the request method, headers are headers you want to add to the request, body is a body you want to add to your request

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?

It consumes the baseURL which is port 9000

8. What are we using the MongoDB Driver for?

The MongoDB Driver allows the app to connect with the Mongo Database and save information.

