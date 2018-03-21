# Cube Chaser
# Project: 001
### Required: 
Jscript

## Introduction
The aim of this project was to create a web based game. There are two characters: the player, and the enemy npc. The aim of the game is to keep your character away from the enemy, until a timer concludes. The player has three lives, if the enemy NPC hits the player they lose a life. When the player runs out of lives, the game ends. 

## High level Description
A non-playing character NPC targets the users mouse position as the player moves across the screen. A timer will start on start, While on a timer you must avoid the NPC. The game ends when the enemy NPC has touched your character three times within the time.  

### High level functional specifications
- Player Character tracks player mouse co-ordinates.
- Enemy NPC follows player mouse.
- Player has 3 lives.
- If player runs out of lives the game ends.
- Player will win if they survive a certain amount of time without being hit.

### High level non-functional specifications

- Obstacles dotted around map.
- Multiple enemy NPCs.
- Multiple diffulty settings.
- Linear level by level.
- Better UI: Game menu, settings, ect.
- Scoring system.
  - Leaderboards.

### Application requirements
- Notepad
- Google Chrome

### Mock-ups

### Storyboards

### Flowchart
![](https://i.imgur.com/5PDVXLm.jpg)

### High-level user stories

### Research
I used multiple forums during research. This was to see how others had solved certain issues i was facing. I found an extremely helpful forum on stack overflow. (https://stackoverflow.com/questions/7143806/make-an-image-follow-mouse-pointer) One of the answers was very useful, as it gave me a greater understanding of how to use functions.

### Teamwork

I was assisted by one of my peer's at 'ReebootGaming'. He helped me better understand how to layout my game screen. I didnt realise that ![](https://i.imgur.com/5ftrhXF.png) made my 'GameViewPort' stick in one position. 

He also helped me understand how to display my mouses co-ordinates. The following snippet ![](https://i.imgur.com/0AB7f4N.png) is displaying my mouse co-ordinates.

![](https://i.imgur.com/5R17B3W.png) creates my player character (Green square). 

## Troubleshooting
- I had trouble getting the Player box (green) to follow the users mouse. To get this to work i searched online for a solution. I eventually found that someone had posted a question to a forum. They asked how they would be able to get an image to follow the users mouse on their website. I took code (shown below) that was given as an answer and disected it. 

![](https://i.imgur.com/h1zwQQO.png)

I looked at this snippet of code. 

![](https://i.imgur.com/OTnEHig.png).

This snippet of code gets my mouse co-ordinates

### Current State of the game
#### Below is a screenshot of the current state of the game.
- Below is a screenshot showing the tracking aspect of the game. This will actively show the position of the mouse pointer. 

![](https://i.imgur.com/vJEL30u.png)

- And here is a screenshot showing my game screen. 

![](https://i.imgur.com/ISyGJgD.png)


