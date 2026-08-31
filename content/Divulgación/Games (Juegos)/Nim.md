Nim is an ancient, world-famous mathematical game of strategy for two players. It is what mathematicians call an "impartial game"—meaning all moves are open to both players, luck plays absolutely zero role, and the game can be completely solved using binary math.

The objective is simple: players take turns removing objects from distinct piles, trying to force a win based on the game's final move.

The most classic configuration of Nim uses **16 objects** (like matches, coins, or pebbles) arranged into **four rows** containing 1, 3, 5, and 7 objects respectively.

1. **The Setup:** The pieces are laid out in a pyramid or distinct piles.
2. **The Move:** On your turn, you must remove **one or more objects** from the board.
3. **The Only Constraint:** You can take as many objects as you want, but they **must all come from the same single row or pile**. You cannot split your turn across multiple rows.


Depending on the pre-agreed rules, Nim is played in one of two formats:

- **Normal Play (Standard):** The player who takes the **very last object** from the board wins.
- **Misère Play:** The player who takes the last object **loses** (you are trying to force your opponent to pick up the very last piece).


In 1901, a mathematician named Charles L. Bouton completely solved the game of Nim by proving that you can always guarantee a win if you convert the number of objects in each row into binary code and add them up using a special method called an exclusive-OR (XOR) addition (also known as the "Nim-Sum").

A game state is considered Safe (Losing) if the Nim-Sum equals zero. If the Nim-Sum is non-zero, the state is Unsafe (Winning) for the active player.

The strategy is simple: if you start on a non-zero layout, you can always make a move that forces the board's sum to zero. By leaving a zero layout for your opponent, no matter what they do on their turn, their move will force the board back into a non-zero state. By repeating this loop, you guarantee victory.

As shown above, the traditional starting layout (1, 3, 5, 7) is a perfectly balanced zero-sum state (000). If you play first against an experienced player from this exact position, you are mathematically guaranteed to lose—unless they make a mistake!





---

