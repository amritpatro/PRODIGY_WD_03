# PRODIGY_WD_03

## Detailed Description

This project involves creating a Tic-Tac-Toe game using HTML, CSS, and JavaScript. Below is a comprehensive breakdown of its components and functionalities:

### HTML Structure

The HTML file structures the game and includes the following sections:

#### Head Section:
- **Title Tag**: Sets the title of the webpage to "Tic-Tac-Toe Game".
- **External Stylesheets**: Links to Bootstrap for styling and Font Awesome for icons.
- **Custom Styles**: A link to the external CSS file (`styles.css`) for custom styles.

#### Body Section:
- **Container**: A `div` container that centers the content and includes:
  - **Heading**: An `h1` element with the title "Tic-Tac-Toe".
  - **Game Board**: A `div` styled as a grid with nine cells.
  - **Game Status**: A `div` for displaying the game status.
  - **Restart Button**: A button for restarting the game.

### CSS Styling

The CSS file styles the game elements as follows:

- **Body**: The background color is set to dark gray, the text color is white, and the font family is 'Roboto'.
- **Container**: The container has a top margin for spacing.
- **Board**: The board is styled as a grid with three columns and a gap between cells. It is centered and has a maximum width.
- **Cell**: Each cell has a fixed size, dark background color, centered text, and a hover effect that changes the background color.
- **Status**: The status text is centered and has a top margin.
- **Button**: The restart button is centered and has a margin for spacing.

### JavaScript Functionality

The JavaScript file handles the game logic and interactivity:

#### Variables:
- **DOM Elements**: `board`, `statusDisplay`, and `restartButton` are selected using `getElementById`.
- **Game State**: `gameActive` is a boolean indicating whether the game is active, `currentPlayer` tracks the current player ('X' or 'O'), and `gameState` is an array tracking the state of the game board.

#### Winning Conditions:
- An array of arrays defining the winning combinations of cell indices.

#### Functions:
- **handleCellPlayed(clickedCell, clickedCellIndex)**: Updates the game state and the clicked cell's content.
- **handlePlayerChange()**: Switches the current player and updates the status display.
- **handleResultValidation()**: Checks for a win or draw and updates the game status accordingly.
- **handleCellClick(clickedCellEvent)**: Handles cell clicks, updates the game state, and validates the result.
- **handleRestartGame()**: Resets the game state and updates the display.

#### Event Listeners:
- Each cell listens for clicks to handle cell plays.
- The restart button listens for clicks to reset the game.

### Conclusion

This project demonstrates how to create a simple and interactive Tic-Tac-Toe game using HTML, CSS, and JavaScript. The combination of these technologies results in a visually appealing and functional game that users can play directly in their web browser. The game logic handles player turns, checks for winning conditions, and allows for game resets, providing a complete and enjoyable user experience.

Feel free to customize the styles and functionality to suit your specific needs and preferences!
