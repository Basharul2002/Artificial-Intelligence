# 🌟 **Artificial Intelligence**

Welcome to an extensive collection of **Python exercises** designed to enhance your coding skills and deepen your understanding of **data structures**, **algorithms**, and **artificial intelligence**. This repository offers valuable resources for both beginners and experienced programmers alike, covering a wide range of topics from basic Python syntax to advanced search algorithms and genetic algorithms.

---

## 📚 **Table of Contents**
- [🌟 Artificial Intelligence](#-artificial-intelligence)
  - [📚 Table of Contents](#-table-of-contents)
  - [🌟 Introduction](#-introduction)
  - [🔢 Basic Coding & Data Structures](#-basic-coding--data-structures)
  - [📝 Python Basics and Functions](#-python-basics-and-functions)
    - [Topics Covered](#topics-covered)
    - [Example Exercise](#example-exercise)
  - [🤖 Simple & Model-Based Agents](#-simple--model-based-agents)
    - [Smart Home System Use Case](#smart-home-system-use-case)
    - [Agent Description](#agent-description)
    - [List of Sensors](#list-of-sensors)
    - [Sensor Values](#sensor-values)
    - [List of Actions](#list-of-actions)
  - [🔍 Search Simulations (BFS, DFS)](#-search-simulations-bfs-dfs)
    - [Romanian Map Simulation](#romanian-map-simulation)
    - [BFS Simulation](#bfs-simulation)
    - [DFS Simulation](#dfs-simulation)
    - [Visual Representation](#visual-representation)
  - [🔍 Search Algorithms (UCS, GBFS, A* Algorithms)](#-search-algorithms-ucs-gbfs-a-algorithms)
    - [UCS Example](#ucs-example)
    - [GBFS Example](#gbfs-example)
    - [A* Example](#a-example)
  - [🧬 Genetic Algorithm](#-genetic-algorithm)
    - [Introduction to Genetic Algorithms](#introduction-to-genetic-algorithms)
    - [Components of Genetic Algorithms](#components-of-genetic-algorithms)
    - [Example Problem](#example-problem)
  - [📞 Contact](#-contact)

---

## 🌟 **Introduction**

This collection is designed to guide you through a comprehensive journey in **Python programming**. Each section contains practical exercises, detailed explanations, and visual representations to reinforce your learning.

---

## 🔢 **Basic Coding & Data Structures**

*File Name:* **1) Basic Coding & Data Structures Exercises.ipynb**

In this section, you'll explore foundational Python exercises that cover essential topics, including:

- **Numeric Operations**
- **Object Types**
- **String Operations**
- **Lists, Stacks, and Queues**
- **Dictionaries**

These exercises will help you establish a strong foundation in Python and master basic data structures.

[🔗 View Notebook](https://github.com/Basharul2002/AI/blob/main/1.%20Basic%20Coding%20%26%20Data%20Structures%20Exercises.ipynb)

---

## 📝 **Python Basics and Functions**

*File Name:* **2) Python_Basics_and_Functions_Exercises.ipynb**

This notebook serves as an introduction to core Python concepts, offering exercises that reinforce fundamental programming skills. Perfect for newcomers or those looking to refresh their knowledge.

### Topics Covered

1. **User Input:** Learn to interact with users by receiving input, processing it, and displaying results.
2. **if Statements:** Explore decision-making logic to alter your code's behavior based on conditions.
3. **for Statements:** Master looping constructs to efficiently iterate over data and perform repetitive tasks.
4. **Functions:** Understand how to create reusable code blocks, enhancing modularity and maintainability.
5. **Output Formatting (Optional):** Refine result presentation with formatted output for clarity and precision.

### Example Exercise

One of the exercises focuses on calculating the area of a circle based on user-provided input, introducing the concepts of validation and formatted output.

[🔗 View Notebook](https://github.com/Basharul2002/AI/blob/main/2.%20Python_Basics_and_Functions_Exercises.ipynb)

---

## 🤖 **Simple & Model-Based Agents**

*File Name:* **3) Agent(Simple, Model Based).ipynb**

In this notebook, we explore the foundational concepts of agents in **Artificial Intelligence**, focusing on two primary types of agents:

- **Simple Reflex Agents:** These agents act based solely on current percepts, without memory of past states.
- **Model-Based Agents:** These agents enhance decision-making by considering historical data and previous states.

### Smart Home System Use Case

A practical example illustrates a **Smart Home System** where a camera detects an approaching individual and performs facial recognition. Recognized faces automatically unlock the door, while unrecognized ones alert the homeowner. The system also activates an alarm in case of forced entry and allows access via a PIN or physical key.

#### Agent Description

**Objective:** Secure access to the home by unlocking the door for recognized faces or valid PINs and locking it afterward.

#### List of Sensors

- **Motion Detector**
- **Camera**
- **Keypad**
- **Pressure Sensor**
- **Padlock**

#### Sensor Values

- **Motion:** {Detected, Not Detected}
- **Camera Status:** {ON, OFF}
- **Face Status:** {Recognized, Not Recognized}
- **PIN Entry Status:** {Correct, Incorrect}
- **Physical Key Status:** {Correct, Incorrect}
- **Owner Decision:** {Granted, Denied}

#### List of Actions

- **Camera ON**
- **Camera OFF**
- **Door ON**
- **Door OFF**
- **Alarm OFF**
- **Door Open**
- **Door Lock**

### Agent Functionality

The agent operates based on a perception-to-action model, dynamically responding to various inputs and situations to manage door access effectively.

### Agent Types Discussed

- **Table-Driven Agent:** Utilizes a predefined action table based on perceptions.
- **Simple Reflex Agent:** Responds directly to current percepts without considering history.
- **Model-Based Agent:** Makes informed decisions by incorporating past states.

[🔗 View Notebook](https://github.com/Basharul2002/AI/blob/main/3.%20Agent(Simple%2C%20Model%20Based).ipynb)

---

## 🔍 **Search Simulations (BFS, DFS)**

*File Name:* **4) Search Simulations(BFS, DFS).ipynb**

Explore classic search algorithms through simulations of:

- **Breadth-First Search (BFS):** Traverse through a graph level by level.
- **Depth-First Search (DFS):** Dive deep into the graph recursively.

This notebook provides an in-depth look at how these search strategies work and their applications.

### Romanian Map Simulation

This section illustrates the search algorithms using a simplified road map of Romania, showcasing road distances in miles.

*Map Overview:*

| **Node**      | **Connections**                                            |
|---------------|-----------------------------------------------------------|
| **Arad**      | Sibiu (140), Zerind (75), Timisoara (118)                |
| **Zerind**    | Arad (75), Oradea (71)                                   |
| **Oradea**    | Zerind (71), Sibiu (151)                                 |
| **Sibiu**     | Arad (140), Oradea (151), Fagaras (99), Rimnicu (80)    |
| **Timisoara** | Arad (118), Lugoj (111)                                   |
| **Lugoj**     | Timisoara (111), Mehadia (70)                            |
| **Mehadia**   | Lugoj (70), Drobeta (75)                                 |
| **Drobeta**   | Mehadia (75), Craiova (120)                              |
| **Craiova**   | Drobeta (120), Rimnicu (146), Pitesti (138)             |
| **Rimnicu**   | Sibiu (80), Craiova (146), Pitesti (97)                 |
| **Fagaras**   | Sibiu (99), Bucharest (211)                              |
| **Pitesti**   | Rimnicu (97), Craiova (138), Bucharest (101)            |
| **Bucharest** | Fagaras (211), Pitesti (101), Giurgiu (90), Urziceni (85)|
| **Giurgiu**   | Bucharest (90)                                          |
| **Urziceni**  | Bucharest (85), Vaslui (142), Hirsova (98)               |
| **Hirsova**   | Urziceni (98), Eforie (86)                               |
| **Eforie**    | Hirsova (86)                                            |
| **Vaslui**    | Iasi (92), Urziceni (142)                                |
| **Iasi**      | Vaslui (92), Neamt (87)                                  |
| **Neamt**     | Iasi (87)                                               |

### BFS Simulation

**Overview:**
- BFS reaches states by exploring nodes level by level, ensuring that no better path can be found once a state is reached.
- Early goal testing is employed as soon as a node is generated.

**Example:**
- **Start Node:** Arad
- **Goal Node:** Bucharest
- **Path Found

:** Arad -> Sibiu -> Fagaras -> Bucharest

### DFS Simulation

**Overview:**
- DFS explores as far down a branch as possible before backtracking.
- While it may not guarantee the shortest path, it is useful in certain scenarios.

**Example:**
- **Start Node:** Arad
- **Goal Node:** Bucharest
- **Path Found:** Arad -> Timisoara -> Lugoj -> Mehadia -> Drobeta -> Craiova -> Rimnicu -> Pitesti -> Bucharest

### Visual Representation

- **BFS Tree Representation:** Shows the order of node expansions.
- **DFS Tree Representation:** Displays how deep the search goes before backtracking.

---

## 🔍 **Search Algorithms (UCS, GBFS, A* Algorithms)**

*File Name:* **5) Search Algorithms (UCS, GBFS, A*).ipynb**

This section delves into more advanced search algorithms, including **Uniform Cost Search (UCS)**, **Greedy Best-First Search (GBFS)**, and **A* Search**.

### UCS Example

- **Optimal for:** Finding the least-cost path in weighted graphs.
- **Mechanism:** Expands the least cost node until the goal is reached.

### GBFS Example

- **Optimal for:** Searching based on heuristic estimations.
- **Mechanism:** Expands nodes based on the lowest heuristic cost.

### A* Example

- **Optimal for:** Finding the least-cost path by combining cost and heuristic estimates.
- **Mechanism:** Evaluates nodes using both path cost and heuristic to ensure optimal search.

---

## 🧬 **Genetic Algorithm**

*File Name:* **6) Genetic Algorithm.ipynb**

This notebook provides insights into **Genetic Algorithms** —a powerful optimization technique inspired by natural evolution.

### Introduction to Genetic Algorithms

Genetic Algorithms simulate the process of natural selection to solve optimization problems by evolving solutions over generations.

### Components of Genetic Algorithms

1. **Population:** A group of potential solutions.
2. **Fitness Function:** Evaluates how well each solution solves the problem.
3. **Selection:** Chooses the best solutions for reproduction.
4. **Crossover:** Combines parts of two parent solutions to create offspring.
5. **Mutation:** Introduces random changes to solutions for diversity.

### Example Problem

An example problem explores optimizing a function using a genetic algorithm, demonstrating how solutions evolve over generations.

[🔗 View Notebook](https://github.com/Basharul2002/AI/blob/main/6.%20Genetic%20Algorithm.ipynb)

---

## 📞 **Contact**

For any inquiries or feedback, please feel free to reach out to me at:

- **Email:** basharul2002@gmail.com
- **GitHub:** [Basharul2002](https://github.com/Basharul2002)

---
