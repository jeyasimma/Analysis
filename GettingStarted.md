### Chess Game Project Documentation

This repository provides a chess game implementation using chess.js and chessboard.js. 
Below is a structured overview of the key functions and their usage, as if they were API endpoints.

##Table of Contents
  -[Start New Game](#StartNewGame)
  -[Handle Player Move](#HandlePlayerMove)
  -[Get Game Status](#GetGameStatus)
  -[Engine Move](#EngineMove)
  -[Highlight Check](#HighlightCheck)
  -[Remove Highlights](#RemoveHighlights)
  -[Show Game Over](#ShowGameOver)
  -[Color Selection](#ColorSelection)
  -[Resize Board](#ResizeBoard)
  -[Libraries Used](#LibrariesUsed)

# Start New Game

Function: startNewGame()
Resets the game board and initializes a new game.
If the user selects Black, the engine makes the first move.
Usage:
``startNewGame();

Effect:
Resets the board to the starting position.
Updates the game status.
