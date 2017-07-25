# Connect-4-game
## Step 1: Breaking up the application into components
    A component that represents a 
        circle
        grid cell
        row of cells
        game board
    A section that displays the game messages
    A section with a restart button
## Step 2: Creating the individual components
    function Circle(){}
    function Cell(){}
    function Row(){}
    function Board(){}
    function Game(){}
## Step 3: Adding game state
    The state should keep track of the following:
    Which player's turn it is 
        (true for black, false for red)
    Which grid cell's have pieces and what color those pieces should be 
        (0 for empty, 1 for black, 2 for red)
    Which player has won 
        ( 0 for no one, 1 for black, 2 for red)
    The empty grid can be represented by a 2-D array. 
    
    The 2-D array consists of an array that has 6 indexes that each have 7 indexes.
## Step 4: Passing State down
## Step 5: Adding functionality to alternate player
## Step 6: Adding functionality to force pieces to drop all the way down
## Step 7: Adding victory detection