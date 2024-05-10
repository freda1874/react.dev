 
## Tic-Tac-Toe game built with React

#### Introduction
Tic-Tac-Toe app allows two players to play the classic game of Tic-Tac-Toe interactively. The game board consists of a 3x3 grid where players take turns marking spaces with 'X' and 'O'.
The first player to align 3 of their marks vertically, horizontally, or diagonally wins the game. If all squares are filled and no player has three marks in a row, the game ends in a draw.
![image](https://github.com/freda1874/react.dev/assets/85437054/f5afa417-8cb9-42eb-bde2-8bd1346e9ad5) ![image](https://github.com/freda1874/react.dev/assets/85437054/95637e6a-e661-46cd-8918-2253f897bb6e)

#### How to Play

- The game starts with an empty 3x3 grid.
- Players take turns clicking on an empty square to make a move.
- The first player to align three of their marks (X or O) vertically, horizontally, or diagonally wins.
- Use the move list below the game board to jump to a previous move at any time, altering the course of the game.
  
#### App Features
This game is built using React, utilizing `useState` hook for state management across the component tree. Styling is handled using an external stylesheet, `styles.css`.
- Uses a status label to indicate which player's turn it is, switching between 'X' and 'O'.Also **remembers** play records each time. Allows players to revert to any previous game state, effectively "traveling back in time" to reconsider strategies.
- Automatically announces a winner if a player gets three marks in a row.
- Highlights the squares that form a winning line   

#### Setup and Installation

1. **Clone the Repository**
   - Open your terminal and clone this repository using the command:
     ```
     git clone <repository-url>
     ```
   - Replace `<repository-url>` with the actual URL of the repository.

2. **Navigate to the Project Directory**
   - Change directory to the project:
     ```
     cd tic-tac-toe-react
     ```

3. **Install Dependencies**
   - Run the following command to install the necessary dependencies:
     ```
     npm install
     ```

4. **Run the Application**
   - Start the development server using:
     ```
     npm start
     ```
   - This command runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser. The page will reload if you make edits.

 
Created with CodeSandbox, 
tutotial from https://react.dev/learn/tutorial-tic-tac-toe 
