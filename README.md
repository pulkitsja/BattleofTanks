# BattleofTanks
Network Based Rendition of Classical Game

All players connect to a single server.
The server updates all the players regularly regarding the current state of their peers. 
Server also maintains a live scoreboard, accessible to all the clients.

Major Game Features -
1. Live ScoreBoard
2. Team Chat application
3. Player Respawning
4. Time Bombs
5. Randomized Maze 

Compiling
1. gcc -g server.c -o server
2. ./server 'Server-IP'
3. gcc -g client.c -o client
4. ./client 'Server-IP' 'Client-IP'
