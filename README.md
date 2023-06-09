## number of squares in a chessboard puzzle

#You are provided with a chessboard and are asked to find the number of squares in it. A chessboard is a board with 8 x 8 grids in it .

Solution:
Looking closely at the chessboard we can see that in addition to the 1 x 1 square, there can be a combination of 2 x 2, 3 x 3, 4 x 4, 5 x 5, 6 x 6, 7 x 7, and 8 x 8 squares too. To get the total number of squares we need to find all the squares formed. 
So,
For nxn pattern --> nxn + (n-1)x(n-1)+ ....+ 1x1.

1 x 1: 8 * 8 = 64 squares.

2 x 2: 7 * 7 = 49 squares.

3 x 3: 6 * 6 = 36 squares.

4 x 4: 5 * 5 = 25 squares.

5 x 5: 4 * 4 = 16 squares.

6 x 6: 3 * 3 = 9 squares.

7 x 7: 2 * 2 = 4 squares.

8 x 8: 1 * 1 = 1 square.

Therefore, we have in all = 64 + 49 + 36 + 25 + 16 + 9 + 4 + 1 = 204 squares in a chessboard.
 
