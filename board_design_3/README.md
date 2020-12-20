# Musketeer Chess Board Design 3
An attempt to create a board design for musketeer chess variant.

The game rules:  
* [Musketeer Chess link 1 official site](https://musketeerchess.net/games/musketeer/rules/rules-short.php)
* [Musketeer Chess link 2 official site](https://musketeerchess.net/site/game-rules/)
* [Musketeer Chess Github](https://github.com/fsmosca/musketeer-chess#j-example-game)

## A. Boards

### Board 1
This is the initial board. The pieces in columns x and y are the available musketeer piece types where each player can select.

![initial_board](https://i.imgur.com/yV9l0Sh.png)

***

### Board 2
White played its first move, selected an Archbishop. This is the beginning of the piece selection phase.   
`1. j9i9 or Aj9i9 or Ai9`


***

### Board 3
Black selected an Elephant.  
`1... k4i4 or Ek4i4 or Ei4`


***

### Board 4
White selected the piece that was selected by black in the 1st move. This is forced. Can be executed automatically by a GUI.  
`2. j5i5 or Ej5i5 or Ei5`

***

### Board 5
Black selected the piece that was selected by white in the 1st move. This is forced. Can be executed automatically by a GUI. This completes the piece selection phase.  
`2... k0i0 or Ak0i0 or Ai0`


***

### Board 6
White played its Archbishop to rank 0. This is the beginning of gating preparation phase.  
`3. i9f0 or Ai9f0 or Af0`

***

### Board 7
Black played its Archbishop to rank 9.  
`3... i0c9 or Ai0c9 or Ac9`

***

### Board 8
White played its Elephant to rank 0.  
`4. i5d0 or Ei5d0 or Ed0`

***

### Board 9
Black played its Elephant to rank 9. This completes the gating preparation phase.  
`4... i4e9 or Ei4e9 or Ee9`

***

## B. Credits
* [Board Painter](https://github.com/jcfrog/board-painter)
* [Musketeer Chess](https://musketeerchess.net/tools/boardpainter/index.php)
* [imgur](https://imgur.com/)
* [GreenShot](https://getgreenshot.org/help/)
