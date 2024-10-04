# 🌟 Artificial Intelligence

Welcome to an extensive collection of **Python exercises** designed to enhance your coding skills and deepen your understanding of **data structures**, **algorithms**, and **artificial intelligence**. This repository offers valuable resources for both beginners and experienced programmers alike, covering a wide range of topics from basic Python syntax to advanced search algorithms and genetic algorithms.

## 📚 Table of Contents

- [🌟 Artificial Intelligence](#-artificial-intelligence)
  - [📚 Table of Contents](#-table-of-contents)
  - [🌟 Introduction](#-introduction)
  - [🔢 Basic Coding \& Data Structures](#-basic-coding--data-structures)
  - [📝 Python Basics and Functions](#-python-basics-and-functions)
    - [Topics Covered](#topics-covered)
    - [Example Exercise](#example-exercise)
  - [🤖 Simple \& Model-Based Agents](#-simple--model-based-agents)
    - [Smart Home System Use Case](#smart-home-system-use-case)
    - [Agent Description](#agent-description)
    - [List of Sensors](#list-of-sensors)
    - [Sensor Values](#sensor-values)
    - [List of Actions](#list-of-actions)
  - [🔍 Search Simulations (BFS, DFS)](#-search-simulations-bfs-dfs)
    - [Search Problem:](#search-problem)
    - [Key Concepts](#key-concepts)
  - [🔍 Search Algorithms (UCS, GBFS, A\* Algorithms)](#-search-algorithms-ucs-gbfs-a-algorithms)
    - [Example Use Case](#example-use-case)
    - [Key Differences](#key-differences)
  - [🧬 Genetic Algorithm](#-genetic-algorithm)
    - [Key Concepts](#key-concepts-1)
  - [📞 Contact](#-contact)

## 🌟 Introduction

This collection is designed to guide you through a comprehensive journey in **Python programming**. Each section contains practical exercises, detailed explanations, and visual representations to reinforce your learning.

## 🔢 Basic Coding & Data Structures

**File Name:** 1) Basic Coding & Data Structures Exercises.ipynb

In this section, you'll explore foundational Python exercises that cover essential topics, including:

- **Numeric Operations**
- **Object Types**
- **String Operations**
- **Lists, Stacks, and Queues**
- **Dictionaries**

These exercises will help you establish a strong foundation in Python and master basic data structures.

[🔗 View Notebook](https://github.com/Basharul2002/AI/blob/main/1.%20Basic%20Coding%20%26%20Data%20Structures%20Exercises.ipynb)

## 📝 Python Basics and Functions

**File Name:** 2) Python_Basics_and_Functions_Exercises.ipynb

This notebook serves as an introduction to core Python concepts, offering exercises that reinforce fundamental programming skills. Perfect for newcomers or those looking to refresh their knowledge.

### Topics Covered

- **User Input:** Learn to interact with users by receiving input, processing it, and displaying results.
- **if Statements:** Explore decision-making logic to alter your code's behavior based on conditions.
- **for Statements:** Master looping constructs to efficiently iterate over data and perform repetitive tasks.
- **Functions:** Understand how to create reusable code blocks, enhancing modularity and maintainability.
- **Output Formatting (Optional):** Refine result presentation with formatted output for clarity and precision.

### Example Exercise

One of the exercises focuses on calculating the area of a circle based on user-provided input, introducing the concepts of validation and formatted output.

[🔗 View Notebook](https://github.com/Basharul2002/AI/blob/main/2.%20Python_Basics_and_Functions_Exercises.ipynb)

## 🤖 Simple & Model-Based Agents

**File Name:** 3) Agent(Simple, Model Based).ipynb

In this notebook, we explore the foundational concepts of agents in **Artificial Intelligence**, focusing on two primary types of agents:

- **Simple Reflex Agents:** These agents act based solely on current percepts, without memory of past states.
- **Model-Based Agents:** These agents enhance decision-making by considering historical data and previous states.

### Smart Home System Use Case

A practical example illustrates a **Smart Home System** where a camera detects an approaching individual and performs facial recognition. Recognized faces automatically unlock the door, while unrecognized ones alert the homeowner. The system also activates an alarm in case of forced entry and allows access via a PIN or physical key.

### Agent Description

**Objective:** Secure access to the home by unlocking the door for recognized faces or valid PINs and locking it afterward.

### List of Sensors

- **Motion Detector**
- **Camera**
- **Keypad**
- **Pressure Sensor**
- **Padlock**

### Sensor Values

- **Motion:** {Detected, Not Detected}
- **Camera Status:** {ON, OFF}
- **Face Status:** {Recognized, Not Recognized}
- **PIN Entry Status:** {Correct, Incorrect}
- **Physical Key Status:** {Correct, Incorrect}
- **Owner Decision:** {Granted, Denied}

### List of Actions

- **Camera ON**
- **Camera OFF**
- **Door ON**
- **Door OFF**
- **Alarm ON**
- **Alarm OFF**

[🔗 View Notebook](https://github.com/Basharul2002/AI/blob/main/3.%20Agent(Simple,%20Model%20Based).ipynb)

## 🔍 Search Simulations (BFS, DFS)

**File Name:** 4) Search Simulations(BFS, DFS).ipynb

This notebook explores the fundamentals of search algorithms, focusing on the **Breadth-First Search (BFS)** and **Depth-First Search (DFS)** algorithms. These algorithms are essential for navigating trees and graphs effectively.

### Search Problem:

The notebook presents a simple search problem where an agent aims to navigate a maze. It demonstrates how the agent utilizes both BFS and DFS strategies to find solutions, with accompanying visualizations for clarity.

### Key Concepts

- **BFS:** Explores all nodes at the present depth before moving on to nodes at the next depth level.
- **DFS:** Explores as far as possible along each branch before backtracking.

[🔗 View Notebook](https://github.com/Basharul2002/AI/blob/main/4.%20Search%20Simulations(BFS,%20DFS).ipynb)

## 🔍 Search Algorithms (UCS, GBFS, A* Algorithms)

**File Name:** 5) Search Algorithms(UCS, GBFS, A*).ipynb

This notebook covers advanced search algorithms, including **Uniform Cost Search (UCS)**, **Greedy Best-First Search (GBFS)**, and **A* Search**. It provides theoretical explanations and practical implementations of these algorithms.

### Example Use Case

Each algorithm is illustrated using a map navigation scenario, allowing users to visualize the process of searching for a path from a start point to a goal while considering different cost metrics and heuristics.

### Key Differences

- **UCS:** Guarantees the shortest path by expanding the least-cost node first.
- **GBFS:** Uses heuristics to find the most promising path quickly but does not guarantee the shortest path.
- **A-star:** Combines the strengths of UCS and GBFS to efficiently find the shortest path.

[🔗 View Notebook](https://github.com/Basharul2002/AI/blob/main/5.%20Search%20Algorithms(UCS,%20GBFS,%20A*).ipynb)

## 🧬 Genetic Algorithm

**File Name:** 6) Genetic Algorithm.ipynb

This notebook introduces the concepts and applications of genetic algorithms. It provides insights into how these algorithms mimic natural selection to solve optimization problems.

### Key Concepts

- **Population:** A set of candidate solutions.
- **Fitness Function:** Evaluates how close a given solution is to the optimal solution.
- **Selection:** Selecting the best candidates for reproduction.
- **Crossover:** Combining pairs of candidates to produce offspring.
- **Mutation:** Randomly altering candidate solutions to maintain diversity.

[🔗 View Notebook](https://github.com/Basharul2002/AI/blob/main/6.%20Genetic%20Algorithm.ipynb)

## 📞 Contact

For any inquiries or suggestions, feel free to reach out via email at [basharulalam6@gmail.com](mailto:basharulalam6@gmail.com).
