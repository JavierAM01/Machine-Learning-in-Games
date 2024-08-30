[Repository in Progress]

Library of Games and Learning Algorithms. It contains three main sections:

1) **Video Game Development.** Creation of video games for general user enjoyment.
2) **Simple Solving Algorithms.** In this section, we develop basic algorithms to solve and beat games, such as binary search, tree search, and expert systems (case distinction).
3) **Machine Learning Algorithms.** In this section, we apply more advanced techniques, although they are not always the best option, such as machine learning, deep learning, and genetic algorithms.

# Table of Contents

1. [Video Game Development](#id1)
   - [Snake](#id1.1)
   - [Tic-Tac-Toe](#id1.2)
   - [Sudoku](#id1.3)
   - [Flappy Bird](#id1.4)
   - [Chess](#id1.5)
   - [Maze](#id1.6)
   - [Arkanoid](#id1.7)

2. [Simple Solving Algorithms](#id2)
   - [Sudoku](#id2.1)
   - [Shortest Path Search](#id2.2)

3. [Machine Learning Algorithms](#id3)
   - [Genetic Algorithm - Flappy Bird](#id3.1)
   - [Introduction to Different AI Models - Tic-Tac-Toe](#id3.2)

# Video Game Development <a name=id1> </a>

|              Preview             |     Link     |
|--------------------------------------------------------------------|--------------| 
<a name=id1.1> </a>
| <image src="/images/snake.gif" width="250" height="250">    |  </p> <p align="center"> [Snake](https://github.com/JavierAM01/Juego-Snake) </p> | 
<a name=id1.2> </a>
| <image src="/images/3enraya.gif" width="250" height="250">  |  </p> <p align="center"> [Tic-Tac-Toe](https://github.com/JavierAM01/Juego-3enRaya) </p> |
<a name=id1.3> </a>
| <image src="/images/sudoku.gif" width="250" height="250">   |  </p> <p align="center"> [Sudoku](https://github.com/JavierAM01/Juego-Sudoku) </p> |
<a name=id1.4> </a>
| <p align="center"><image src="/images/flappybird.gif" height="250"></p>| </p> <p align="center"> [Flappy Bird](https://github.com/JavierAM01/Juego-FlappyBird) </p> |
<a name=id1.5> </a>
| <image src="/images/ajedrez.gif" width="250" height="250">  |  </p> <p align="center"> [Chess](https://github.com/JavierAM01/Juego-Ajedrez) </p> |
<a name=id1.6> </a>
| <image src="/images/laberinto.gif" width="250" height="250">|  </p> <p align="center"> [Maze](https://github.com/JavierAM01/Juego-Laberinto) </p> |
<a name=id1.7> </a>
| <image src="/images/arkanoid.gif" width="250" height="250"> |  </p> <p align="center"> [Arkanoid](https://github.com/JavierAM01/Juego-Arkanoid) </p> |

</p> <p align="center">  </p>

# Simple Solving Algorithms <a name=id2> </a>

## Sudoku <a name=id2.1> </a>

|                  Preview                |    Algorithm     |
|-----------------------------------------|------------------|
| <image src="/images/sudoku.gif" width="250" height="250"> | The Sudoku solving algorithm uses recursion to solve this challenging puzzle. The main idea is to break down the problem into smaller sub-problems and solve them recursively. The algorithm looks for an empty cell on the board and tries different numbers from 1 to 9, checking if they follow Sudoku rules. If a valid solution is found, it moves on to the next empty cell and repeats the process. If no valid solution is found, it backtracks and tries another number. This process continues until all cells are filled or a complete solution is found. Recursion efficiently explores all possible number combinations. <p align="center"><a href=https://github.com/JavierAM01/Juego-Sudoku> view code </a></p> |
| <image src="/images/sudoku-2.png" width="250" height="250"> | In this repository, I present a more human-like version of the Sudoku solving algorithm. Instead of relying solely on recursion, this version uses different techniques to find possibilities for each empty cell based on the rows, columns, and blocks on the board. A meticulous approach is used to explore different strategies to reduce options and make informed decisions at each step. Additionally, more advanced methods are incorporated to identify patterns and make logical inferences. This new implementation provides a perspective closer to how humans solve Sudokus, offering an interesting insight into game-solving techniques. <p>The code is written in Haskell, so the graphics are more primitive.</p> <p align="center"><a href=https://github.com/JavierAM01/Juego-Sudoku-2> view code </a></p> |

## Shortest Path Search <a name=id2.2> </a>

|                  Preview                |    Algorithm     |
|-----------------------------------------|------------------|
| <image src="/images/algo1.gif" width="250" height="250"> | [Dijkstra's Algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm). Dijkstra's algorithm is a shortest path search algorithm for a weighted graph. It is used to find the shortest route from a source node to all other nodes in a directed or undirected graph. It works by assigning a provisional distance to each node and updating these distances as the graph is explored, always selecting the node with the smallest provisional distance until reaching the destination node or all nodes reachable from the source node. <p align="center"><a href=https://github.com/JavierAM01/Juego-ShortestPath> view code </a></p> |
| <img src="/images/algo2.gif" width="250" height="250"> | Modification of Dijkstra's algorithm. This modification adds the consideration that the shortest path between two points is a straight line, thus shortening the search in some cases. <p align="center"><a href=https://github.com/JavierAM01/Juego-ShortestPath> view code </a></p> |

# Machine Learning Algorithms <a name=id3> </a>

## AIGym - CartPole

|                  Preview                |    Algorithm     |
|-----------------------------------------|------------------|
| <img src="/images/ai/CartPole.gif" height="250" width="250"> | The CartPole environment is a classic challenge in reinforcement learning, where the goal is to balance a pole on a cart by applying discrete actions. In this repository, you'll find different approaches to solving this problem using algorithms such as Q-Learning, Deep Q-Networks (DQN), Policy Gradient, among others. <p align="center"><a href=https://github.com/JavierAM01/AIGym-CartPole> view code </a></p> |

## Genetic Algorithm - Flappy Bird <a name=id3.1> </a>

|                  Preview                |    Algorithm     |
|-----------------------------------------|------------------|
| <img src="/images/ai/flappybird.gif" height="300" width="170"> | In this project, we explore the powerful application of a genetic algorithm to solve the challenging game Flappy Bird. By representing the birds as individuals in a population and applying genetic operators like selection, crossover, and mutation, we aim to find the optimal combination of traits and behaviors that maximize the ability to avoid obstacles and achieve high scores. Through iterative optimization based on fitness evaluation and generational evolution, the genetic algorithm converges towards increasingly better solutions. Discover how this mathematical technique allows us to tackle complex problems and achieve impressive results in the context of Flappy Bird. <p align="center"><a href=https://github.com/JavierAM01/AlgoritmoGenetico-FlappyBird> view code </a></p> |

## Introduction to Different AI Models - Tic-Tac-Toe <a name=id3.2> </a>

|                  Preview                |    Algorithm     |
|-----------------------------------------|------------------|
| <img src="https://github.com/JavierAM01/Introduction-to-different-AI-models/blob/main/images/MCTS/winner.gif" height="300" width="250"> | <p>In this repository, we conduct a comparison of three types of algorithms:</p> <p> 1) Neural Networks,</p> <p> 2) Reinforcement Learning,</p> <p> 3) Monte Carlo Tree Search.</p> <p>To this end, we created a model for each of them and trained them to play Tic-Tac-Toe. Through this comparison, we aim to analyze and evaluate the performance and capabilities of each algorithm in solving this strategic challenge.</p> <p align="center"><a href=https://github.com/JavierAM01/Introduction-to-different-AI-models> view code </a></p> |
