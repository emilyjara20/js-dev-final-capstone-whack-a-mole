# Whack-a-Mole!

# Game overview
This project is a browser-based Whack-a-Mole game where the player clicks on randomly appearing moles to earn points within a limited time. The goal is to achieve the highest score before the timer runs out. The game emphasizes quick reaction time and accuracy.

![whackamole](https://github.com/gabrielsanchez/erddiagram/blob/main/whackamole.gif?raw=true)

# Development Plan
- Game start / reset function: Initializes score, timer, and mole positions
- Random mole generator: Uses a random index to display moles in different holes
- Click handler: Detects user clicks and updates score
- Game over logic: Stops the game and displays final score

# Challenges and Debugging

- Issue: Score incrementing multiple times per click
  - Fix: Disabled repeated clicks on the same mole
- Issue: Timer not stopping properly
  - Fix: Ensured game state variable controls all functions

# Project Summary
This project involved building a fully functional Whack-a-Mole game using HTML, CSS, and JavaScript. I designed the game logic, implemented randomization and timing features, and handled user interaction through event listeners. Challenges included managing timing functions and preventing duplicate scoring, which were resolved through debugging and testing. Overall, the project strengthened my understanding of JavaScript fundamentals, and DOM manipulation.

# Replit screenshot 
<img width="2112" height="1284" alt="image" src="https://github.com/user-attachments/assets/aafe20d7-60ea-472f-a199-b4a4fe010542" />
