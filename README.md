# tic-tac-toe
Single-payer, text-based


I went through the hassle of creating a system that render coordinates for the user to guide their shoot alongside a
board that starts as empty.
As the user chooses a spot, the script replaces the original coordinate with a "blank", which signifies that said spot is
not longer open; and replaces the blank on the board with an "X" ("0" for the pc)

I realized that a couple of lists, nested lists and a nested dictionary where necessary to keep track of the empty spots,
render the board, render the grid of coordinates, and to check if either player or pc has won after every turn.

More details are included in comments inside the code. Feel free to use this code as you please, and
please let me know if you have any note. Thanks.

R.C.
