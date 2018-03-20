# PROJECT-1-TRACEBALL

## Game Description
The player will control a square by moving their mouse cursor within the game window. The player will be chased by an NPC square that will try to touch the players square. If the two squares come in contact, the player will lose a life. Once they lose 3 lives them its game over. 
## User Stories
1. As a player I would like to know when I have come in contact with an NPC
2. As a player I would want my character to follow my mouse cursor
3. As a player, I would want to know when I have lost all 3 lives
4. As a user I would like to play in a browser
5. As a player I'd want the NPC to follow my character
6. As a user I would like to be able to see both characters

## Flow Chart:
![trace-ball-flow-chart](https://user-images.githubusercontent.com/31927590/33268885-b42e75b0-d376-11e7-9e28-870bbc7c0def.PNG)
## Gant Chart:
![capture](https://user-images.githubusercontent.com/31927590/33561443-8abeee78-d90a-11e7-9d87-4bb57bb55dcd.PNG)
## Product Backlog:

### High Level Function Requirements

* Create Canvas(500pixels x 500pixels)
* Create 2 dimensional character
* Create a non-playing character NPC
* User mouse movement moves character
* Have NPC move to player position
* Character stays within Canvas
* Collision detection and display
* Start and stop game

### High Level Non-Functional Requirements

* Canvas Colour
* Character and NPC shape
* Player and NPC colour
* Canvas size

# Design Documentation:
## Process of Implementation
We started the project by creating the HTML page for the game to run on. We then made the canvas which is the playable area for the player and the NPC. We then tracked the mouse coordinates so that we could map the players square to those coordinates. Once we tracked the player shape to the mouse coordinates, we were then able to track the NPC to the player. We made the NPC have a different colour so that it was clear which shape was which. Once we were able to have the NPC track the player we started to look at the collision aspect as that there was a clear indication when the two shapes came in contact - we did this by changing the colour of the player’s shape. The last feature that we had to implement was the lives, we added 3 lives and made it so when the player and the NPC collide a life would be deducted and once all lives are gone, the game ends.
## IDE used and Features
The IDE (Integrated Development Environment) that was used was notepad. Unfortunately, it has no redefining features which could have helped during the coding process which for a first time coder is fairly difficult. It can only be used as an area to write code and save the file in relation to the type of code written. After the first week, we switched to an online IDE called 'repl.it' it allows the user to test the code as well as give basic debugging features. 
#### Here is a screenshot of my working code with game to the right:
![project_1](https://user-images.githubusercontent.com/31927590/35565773-c8909232-05b6-11e8-88ee-a3b5e15dedd3.png)
## Debugging Process
When we first started coding using notepad, we did not have an easy way of debugging problems with our code, we would have to scroll through the code and make changes and keep running the code to see the changes. Once we switched to 'repl.it' our debugging improved as we were able to see a live preview as well as get valid debugging messages to tell us where we made mistakes.
## Coding Standards
During the coding process, I made sure to constantly indent my code often so that I was able to identify the breaks in commands or even functions. it also means you don’t have to press space a lot to get the same affect. Throughout i also made sure to add comments where necessary in order to understand the code if i needed to come back to it. Curly brackets were also used to break up my code. I used appropriate variable names also so that i was able to quickly read and understand what variables did what.
### Commenting:
When i was writing my code i made sure to always correctly comment any lines of code that i did not fully understand, this way i was able to come back to the code, read the comment and understand it again.
Below is an example from my code where i use Comments:
```javascript
//draw co-ordinates of text
	context.fillStyle = "Red"; //makes the text red
	context.font="18px sans-serif"; //defines the font and the size
	context.fillText("Mouse ("+mouseX+","+mouseY+")", 10, 20); 
	context.fillText("Lives = ("+lives+")", 180, 20);
```
## Evaluation
Overall I feel that as this was my first time coding an interactive 'game' styled program it went very well. I learnt have to diagnose simple coding errors/mistakes as well as pick up simple terminology whilst being able to implement it into my code. although i did not comment on my code as much as was recommended I felt that I was able to understand everything and understand what each line of code did as well as its importance.
