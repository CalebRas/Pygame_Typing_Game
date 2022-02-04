# Overview

This game, Jungle Typer, is the first game I created with a GUI.  I made it to get my feet wet in game and desktop app development while using Pygame and Python.  In doing so, I learned how to display multiple screens of graphics, handle input from the mouse and keyboard, and move objects.  Combining those, I created an interactive game with logic such as lives, scoring, and levels.  Overall, implementing this project allowed me to add a basic knowledge of game development to my software engineering repertoire. 

Though this game is a standalone app and personal learning project, I continue to add to grow my knowledge, it also ended up serving as the base code and engine for a more robust game I created as part of a team.  We designed and implemented a very similar application to help K12 kids build their typing skills.  Having no knowledge of game engineering previous to this project, it served as a great tool to supply my team and gave me the skills to collaborate with them as we added more classes and functionality to my code. There is a link for that project's repository below.

[Typing Trainer Repo](https://github.com/Tyler242/Typing-Trainer)

Game Rules:
The object of Jungle Typer is to get the highest score possible while typing the moving words before they disappear off the edge of the screen.  If a word is typed correctly, a point is added to the score for every letter in the word, meaning longer words are worth more than shorter ones.  After every 50 points, the game levels up, and the words move faster.  At every level, the player gets five lives, which are used as untyped words go off the screen.  After the player runs out of lives, their final score is displayed.

Please click on the link below for a video demonstration of the gameplay and a code walkthrough. 

[Jungle Typer Demo Video](https://youtu.be/2uxdgXqnSUM)


# Development Environment

* Visual Stuido Code 
* Python 3.9.7 64-bit
* Pygame 2.1.2

# Useful Websites

* [Pygame Documentation](https://www.pygame.org/docs/)
* [Getting Started with Pygame, GeeksforGeeks](https://www.geeksforgeeks.org/getting-started-with-pygame/?ref=gcse)

# Sources

* [Background Image]("https://www.vecteezy.com/free-vector/game-background")
* [Full Word List](https://www.mit.edu/~ecprice/wordlist.10000)

# Future Work

Below are a few of the features I plan to implement in the future: 
* The ability to save scores with a username 
* Add a restart button
* Letters in words change color as typed