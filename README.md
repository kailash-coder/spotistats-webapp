# Spotistats
Spotistats is a tool that uses the Spotify Web API to give statistics about a user's musical habits on Spotify. Currently, this includes information about a user's top artists and top tracks.

API calls to the Spotify database are accomplished with a Node/Express backend. The client id and secret id are hidden using dotenv.

## Viewing the Application
1. Clone down this repository and install npm. Execute the following command in your CLI.
```
npm install
```    
2. To start the application on localhost:3000, enter the following command.
```
npm start
``` 

## Creating the local_config
To run Statify, a file named `spotistats/local_config.js` must exist with the 
following contents:
```
const spotify = {
  clientId: '<spotify API client ID>',
  clientSecret: '<spotify API client secret>'
};

module.exports = { spotify };
``` 
