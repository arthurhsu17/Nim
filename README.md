# Nim
Nim is a strategy game that involves two players that take turns removing objects from a pile

## Rules
The only rule of the game is that each player must take at least one object from the same pile, as many as they like, as long it is still available. E.g. if a row has 5 objects, the maxiumum you can take is 5 objects, if you try and take more an error will occur.

## Gameplay
<img width="227" alt="Screenshot 2022-03-21 at 2 34 32 PM" src="https://user-images.githubusercontent.com/71420919/159285370-14365ad9-74b9-4acb-8436-6c0f078b9e2a.png">

The game is simply run by the  `nim` command by after running the program inside GHCI.

The user is given the choices to enter the row number and number of stars to remove.


<img width="227" alt="Screenshot 2022-03-21 at 2 34 47 PM" src="https://user-images.githubusercontent.com/71420919/159285396-ce7e99a5-f648-4357-930b-837b1eedd828.png">

Once chosen by player 1, it is removed from the board and is switched to the next player to make a move.

<img width="205" alt="Screenshot 2022-03-21 at 2 35 05 PM" src="https://user-images.githubusercontent.com/71420919/159285421-05d1ff8c-72fe-48b1-9d15-ec7a2e200efd.png">

Once chosen by player 2, it is switched back to player 1.

<img width="207" alt="Screenshot 2022-03-21 at 2 35 33 PM" src="https://user-images.githubusercontent.com/71420919/159285430-914d6975-fadd-484a-b941-79cb37f8b221.png">

The game ends when there are no more objects to remove, so best to remove objects one at a time and not in the same pile!
