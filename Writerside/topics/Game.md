# Game
## Data
### Board  
  + This Will be represented by a map of key value pairs.  
  + The key is a tuple containing board coordinates {letter, number}
  + The value will be a tuple represent what is on the board, if anything.{colour, piece}

Atom Values for pieces  
[:knight, :king, :pawn, :bishop, :rook, :queen, :empty]

Atom Values for colours  
[:black, :white]
    
### Move
+ This will be a struct
+ the struct will be {turn, player, piece moved, move location, gametime, turntime}
### Moves
A list of Move maps

### Piece rules
A list containing rules for what a piece can and cannot do.  
These rules are functions