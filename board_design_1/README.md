# Musketeer Chess Board Design
An attempt to create a board design for musketeer chess variant.

The game rules:  
* [Musketeer Chess link 1 official site](https://musketeerchess.net/games/musketeer/rules/rules-short.php)
* [Musketeer Chess link 2 official site](https://musketeerchess.net/site/game-rules/)
* [Musketeer Chess Github](https://github.com/fsmosca/musketeer-chess#j-example-game)

## A. Board Design 1

### Board 1
This is the initial board. The pieces in columns j and k are the available musketeer piece types where each player can choose.

![initial_board](https://i.imgur.com/wOzDfX0.png)

***

### Board 2
White played its first move, selected an Archbishop. This is the beginning of the piece selection phase.   
`1. j9i9 or Aj9i9 or Ai9`

![board2](https://i.imgur.com/K7DFnxo.png)

***

### Board 3
Black selected an Elephant.  
`1... k4i4 or Ek4i4 or Ei4`

![board3](https://i.imgur.com/uNUPOkr.png)

***

### Board 4
White selected the piece that was selected by black in the 1st move. This is forced. Can be executed automatically by a GUI.  
`2. j5i5 or Ej5i5 or Ei5`

![board4](https://i.imgur.com/FYcpjDT.png)

***

### Board 5
Black selected the piece that was selected by white in the 1st move. This is forced. Can be executed automatically by a GUI. This completes the piece selection phase.  
`2... k0i0 or Ak0i0 or Ai0`

![board5](https://i.imgur.com/tnOHOdx.png)

***

### Board 6
White played its Archbishop to rank 0. This is the beginning of gating preparation phase.  
`3. i9f0 or Ai9f0 or Af0`

![board6](https://i.imgur.com/4eaaoPI.png)

***

### Board 7
Black played its Archbishop to rank 9.  
`3... i0c9 or Ai0c9 or Ac9`

![board7](https://i.imgur.com/FEKVzCe.png)

***

### Board 8
White played its Elephant to rank 0.  
`4. i5d0 or Ei5d0 or Ed0`

![board7](https://i.imgur.com/kfkbVJX.png)

***

### Board 9
Black played its Elephant to rank 9. This completes the gating preparation phase.  
`4... i4e9 or Ei4e9 or Ee9`

![board7](https://i.imgur.com/QXOr7ER.png)

***

## B. Credits
* [Board Painter](https://github.com/jcfrog/board-painter)
* [Musketeer Chess](https://musketeerchess.net/tools/boardpainter/index.php)
* [imgur](https://imgur.com/)
* [GreenShot](https://getgreenshot.org/help/)
