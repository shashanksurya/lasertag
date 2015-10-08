Introduction

Our idea for this project is to design an online multiplayer game using a game engine and socket programming. This game uses the rich C++ network library to communicate between players and a centralized server which manages the complete game.

Game Description

The game starts with each player connecting to the server first and wait for the server till certain number of players (2-4) are online. Once the required number of players are online, the game starts by tagging each player with an ID or alias name required for the game. Each player avatar will have health bar and also a laser gun which has unlimited ammo. Once each player is ready to play the game, the server begins a countdown for everyone to get ready to play the game. Each player then shoots the other players on the network with his laser gun inside a maze. The challenge of the game is to find other players inside the arena (or maze) and kill every one of them to win. The last player to survive this battle will be declared as the winner. 

Game Rules
•	The health will be decreased by certain amount each time a player is hit by the laser
•	Each player should join the game only once to avoid any network issues
•	Player will be declared as dead when all his health is depleted

Technical Requirements
We are planning to develop this using the below tools.
Unreal Engine 4 (Free for students)	Game engine required for the gameplay
C++ Networking Libraries	For supporting the network functionality of both client and servers
Parallel programming libraries(if time permits)	Making the game run on multiple cores instead of using one core to speed up the game and improve the graphics

We plan to design the game to be simple without any need of a graphic card on the system. As we just started to design the required components for the game, we are keeping the goals of the project realistic. The parallel programming libraries in C++ can be used to enhance the gameplay but, we plan to finish the basic game and extending to this functionality later.
Project Progress
•	Installed and configured Unreal Engine 4
•	Working on creating mesh models for avatars(players) in the game
•	Developed basic skeleton required to support server functionalities 
•	Preparing use cases required for game
Also, we have spent considerable amount of time in discussing about the project and the libraries that can be used for developing this game. 
