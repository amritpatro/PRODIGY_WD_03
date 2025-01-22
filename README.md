# PRODIGY_WD_03
Detailed Description
This code creates a Tic-Tac-Toe game using HTML, CSS, and JavaScript. Here's a detailed breakdown of its components and functionalities:

HTML Structure
The HTML file structures the game and includes:

Head Section:

The title tag sets the title of the webpage to "Tic-Tac-Toe Game".

External stylesheets are linked, including Bootstrap for styling and Font Awesome for icons.

A link to the external CSS file (styles.css) is included for custom styles.

Body Section:

The body tag contains a div container that centers the content and includes:

A heading (h1) with the title "Tic-Tac-Toe".

A div for the game board, styled as a grid with nine cells.

A div for displaying the game status.

A button for restarting the game.

CSS Styling
The CSS file styles the game elements:

Body: The background color is set to dark gray, the text color is white, and the font family is 'Roboto'.

Container: The container has a top margin for spacing.

Board: The board is styled as a grid with three columns and a gap between cells. It is centered and has a maximum width.

Cell: Each cell has a fixed size, dark background color, centered text, and a hover effect that changes the background color.

Status: The status text is centered and has a top margin.

Button: The restart button is centered and has a margin for spacing.

JavaScript Functionality
The JavaScript file handles the game logic and interactivity:

Variables:

board, statusDisplay, and restartButton are DOM elements selected using getElementById.

gameActive is a boolean that indicates whether the game is active.

currentPlayer tracks the current player ('X' or 'O').

gameState is an array that tracks the state of the game board.

Winning Conditions: An array of arrays that defines the winning combinations of cell indices.

Functions:

handleCellPlayed(clickedCell, clickedCellIndex): Updates the game state and the clicked cell's content.

handlePlayerChange(): Switches the current player and updates the status display.

handleResultValidation(): Checks for a win or draw and updates the game status accordingly.

handleCellClick(clickedCellEvent): Handles cell clicks, updates the game state, and validates the result.

handleRestartGame(): Resets the game state and updates the display.

Event Listeners:

Each cell listens for clicks to handle cell plays.

The restart button listens for clicks to reset the game.

Conclusion
This project demonstrates how to create a simple and interactive Tic-Tac-Toe game using HTML, CSS, and JavaScript. The combination of these technologies results in a visually appealing and functional game that users can play directly in their web browser. The game logic handles player turns, checks for winning conditions, and allows for game resets, providing a complete and enjoyable user experience.
