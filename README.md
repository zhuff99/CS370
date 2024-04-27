# CS370

Current/Emerging Trends in CS

This class was based on AI and machine learning. Most assignments were conducted using Python and Jupyter notebook (.ipynb).

Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?
For the final project we were to add code to the TreasureMaze.ipynb file. The two other python files and the rest of the code
in the TreasureMaze file were written by SNHU. The only code that was inputed by me was under the sudo code outline. 



The code was designed to:
    #    Reset the maze with agent set to above position
    #    envstate = Environment.current_state
    #    While state is not game over:
    #        previous_envstate = envstate
    #        Action = randomly choose action (left, right, up, down) either by exploration or by exploitation
    #        envstate, reward, game_status = qmaze.act(action)
    #        episode = [previous_envstate, action, reward, envstate, game_status]
    #        Store episode in Experience replay object
    #        Train neural network model and evaluate loss
    #    If the win rate is above the threshold and the model passes a completion check, this is our epoch.
