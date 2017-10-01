# Playing 2048 game with an automated bot.
Bot uses Expectimax search with depth of 4 to find the best possible move.
Project is still in progress.During testing it gave the 1024 tile all the time and 2048 tile upto <br />
60% of the games.


# Prerequisites

Game theory ,Minmax,Expectimax

# Files Info

direct.py --> Expectimax implementation(all brainy stuffs in there )<br />
puzzle.py ---> Implementation of game(main file,run this file for demo)<br />
logic.py ----> logic of game progress<br />
merge.py ----->helper file for merging of matrix<br />



## Demo

(after installing the dependencies(requirements.txt))<br />
cd 2048-Ai<br />
$ python puzzle.py

![webp net-resizeimage 2](https://user-images.githubusercontent.com/17298412/31058099-8a9077a4-a70b-11e7-99bb-e55cd540bb6d.png)




## Heuristics

(In file direct.py)
I have used a score and a penalty function.<br />
A configuration Gets a high score if it follows snake line pattern.<br />
Weights are assigned to individual tiles.U can tweek them to get better results.<br />
Penalty is given if u have too many empty tiles.<br />
U can download the game interface from https://github.com/yangshun/2048-python.

## Future work

1.Getting 2048  tiles or more at higher freq.<br />
2.Using Reinforcement learning didn't gave promising results.<br />
  The highest tile it used to get during the game was 128 .</br>
  So still working on improving that model.
  
 ## Refrence
 https://stackoverflow.com/questions/22342854/what-is-the-optimal-algorithm-for-the-game-2048


