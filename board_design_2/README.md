# Musketeer Chess Board Design 2
An attempt to create a board design for musketeer chess variant.

The game rules:  
* [Musketeer Chess link 1 official site](https://musketeerchess.net/games/musketeer/rules/rules-short.php)
* [Musketeer Chess link 2 official site](https://musketeerchess.net/site/game-rules/)
* [Musketeer Chess Github](https://github.com/fsmosca/musketeer-chess#j-example-game)

## A. Boards

### Board 1
This is the initial board. The pieces in columns w and z are the available musketeer piece types where each player can choose.  

#### Game Phases
* Piece selection  
  * All pieces selected will enter the green boxes
* Gating preparation  
  * All pieces from green boxes will enter the yellow boxes
* Normal chess game phase

![initial_board](https://i.imgur.com/TU9LWsT.png)

***

### Board 2
White played its first move, selected an Archbishop. This is the beginning of the piece selection phase.   
`1. z9y9 or Az9y9 or Ay9`

![board2](https://i.imgur.com/sojBtM1.png)

***

### Board 3
Black selected an Elephant.  
`1... w5x5 or Ew5x5 or Ex5`

![board3](https://i.imgur.com/5zAjFEO.png)

***

### Board 4
White selected the piece that was selected by black in the 1st move. This is forced. Can be executed automatically by a GUI.  
`2. `

`![board4](https://i.imgur.com/FYcpjDT.png)`

***

### Board 5
Black selected the piece that was selected by white in the 1st move. This is forced. Can be executed automatically by a GUI. This completes the piece selection phase.  
`2... `

`![board5](https://i.imgur.com/tnOHOdx.png)`

***

### Board 6
White played its Archbishop to rank 0. This is the beginning of gating preparation phase.  
`3. `

`![board6](https://i.imgur.com/4eaaoPI.png)`

***

### Board 7
Black played its Archbishop to rank 9.  
`3... `

`![board7](https://i.imgur.com/FEKVzCe.png)`

***

### Board 8
White played its Elephant to rank 0.  
`4. `

`![board7](https://i.imgur.com/kfkbVJX.png)`

***

### Board 9
Black played its Elephant to rank 9. This completes the gating preparation phase.  
`4... `

`![board7](https://i.imgur.com/QXOr7ER.png)`

***

## B. Credits
* [Board Painter](https://github.com/jcfrog/board-painter)
* [Musketeer Chess](https://musketeerchess.net/tools/boardpainter/index.php)
* [imgur](https://imgur.com/)
* [GreenShot](https://getgreenshot.org/help/)
