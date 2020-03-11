# Gym-Retro-Examples
Code from a presentation I did over RL Learning with Gym Retro. Very basic examples.

There are 3 examples included in Jupyter Notebooks via Google Colab:
1. Random Agent
2. [Brute Force Agent](https://github.com/openai/retro/blob/master/retro/examples/brute.py)
3. [DQN Agent](https://github.com/philtabor/Youtube-Code-Repository/blob/master/ReinforcementLearning/DeepQLearning/dqn_keras.py)

Brute Force and DQN algorithms link above to the repositories for the algorithms I used for Brute Force and DQN. Changes were made so code is not a 1:1 copy but should still mostly be the same.

# Notes
If not using Google Colab you will probably need to install Gym similar to the way Gym Retro was installed using pip.
Rom files are not included due to copyright concerns. You need to provide your own. The ones I used are:
1. Joust (USA).nes
2. Ms. Pac-Man (USA).nes
3. Space Invaders (Japan).nes
4. Super Mario Bros. (World).nes

DQN takes a lot of ram. 50000 memory size with 4 staked frames converted to grayscale and downsampled 2X still takes approximately 22 GB!
It also took about 8ish hours to train 250 games on Super Mario and 5ish hours to train 250 games on Ms. Pacman and they both still need more training. If using Google Colab remember that they limit you to approximately 12 hours for GPU backend. Colab might also disconnect the environemnt earlier if tab is not active.
