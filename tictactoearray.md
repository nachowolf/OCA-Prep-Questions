# Tic Tac Toe Array

### You're playing X's and O's with your friend and you are the X.

![xoxo](https://nachowolf.github.io/OCA-Prep-Questions/resources/images/tictactoe.PNG)


```
public class TicTacToeArray{

    public static void main(String[] args){
        char[][] grid = new char[3][3];
        grid[0][0] = 'X';
        grid[2][1] = 'O';
        grid[2][2] = 'X';
        grid[1][1] = 'O';
        grid[2][0] = 'X';
        grid[0][2] = 'O';

    // insert line of code here!

    }
}
```
### Which line of code below will complete the line of X's so that you win the game?

* A.  grid[0][1] = 'X';
* B.  grid[1][0] = 'X';
* C.  grid[1][2] = 'O';
* D.  grid[1][1] = 'O';
* E.  grid[3][1] = 'X';