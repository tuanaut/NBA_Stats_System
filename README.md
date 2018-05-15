# NBA_Stats_System
This project will track statistics on a per-team, per-player, per-game basis.


## Goals
This project will track statistics on a team basis, on a person basis, and on a game basis.
Teams should be abstracted as to represent any kind of team, and then an concrete definition provided (in a separate package) for NBA
Players should be abstracted as to represetn any kind of player, and then concrete definition ...
Games should be ....



### Teams
Teams will start building from a top down level. We should be able to see what player is on what team, and when they started. It is common for players to move accross temas, so start and end dates are required. And weather or not they are currently on a team should be tracked, and the state of the player (general play status - injury, benched, etc.)
<br/>
You should be able

### Games
Games will start building from a top down level


### Statistics
Statistics should be approached from a top down level. We would like to start tracking

# Create a project
Building a project:
1. use the maven archetype to generate the project (java core (j2se, java8))
2. add logging using dependency information. Finad and verify the latest JUNIT

## structure
1. Break the project into the MVC mode
2. Ensure the model supports both abstract layers, as well as concrete. Ensure the concrete layers ARE NOT IN THE SAME PLACE (PACKAGE) as the abstraction
3. Controllers should have the following purposes:
  3.a seed a player
  3.b seed a team
  3.c seed a list of games
4. I should be able to request a list of all upcoming games
5. I should be able to request a list of all finished games
..* I should be able to see the final score for each of these games 
6. For each game that I see, I want to get a list of all players



## OLD
This project will collect stats from the remaining four teams from the NBA playoffs (Golden State Warriors, Houston Rockets, Cleveland Cavaliers, and Boston Celtics). It will use this data to log rankings of these teams by the team stats. 

The project will be a Maven project written in Java and will use JUnit testing. It will focus on using logging files, identity classes, and improved coding conventions. 

The collaborators on this project will be Tuan and Avi. The project will be pulled daily and features/functionality will be implemented on seperate branches from master. After the finished features are approved by the other collaborators, the finished branch will be merged back into master.
