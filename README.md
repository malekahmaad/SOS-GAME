This game has 5 files:

1- SOS.py: this file is the main game file, it contains the SOS game class with all the function it needs.

2- SOS_AI.py: this file is the AI player file, it contains the MCTS player classes, PUCT player classes and the network that is needed for the PUCT algorithm.

3- trainer.py: this file is the MCTS trainer, the MCTS player plays against itself number of games and it trains the neural network for every game it plays.

4- PUCT_trainer.py: this file is the PUCT trainer, the PUCT player plays against itself number of games and it trains the neural network for every game it plays.

5- player.py: this file contains three functions to play the game, it gives the ability to play against a player, AI (MCTS) and strong AI (PUCT)

------------------------------------------------------------------------------------------------------------------------
To try the game you need to do this:

1- go to the player.py file and choose which player function to run.

2- go to the terminal and write this line: python player.py.

NOTE: if you want to play against the PUCT player you need to run the two trainers to train the neural network (when you see this file "SOS.weights.h5" then you ca play against the strong AI).
