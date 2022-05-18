# Rocket League Bots

### Introduction
Rocket League is a multi-platform video game, developed by Psyonix (now a subsidiary of Epic Games) and released in 2015. The game's growth in popularity has culminated in a global online community of players, a professional e-sports circuit, and even e-sports scholarships for accomplished young players aiming to compete at the collegiate level. 

### Project Overview
This project aims to explore the applications and limitations of artificial intelligence and machine learning within Rocket League, and ultimately seeks to determine if bots capable of a high level of game skill can be constructed and trained. These bots will be developed using Python and its ML libraries such as TensorFlow and Pytorch. Bots will be tested and trained in matches against one another, and eventually, against human players. 

### A Primer on Rocket League, for the Uninitiated
The concept of the game in its base form is simple: vehicular soccer (aka football) within a three-dimensional, rectangular enclosure; complete with two goals, walls and a ceiling that the players' cars can drive on. A point is awarded to the team that successfully shoots the ball into the opposing team's goal, and the team with the most points at the end of the 5-minute timer wins. In the event of a draw, overtime will be played in a "sudden death" format, where the first team to score wins. Players compete in teams of 1-4, and can choose to play in both casual and ranked settings. 

Each car is equipped with a rocket engine at the rear, which can be used to increase the car's speed on the ground, or to launch the car at the ball while the ball is airborne. To utilize this rocket engine, players must drive over "boost pads" to fill the rocket's reserves. 

While the rules of Rocket League are simple, actual gameplay is anything but. The nature and pace of the game forces players to consider their speed, direction, positioning, launch angle, and ball trajectory when attempting to make contact with the ball. The calculus is further complicated in team games (2v2, 3v3, or 4v4), where players must also consider their teammates' positioning in addition to that of their opponents. Without delving into the specifics of mechanics and team strategy, it should be noted that errors made when challenging for the ball are frequently punished in the form of conceding a goal.

### Performance Metrics
Once it has been determined that a bot can competently perform all functions necessary in the game, performance will be monitored using the following metrics:
- all-time win/loss record
- avg goals scored per match
- avg goals conceded per match
- avg assists per match
- avg saves per match
- in-game rank, which is denoted below, in ascending order:
  - Bronze
  - Silver
  - Gold
  - Platinum
  - Diamond
  - Champion
  - Grand Champion
  - Supersonic Legend

### Meet the Bots
#### BoostHog 
BoostHog is an initial foray into this bot creation project, and a test of the bot's ability to interact with stationary objects on the field of play. BoostHog's primary directive is to drive over boost pads on the field, locating the nearest boost pad to travel to once one is picked up. BoostHog will also use its boost to travel between pads as fast as possible, in order to beat other players to the pad (hence the name). If a boost pad has been taken by a player, the bot will ignore that pad and opt for the closest pad that is still active. 

While BoostHog may not be the greatest competitor in Rocket League history, it serves its purpose for demonstrating python's capabilities and potential, and a foundation upon which AI or ML code can be deployed.

####

