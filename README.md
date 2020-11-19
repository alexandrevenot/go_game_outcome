# GO game outcome

We get 41563 go game boards in json format, and for each board we know the blacks winrate on 100 games starting with that board.
This code creates a neural network that learns on this dataset, and gets a 0.05 MSE when tested on new boards.
