# Dynamic Tic Tac Toe

Is a new take on the normal Tic Tac Toe, with a way to expand this game that we all have been playing for a long time.

Rules of the game.

1. Before start the number of rows and columns have to be selected. (suppose the player have selected r rows and c columns (r and c can be different)
2. The Game is played between 2 player, one will select 'O' and the other will select 'X', and will take turns to select 
	a block in the mesh( the rows and columns we have decided).
3. This will go on till either all the boxes are filled, or one of the players completes the winning condition. 
	

## What is the winning condition

```

That a player is able to mark at-least min(c,r) block in a straight line (could be horizontal/vertical/diagonal)


```



## How to build 

(Note you have to install cmake on your system for this to work

```
# goto any folder where u wish to clone & build
cd C:\DesiredFolder\
git clone https://github.com/aman98sahay/Dynamic-Tic-Tac-Toe.git 

mkdir build 
cd build 
cmake ..
cmake --build .

```