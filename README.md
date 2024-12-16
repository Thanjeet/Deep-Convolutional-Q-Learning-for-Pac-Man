# Deep Convolutional Q-Learning for Pac-Man
This repository implements Deep Convolutional Q-Learning (DCQN) to train an agent to play the classic Pac-Man game. 
DCQN is a powerful technique that leverages convolutional neural networks to process visual input and learn optimal policies.

## Code Structure
The code is organized into three main parts:

### 1. Building the AI:

Defines the convolutional neural network architecture.
The network takes the preprocessed game frames as input and outputs Q-values for each possible action.
### 2. Training the AI:

Sets up the Pac-Man environment using gym and ale_py.
Initializes hyperparameters like learning rate, discount factor, and exploration rate.
Implements a replay buffer to store experiences for training.
Defines the DQN agent class:
Contains the local and target Q-networks.
Implements functions for acting, learning, and updating the target network.
Trains the agent using the DQN algorithm.
### 3. Visualizing the Results:

Saves a video of the trained agent playing Pac-Man.
## Running the Code
### Install Dependencies: 
Ensure you have the following libraries installed:

Bash

pip install gym ale-py torch numpy
### Train the Agent: 
Run the provided Python script to start the training process. This may take several hours or even days, depending on your hardware and hyperparameter settings.
### Visualize the Results: 
After training, the script will save a video of the agent playing the game.
