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
White played its first move, selected an Archbishop. This is the beginning of the piece selection phase. The first piece selected would go to rank 1 for white.  
`1. y9y1 or Ay9y1 or Ay1`

![b2](https://i.imgur.com/lLIVRfT.png)

***

### Board 3
Black may reply by selecting the Elephant and put it in rank 7.  
`1... y5x7`

![b3](https://i.imgur.com/Mf6LH6m.png)

***

### Board 4
White will own the Elephant here to complete its piece selections, note this is the piece that was selected by Black. Can be automatically executed by the a GUI.

`2. y5y2`

![b4](https://i.imgur.com/1B9Kbzf.png)

***

### Board 5
Black will own the Archbishop as well to complete its piece selections, note this is the piece that was selected by White. Can be automatically executed by the a GUI. At this point the gray color will turn into white and black color that is the selected pieces of white will be colored white, and that of black will be colored black.

![b5](https://i.imgur.com/N9TUvGm.png)

***



## B. Credits
* [Board Painter](https://github.com/jcfrog/board-painter)
* [Musketeer Chess](https://musketeerchess.net/tools/boardpainter/index.php)
* [imgur](https://imgur.com/)
* [GreenShot](https://getgreenshot.org/help/)
