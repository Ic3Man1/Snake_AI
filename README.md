# Snake Game (Pygame + Reinforcement Learning)

This project is an implementation of the classic Snake game using Python and Pygame,
augmented with a reinforcement learning AI agent that learns to play the game through trial and error.

It was built by following this tutorial:  
[Python + PyTorch + Pygame Reinforcement Learning – Train an AI to Play Snake (YouTube)](https://www.youtube.com/watch?v=L8ypSXwyBds)  
(by freeCodeCamp.org)

## Features

- Snake grows when it eats food
- Game over when the snake hits the wall or itself
- Clean and modular Pygame-based code
- Score tracking
- Deep Q-Learning agent that learns to play using reinforced learning

## How it works

An AI agent is trained using Deep Q-Learning to play the Snake game. When you run the program,
you will observe the agent learning in real-time. At first, the movements may seem random or ineffective, 
but as training continues, the AI gradually learns to survive longer and improve its score. 
This demonstrates how reinforcement learning allows agents to improve through experience.

## How to Run

1. Make sure you have Python 3.7+ installed.
2. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   venv\\Scripts\\activate   # On Windows
   source venv/bin/activate  # On Linux/macOS
