# snhu-pirate-intelligence
Project Two - AI Pirate Intelligence 

# Overview

This project involved developing a pirate intelligent agent capable of navigating a maze to find treasure using deep Q-learning. The agent's goal was to optimize its path through the maze while maximizing its rewards based on a reinforcement learning algorithm. The project demonstrates the application of key concepts in reinforcement learning and neural networks to a practical problem.

# Project Work
## Provided Code
For this project, I was given the following code:
- Environment Setup: The `TreasureMaze.py` class represented the environment, defining the maze matrix and managing the state of the game, including rewards and penalties based on the pirate's actions.
- Experience Replay: The `GameExperience.py` class stored the episodes during training, helping the agent learn by replaying past experiences.
- Model Building: The code to build a neural network model, which included layers, activation functions, optimizers, and loss functions, was provided as a foundation for training the agent.

### Code I Created

I developed the deep Q-learning algorithm to train the pirate agent. This included:
- Implementing the logic for the Q-training algorithm to help the agent learn the optimal path to the treasure.
- Adjusting parameters such as exploration rate and memory size to ensure the agent balanced exploration and exploitation during training.
- Running simulations to train the model over several epochs and verifying that the agent achieved a consistent 100% win rate.

## Reflection on Learning and Its Connection to Computer Science

### What Do Computer Scientists Do and Why Does It Matter?
Computer scientists solve complex problems by designing algorithms and systems that can automate tasks, process data, and make decisions. This work is cruicial because it drives innovation across industries, from developing intelligent systems like the pirate agent in this project to creating software that powers critical infrastucture.

### How Do I Approach a Problem as a Computer Scientists?
Approaching a problem as a computer scientist involves breaking down the problem into smaller, manageable parts, developing algorithms to solve each part, and the integrating these solutions into a functional system. In this project, I tackled the problem by first understanding the environment and provided tools, then focused on implementing and refining the Q-learning algorithm to meet the goal of navigating the maze.

### What Are My Ethical Responsibilities to the End User and the Organization?
As a computer scientist, my ethical responsibilities include ensuring that the systems I develop are safe, secure, and do not cause harm to users and society. This involves protecting user data, preventing biases in algorithms, and being transparent about the capabilities and limitations of the technology. In this project, while ethical concerns were less pronounced, they would be critical if this AI were applied in a real-world context, such as ensuring fairness in decision-making processes or protecting user data.

## Conclusion
This project has strengthened my understanding of reinforcement learning and its applications in creating intelligent agents. It also reinforced the importance of ethical considerations in computer science, particularly in the development and deployment of AI systems.


