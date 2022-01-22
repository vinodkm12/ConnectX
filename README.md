Used in Kaggle Competition ConnectX
Alpha-Beta pruned decision tree engine plus novel evaluation function
Evaluation function uses number of controlled columns as metric
Columns are controlled by whether player has "traps" set up in the columns, 
    which are squares the opponent cannot place into otherwise they will instantly lose.
If a player has a trap in an even numbered square and an odd numbered square in the same column,
    they have endgame control over that column. 
Player seeks to win the game through obvious connect4 points while maximizing total number of traps
    with a higher weight to traps in columns that lead to endgame control. 
