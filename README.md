
## 🎯Minimax Agent: Checkers

Design an agent using the **Minimax algorithm** capable of playing the game 
of Checkers.

**Game Rules:**
- Played on an 8×8 board between two players, each starting with 12 pieces
- Pieces move diagonally, forward only, into an adjacent empty square
- **Capturing:** if an opponent's piece is diagonally adjacent with an empty 
  square right behind it, the player can jump over and capture it
- Multiple sequential jumps are allowed in the same turn if available
- **Kinging:** a piece reaching the opposite end row becomes a King, which 
  can move diagonally both forward and backward
- **Win condition:** a player wins when the opponent has no pieces left or 
  no legal moves remain
- ⚠️ **Key rule difference from standard Checkers:** capturing is **not 
  mandatory** in this project (unlike most official Checkers variants)

