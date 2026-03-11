# Unit 3: AI Problem Solving and Search Techniques

## Introduction

Artificial Intelligence (AI) aims to create intelligent systems that can perform tasks requiring human intelligence. One of the fundamental aspects of AI is **problem solving**, where a computer program searches for solutions to complex problems using logical reasoning and algorithms.

Problem solving in AI often involves exploring different possible states and finding the best path to reach a goal state. This is achieved using **search techniques** which systematically examine possible solutions.

---

## Definition of AI Problem Solving

AI problem solving is the process of finding a sequence of actions that transforms the **initial state** of a problem into a **goal state**.

It typically involves:

* Identifying the problem
* Representing the problem in a structured form
* Applying algorithms to explore possible solutions
* Selecting the best solution based on specific criteria

---

## Search Techniques

Search techniques are methods used by AI systems to explore the **state space** of a problem in order to find a solution.

A search process generally includes:

* Initial state
* Goal state
* State space
* Operators (actions)
* Path cost

The search algorithm systematically explores possible states until the goal state is reached.

---

## Types of Search

### 1. Uninformed Search (Blind Search)

Uninformed search algorithms do not use any additional knowledge about the problem other than the problem definition.

Common uninformed search methods:

* Breadth First Search (BFS)
* Depth First Search (DFS)
* Depth Limited Search
* Iterative Deepening Search
* Uniform Cost Search

Characteristics:

* No heuristic knowledge used
* Explores the search space blindly
* May require more time and memory

---

### 2. Informed Search (Heuristic Search)

Informed search algorithms use **heuristic information** to guide the search process toward the goal more efficiently.

Common informed search algorithms:

* Greedy Best First Search
* A* Search Algorithm
* Hill Climbing
* Beam Search

Characteristics:

* Uses heuristic functions
* Reduces search space
* Faster than uninformed search in many cases

---

## Heuristic Function

A **heuristic function** is a function that estimates the cost of reaching the goal from a given node.

It is usually represented as:

h(n)

Where:

* n = current node
* h(n) = estimated cost to reach the goal

Properties of good heuristic functions:

* Admissible (never overestimates the cost)
* Consistent
* Helps reduce computation time

Example:

* Straight-line distance used in route finding problems

---

## Problem Representation

In AI, a problem must be represented in a structured form so that the computer can understand and solve it.

A typical problem representation includes:

1. Initial State – starting point
2. Goal State – desired result
3. State Space – all possible states
4. Operators – actions that change states
5. Path Cost – cost of moving from one state to another

Example problems:

* 8-Puzzle Problem
* Water Jug Problem
* Travelling Salesman Problem

---

## Applications of AI Problem Solving

AI problem solving techniques are used in many real-world applications:

* Robotics
* Game playing (Chess, Tic-Tac-Toe)
* Navigation systems
* Route planning
* Automated reasoning
* Medical diagnosis

These systems use search techniques to evaluate different possibilities and select optimal solutions.

---

## Advantages

* Helps solve complex problems efficiently
* Provides optimal or near-optimal solutions
* Improves decision making
* Automates intelligent tasks
* Widely applicable in multiple domains

---

## Limitations

* Some problems have very large search spaces
* High computational cost
* Requires good heuristic design
* May consume large memory
* Not always guaranteed to find the best solution

---

## Summary

AI problem solving is a core concept in artificial intelligence that focuses on finding solutions using systematic search strategies. Search techniques explore possible states in order to reach a goal state. These techniques are broadly categorized into **uninformed search** and **informed search**.

Heuristic functions improve search efficiency by estimating the cost to reach the goal. Proper problem representation and efficient search algorithms enable AI systems to solve complex real-world problems effectively.
