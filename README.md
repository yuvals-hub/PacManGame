# PacManGame

UV-Boy: Pacman Game

UV-Boy is a user-interactive gaming device built on the MCB1700 embedded systems board. The device utilizes the board's joystick and push buttons for input and integrates its LEDs, GLCD, and speaker for an engaging multimedia experience. This project demonstrates how to create a fully functional Pacman game within the constraints of minimal user inputs and embedded systems programming.

Features
Simple Controls:
Five joystick commands: Up, Down, Left, Right, Center
Single push button for gameplay
Dynamic Gameplay:
Seamless navigation through the main menu and game functionalities
Timed events and user-triggered actions drive the game logic
Hardware Integration:
Joystick for navigation and game input
LCD for visual display of the game
LEDs for additional feedback
Speaker for audio effects
Design and Implementation
The program is entirely written in C and consists of:

Initialization: The main() function sets up the LCD, LED, joystick, and other components before launching the main menu.
Main Menu: Displays options that the user can navigate using the joystick.
Game Logic: The Pacman game is designed to be engaging while maintaining simplicity. Movement, collisions, and game events are conditionally executed based on joystick inputs and timers.
Development Process
This project is the culmination of the COE718: Embedded Systems Design course at Toronto Metropolitan University. Building on prior lab exercises, students implemented various components of the MCB1700, gaining experience with:

Joystick programming using KBD development files
LCD design with GLCD commands
LED manipulation using simple bit-banding techniques
Key Components
Joystick: Central to user input, with five directions mapped to integer values for conditional function calls.
LCD: Displays the game's graphical interface, requiring precise implementation for smooth gameplay.
LEDs: Provide visual feedback for events like game state changes.
Speaker: Enhances the gaming experience with sound effects.
Challenges and Adjustments
During development, the project encountered both expected and unexpected issues, such as timing conflicts and hardware limitations. These were resolved by refining the design and optimizing the code structure.

Requirements
Hardware: MCB1700 Development Board
Software: Keil uVision IDE for C programming
Conclusion
UV-Boy demonstrates the practical application of embedded systems knowledge through the design and implementation of a Pacman game. By leveraging the MCB1700’s hardware capabilities and applying real-time programming concepts, this project delivers a fun and functional gaming experience.

Enjoy Pacman on UV-Boy!
