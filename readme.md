# Interactive Chess Game

This project is a simple, interactive chess game built using HTML, CSS, and JavaScript. It provides a fully functional chessboard where two players can play against each other in the browser.

## Features

- Fully interactive chessboard
- Legal move validation
- Turn-based gameplay (alternating between white and black)
- Piece capture
- Check and checkmate detection
- Stalemate detection
- Responsive design for various screen sizes

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- [chess.js](https://github.com/jhlywa/chess.js) library for chess logic and move validation

## Setup and Installation

1. Clone this repository or download the source code.
2. Open the `index.html` file in a modern web browser.

That's it! No additional setup or installation is required.

## How to Play

1. The game starts with the white player's turn.
2. To move a piece:
   - Click on the piece you want to move. The selected piece's square will be highlighted.
   - Click on the destination square where you want to move the piece.
3. If the move is legal, the piece will move to the new square. If not, the move will be ignored.
4. Players take turns moving pieces.
5. The game ends when one player checkmates the other, or when a stalemate occurs.

## Game Status

The current game status is displayed below the chessboard. It shows:
- Whose turn it is
- If a player is in check
- If the game has ended (checkmate or draw)

## Future Enhancements

- Add a move history display
- Implement an undo move feature
- Add a timer for each player
- Create an AI opponent
- Implement online multiplayer functionality

## Contributing

While this project is primarily for educational purposes, suggestions and improvements are welcome. Feel free to fork the repository and submit pull requests.

## Acknowledgments

- Thanks to the creators of the [chess.js](https://github.com/jhlywa/chess.js) library for providing the chess logic.
- Unicode chess piece characters are used for the game pieces.

Enjoy playing chess!