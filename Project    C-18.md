#                                                Project    C-18

## Bug No. 1:-

*trex  is not colliding the invisibleground.*

## The code by which I fixed the  bug:-

`trex.collide(invisibleground);`

## Bug No. 2:-

the y position  of  the trex  required for jumping was very high.

## The code by which I fixed the bug:-

`if(keyDown(space) && trex.y >=  170){`

`trex.velocityY = -12`

### `}`

## Bug No.3:-

## The game is reseting as I am pressing space key

## The code by which I fixed the bug:-

`if(gameState === END && mousePressedOver(reset)){`

`reset();`

`}`