# Retro Fighter - 2D Fighting Game

Retro Fighter is a browser-based 2D fighting game built with HTML5, JavaScript, and the Canvas API. The game aims to recreate the spirit of classic arcade fighting games with player controls, health mechanics, and visual effects.

---

## Game Features

- Two Characters: Player 1 and Enemy, each with unique hitboxes and health.
- Attack System: Implemented using attack box logic with collision detection.
- Winner Detection: Determines a winner based on health or timer expiration.
- Countdown Timer: A 100-second game timer that ends the match automatically.
- Canvas-Based Rendering: Uses the HTML5 <canvas> element for drawing and animating characters.
- Sprites Support: Add custom assets via the /assets folder to personalize the game's visuals.

---

## Getting Started

### Requirements

- A modern web browser (Chrome, Firefox, Edge, etc.)
- No installations required (client-side only)
- Any code editor can be used (e.g., VS Code, Neovim)

---

### How to Run the Game Locally

1. Clone the repository:

   git clone https://github.com/your-username/retro-fighter.git

2. Navigate to the folder:

   cd "D:/fighting game"

3. Open game.html in a browser:

   - Double-click the file
   - Or use a live server extension if using VS Code

---

### Controls (example)

Key       | Action
--------- | ----------------
A / D     | Move left/right
W         | Jump
Space     | Attack
Arrow Keys| Enemy Controls

Controls can be customized by editing game.js.

---

## Code Overview

- game.js: Handles rendering, player input, health bars, and overall game logic.
- utils.js:
  - rectangularCollision(): Detects if attack boxes intersect.
  - determineWinner(): Compares health and declares the winner.
  - decreaseTimer(): Countdown timer that ends the match when it reaches zero.

---

## Customization

You can enhance the game by:

- Replacing characters with custom sprite sheets.
- Adding sound effects for attacks, hits, and wins.
- Extending the timer or improving the health bar UI.
- Adding advanced attack animations.

Assets should be placed in the /assets folder, and paths should be updated in game.js.

---

## Screenshots and Descriptions

**1. Fight Scene**  
This screenshot shows the main gameplay where Player 1 and the Enemy are facing each other, ready to fight. The attack boxes and health bars are visible.  
![Screenshot 1](screenshots/fight.jpeg)

**2. Gameplay Action**  
Here you can see an action moment in the game with attacks being executed and the health bar updating dynamically.  
![Screenshot 2](screenshots/gameplay.jpeg)

**3. Player 1 Wins**  
This screenshot shows the victory screen when Player 1 wins the match. The game correctly detects the winner and displays the result.  
![Screenshot 3](screenshots/player%201%20wins.jpeg)

**4. Player 2 Wins**  
Similarly, this shows the victory screen for Player 2, demonstrating that the game can handle both outcomes correctly.  
![Screenshot 4](screenshots/player%202%20wins.jpeg)

---

## Technologies Used

- HTML5 + Canvas API
- Vanilla JavaScript
- CSS3 (optional enhancements)

---

## Future Improvements

- Multiplayer controls
- Combo attacks and special moves
- Score system
- Mobile support

---

## Contribution

Pull requests are welcome. To contribute:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## License

This project is licensed under the MIT License. You are free to use, modify, or distribute it.

---

## Acknowledgments

- Inspired by classic fighting games such as Street Fighter II and Mortal Kombat
- Built as a learning project to explore 2D game development with JavaScript
