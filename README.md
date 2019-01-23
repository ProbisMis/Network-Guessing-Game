# Network-Guessing-Game
This game is a basic guessing game between two users. 
Both sides will guess a number whoever is closer to server's random number, that player wins the round.
Winning condition is best of 3. Whoever makes 2 round wins, wins the game as well. 

Requirements; 
1. You need to know the server IP and listening PORT.
2. You need to give one-word name to connect to lobby.
3. You can not choose a name that already exist in the game lobby. 

After connection  established with lobby;
1. You can request a player list to see which players are connected to game and corresponding points near their name
2. You can invite a player to play game. If enemy is not receiving invitations or not in game. 
3. If enemy player rejects your request do not worry, you can invite another player or retry after few seconds.
4. If enemy player accepts your request guessing game starts.

Here the game panel for player 1;
![client-burak](https://github.com/ProbisMis/Network-Guessing-Game/blob/master/client-burak.png)

Here the game panel for player 2;
![client-enemy](https://github.com/ProbisMis/Network-Guessing-Game/blob/master/client-enemy.png)

And the server looks like;
![server](https://github.com/ProbisMis/Network-Guessing-Game/blob/master/server.png)

Bugs;
1. Closing window forms from X button will make the game crash. More precisely, you will still be in the gamelobby. Eventhough , you are quitting. 
