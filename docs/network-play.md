# Network Play

## Game Client Authentication

- Game client must ask the user for their username and password, which it can store in a configuration file so it doesn't need to be entered every time the program is run
- Game client will use the username and password to retrieve an authtoken from the server, the auth token is used to authenticate your requests to the server

## Game Management Workflows

- Creating a Game
- Joining a Game
- Playing a Game

### Creating a Game

-   Enter your player name
-   Enter the game name
-   Use the DandD Client Module to create the game
-   Wait for players to join and the game to start

### Joining a Game
-   List out the games that are waiting for players
-   Pick a game
-   Input your player name
-   Use the DanD Client Module to Ask Permission to Join
-   If accepted into the game, wait for the game to start
-   if not accepted into the game, return to the main menu