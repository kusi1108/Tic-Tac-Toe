## Tic-Tac-Toe game Introduction
This is a java based Game developed on VS Code.
#### Technologies used
- Java
- Java Swing(Graphic Library): Jpanel, JButton, ActionListener, Grid Layout

### Project Setup
- A new Java project named "tic-tac-toe" is created, and necessary files are prepared by removing default lines in the 'app.java' file and creating a 'TicTacToe.java' file for the game code

### Building the Game Interface
- The game window is set up using Java's Graphics Library, with specified dimensions and properties including non-resizability and a close operationss.
- Panels are introduced for the game board and for displaying text, such as current player information and game statusss.
- A three-by-three grid layout is established for the Tic-Tac-Toe board using a JPanel with buttons representing each tiless.
### Game Logic Implementation
- Buttons are initialized with action listeners to set the text to the current player's marker (X or O) when clickeds.
- The program alternates between players and checks for empty tiles before placing a markers.
- A check for winners is implemented, examining horizontal, vertical, and diagonal winning conditionsss.
### Enhancements and Final Features
- When a player wins, the tiles' colors change to indicate the winner, and a message is displayed on the text labelss.
- A tie condition is checked by counting the number of turns, and if no winners are found after all tiles are filled, the game denotes a tie with color changes for all tilesss.
- Adding a restart button and tracking player scoresss.
### Conclusion
- The Tic-Tac-Toe game interface is successfully built using Java's Graphics Library, with a clear layout, interactive buttons, and informative text displays for players.
- The game logic effectively handles player turns, marker placement, and checks for win or tie conditions, creating a functional and engaging game experience.
- Future improvements, such as adding a restart button and score tracking, are proposed, allowing room for further development and user engagement.

### Below is the Map representation for better understanding
![image](https://github.com/user-attachments/assets/5caaeff8-7ff3-4f3d-ac26-f5ae31fad570)
