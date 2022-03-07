# The X-Wing Racer Simulation Game

<img src="./src/client/assets/images/game.png" alt="screenshot of game" height=300px>

## About

This project was created as a part of the Udacity JavaScipt Nanodegree program.  It's purpose is to dimonstrate the use of callbacks, promisses, and async/await in asynchronous javascript programming.

The game is simple.  Select your race track, your racer, and click Start Race.  Wait for the countdown to finish and the leaderboard to display.  Click the green burron on the right to accelerate and keep your racxer on top.  Once all racers have completed the race the results will be desplayed in the leader board. 

## Getting Started

In order to build this game, we need to run two things: the game engine API and the front end.

### Start the Server

The game engine has been compiled down to a binary so that you can run it on any system. Because of this, you cannot edit the API in any way, it is just a black box that we interact with via the API endpoints.

To run the server, locate your operating system and run the associated command in your terminal at the root of the project.

| Your OS               | Command to start the API                                  |
| --------------------- | --------------------------------------------------------- |
| Mac                   | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-osx`   |
| Windows               | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server.exe`   |
| Linux (Ubuntu, etc..) | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-linux` |

Note that this process will use your terminal tab, so you will have to open a new tab and navigate back to the project root to start the front end.

#### WINDOWS USERS -- Setting Environment Variables
If you are using a windows machine:
1. `cd` into the root of the project containing data.json 
2. Run the following command to add the environment variable:
```set DATA_FILE=./data.json```

If you still run into issues running the API server on your machine, you can run this project in the Udacity classroom.


### Start the Frontend

First, run your preference of `npm install && npm start` or `yarn && yarn start` at the root of this project. Then you should be able to access http://localhost:3000.
