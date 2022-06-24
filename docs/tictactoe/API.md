# API
## Class Name: TicTacToe

## Fields

| Name          | Data Type         | Description                         |
|:--------------|:------------------|-------------------------------------|
| Board         | Array of Arrays   | Stores the values in the board      |
| currentPlayer | Integer           | Who is the current Player?          |
| currentValue  | String            | What is the current Value? (X or O) |
| blank (" ")   | String            | Blank String for comparing          |
| X ("X")       | String            | String Letter "X" for comparing     |    
| O ("O")       | String            | String Letter "O" for comparing     |


## Methods - User Interface
Methods used for creating the User Interface

| Name                     | Parameters     | Return Type        | Description                                       |
|:-------------------------|:---------------|--------------------|---------------------------------------------------|
| TicTacToe (Constructor)  | None           | Object (TicTacToe) | Creates an instance of class                      |
| drawBoard                | None           | Void               | Draws the Tic Tac Toe Grid                        |
| UI                       | None           | Void               | Draws the Interface for Input & Grid              |


## Methods - Change Interface
Methods used for changing the User Interface

| Name                     | Parameters                     | Return Type        | Description                                       |
|:-------------------------|:-------------------------------|--------------------|---------------------------------------------------|
| changeCurrentPlayer      | None                           | Void               | Changes the Current Player & value                |
| setX                     | Position (int)                 | Void               | Changes Value from blank to X at given position   |
| setO                     | Position (int)                 | Void               | Changes Value from blank to O at given position   |


## Methods - Helpher Methods for Changing the Interface
Helper Methods used for Main Methods of Changing the Interface

| Name                     | Parameters                     | Return Type        | Description                                       |
|:-------------------------|:-------------------------------|--------------------|---------------------------------------------------|
| currentValue             | Position (int)                 | String             | Returns the corresponding value at given position |
| setValue                 | Position (int), Value (String) | Void               | Sets the given value at given position            |
| remainder                | Dividend (int), Divisior (int) | Integer            | Returns the Remainder of given values             |


## Logical Methods - Checking the Conditions

Main Logic to check if the player is won or game is draw.

| Name                     | Parameters                     | Return Type        | Description                                       |
|:-------------------------|:-------------------------------|--------------------|---------------------------------------------------|
| checkIfWon               | Void                           | Boolean            | Check if the player is won                        |
| checkIfDraw              | Void                           | Boolean            | Check if the game is draw                         |
