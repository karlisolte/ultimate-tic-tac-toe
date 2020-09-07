# ultimate-tic-tac-toe

## Tactics

X to play at board 5 and win:  
![alt text](https://github.com/karlisolte/ultimate-tic-tac-toe/blob/master/1.png?raw=true)

Winning board loses to (3, 8). The only safe move (5, 3) loses to (3, 5) as X is forced to play (5, 1),
but after (8, 5)! O wins. Solution: immediately giving free move (5, 1)! wins for X.

X to play at board 4 and win:  
![alt text](https://github.com/karlisolte/ultimate-tic-tac-toe/blob/master/2.png?raw=true)  

Winning board loses to (5, 7)! followed by (0, 5).  

O played (6, 0) refusing to win board and giving free move instead. If O played (6, 1), (1, 4)! winds for X.
![alt text](https://github.com/karlisolte/ultimate-tic-tac-toe/blob/master/3.png?raw=true) 

 X to play at board 3 and win:  
![alt text](https://github.com/karlisolte/ultimate-tic-tac-toe/blob/master/4.png?raw=true)  

Two moves only: (3, 0) which gives opponent free move and (3, 6) which forces O to 6 and blocks O from winning board 3.
Yet after (3, 6) - (6, 3) - (3, 0) - (5, 4) we have draw. After (3, 0) - (5, 4) - (6, 8) wins, after (3, 0) - (6, 8) - (5, 4) wins.

X to play at board 4 and draw:  
![alt text](https://github.com/karlisolte/ultimate-tic-tac-toe/blob/master/5.png?raw=true)  

Winning board loses to (0, 1) as O wins also the last board. The only free move (4, 3) loses to (3, 4).
Moves (4, 2), (4, 5), (4, 8) loses to (0, 1) - (3, 4) - (4, 3) as O wins one more board. Drawing line is (4, 6)! - (3, 4) - (4, 3) as X manages to hold board 0 while winning board 4.