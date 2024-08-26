Turn-Based Chess-like Game with WebSockets

This project is a real-time, turn-based strategy game inspired by chess. It uses a server-client architecture with WebSockets for smooth communication between players.

Get Started!

Before you jump in, make sure you have the following:

* Node.js: Download and install Node.js from the official website ([https://nodejs.org/](https://nodejs.org/)) if you don't have it already.
* Web Browser: Any modern web browser like Chrome, Firefox, or Edge will work.

Setting Up Your Game

Clone the Repository:

   Open your terminal or command prompt and use the following command to clone this repository:

   ```bash
   git clone https://github.com/monish-parimi/ParimiMonish_21BCE8397-Turn-based-Chess-like-Game-with-Websocket-Communication.git
   ```

   Then, navigate to the project directory:

   ```bash
   cd ParimiMonish_21BCE8397-Turn-based-Chess-like-Game-with-Websocket-Communication
   ```

Server Setup:

1. Install Dependencies:

   Change directories to the server folder and install the required dependencies using npm:

   ```bash
   cd server
   npm install
   ```

2. Start the Server:

   Run the server using the following command:

   ```bash
   node server.js
   ```

   This will start the WebSocket server, typically running on `ws://localhost:8080`.

**Client Setup:**

1. **Navigate to Client Directory:**

   Go back to the main project directory and navigate to the client folder:

   ```bash
   cd ../client
   ```

2. **Launch the Game:**

   Open the `index.html` file in your web browser. You can either open it directly using the browser or through your file explorer.

Playing the Game

Match Up:

The game is designed for two players. Each player controls a team of five characters: Pawns, Hero1s, and Hero2s. Players take turns strategically moving their characters across the board according to the game rules.

How to Play:

On your turn, simply click on one of your characters and choose a valid move from the available options. As moves are made, the game state updates in real-time, reflecting the new positions of all characters. The game continues until one player eliminates all of the opponent's characters, claiming victory!

Game Rules:

Setting Up the Board:

* The game takes place on a 5x5 grid.
* Two players face off, each with five characters strategically placed on their starting row.

Character Movement:

- Pawn: This basic unit can move one space in any direction (left, right, forward, backward).
- Hero1: A powerful warrior who can move two spaces straight in any direction, eliminating any opponent's character that stands in its path.
- Hero2: A tactical unit that moves two spaces diagonally in any direction, also eliminating any opponent encountered along the way.

Taking Turns:

* Players alternate turns, making one move per turn.

Combat:

- Landing on an opponent's character eliminates it from the game.
- Hero1 and Hero2 can eliminate any opponent character within their movement path, not just the final destination.

Invalid Moves:

 The game enforces valid moves. If you attempt an invalid move, you'll need to choose again. Here are some examples of invalid moves:
    * Selecting an opponent's character.
    * Moving a character outside the grid boundaries.
    * Making a move that violates your character's movement pattern (e.g., Pawn moving diagonally).
    * Attacking a friendly character.

Winning the Game:

 The player who successfully eliminates all of their opponent's characters wins the game!

Contact:

If you have any questions or encounter any issues, feel free to reach out I'd be happy to help!
