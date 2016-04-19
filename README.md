# 2dgame-Server-Side

Server side for the 2DGame App.

## Getting Started

### Get the code

Clone this project on your local machine with

    git clone https://github.com/andreasonny83/2dgame-server.git

### Install the project devDependencies

This project uses NodeJS and npm. If you don't have them already installed on your local machine check the [official documentation](https://docs.npmjs.com/getting-started/installing-node).

Then navigate inside your project directory and run:

    npm install

## Running the server

Once you have all the dependencies install, open a terminal window,
navigate inside your local copy of this repository. Then run:

    npm start

This will initialize the server on your local machine.
Leave the terminal running on your background, then the client side should be able to establish a communication.

You can run a quick sanity check on your server machine just opening a browser on: `http://localhost:9004/status`. If you're able to see a JSon formatted output displaying a `Status: 200` and some other server information, your server is running and your client app should be able to establish a communication with it.
