# **AI-Driven Flappy Bird**

This project is an AI-powered version of the classic *Flappy Bird* game, utilizing the NEAT (NeuroEvolution of Augmenting Topologies) algorithm to train artificial intelligence agents to play the game. The birds are controlled by neural networks that evolve over generations through a genetic algorithm, allowing them to improve their performance as they "learn" to navigate pipes and avoid obstacles.

## **Project Overview**
In this project, the AI uses a genetic algorithm (NEAT) to control a bird in the *Flappy Bird* game. The bird's objective is to fly between pipes without colliding with them or touching the ground. The game gets progressively more difficult as the bird learns to avoid obstacles and score higher.

Key features include:
- **Neural Network Evolution**: The bird’s brain evolves over multiple generations.
- **Game Simulation**: Simulates the classic *Flappy Bird* game with realistic physics and graphics.
- **Dynamic Training**: Birds’ fitness scores are adjusted based on their ability to survive and avoid pipes.
- **Visual Debugging**: Displays lines that show the distance from the bird to upcoming pipes in real-time.

## **Features**
- 🐦 **Neural Network-based AI**: The bird's flight is controlled by a neural network that evolves over time.
- 🧬 **Genetic Algorithm (NEAT)**: Birds "learn" through the NEAT algorithm, with fitness based on their ability to navigate obstacles.
- 🔄 **Dynamic Pipe Movement**: Pipes move towards the bird, creating a progressively difficult challenge.
- 🎮 **Interactive Game Environment**: Developed using Pygame for a smooth and interactive game experience.
- 🌱 **AI Training**: The bird’s neural network trains with each generation, improving as it learns from past attempts.

## **How It Works**
1. The bird is controlled by a neural network, which determines whether the bird should jump or fall.
2. The NEAT algorithm trains the neural networks over generations, selecting birds with higher fitness scores to reproduce.
3. The bird’s fitness is calculated based on how long it survives and how far it progresses.
4. The game environment includes pipes that the bird must navigate without colliding with them.

## **Installation**
To run the project locally:

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/AI-Driven-Flappy-Bird.git
    cd AI-Driven-Flappy-Bird
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the game:
    ```bash
    python main.py
    ```

## **Technologies Used**
- 🐍 **Python 3.x**
- 🎮 **Pygame** for game development
- 🧠 **NEAT (neat-python)** for evolving neural networks

## **Contributing**
Feel free to fork the project, submit issues, or create pull requests if you'd like to contribute to its development.

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Enjoy playing the AI-powered Flappy Bird! 🚀**
