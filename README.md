# Connect 4 AI Project
---

## Team Members

* Youssef Osama
* Kyrolles Wageh

---

## Supervisor

Dr. Marwa Mamdouh

---


An intelligent Connect 4 game developed as an Artificial Intelligence project.
This project applies AI concepts to build a strategic agent capable of playing Connect 4 against a human player or another AI agent.

---

## Project Overview

Connect 4 is a classic two-player strategy game played on a **6 × 7 grid**.
Players take turns dropping colored discs into one of the seven columns, and each disc occupies the lowest available position in that column.

The objective is simple:
the first player to connect **four consecutive discs** horizontally, vertically, or diagonally wins the game.

This project focuses on designing and implementing an intelligent AI agent that can:

* Analyze the current board state
* Predict possible future moves
* Evaluate strategic outcomes
* Choose the best possible move
* Compete efficiently against human or AI opponents

The project demonstrates how Artificial Intelligence can be applied in game environments using decision-making and search techniques.

---

## Problem Rules

The Connect 4 game follows these rules:

* The game is played on a **6 × 7 grid**
* Two players take turns dropping one disc at a time
* A disc always falls to the lowest available position in the selected column
* Players cannot place a disc in a full column
* The first player to connect **four consecutive discs** wins
* Connections can be:

  * Horizontal
  * Vertical
  * Diagonal
* If the board becomes full without a winner, the game ends in a draw
* The AI agent must always choose valid legal moves only

---

## AI Agent Design

The AI agent is designed to make intelligent strategic decisions during gameplay.

Its main objectives are:

* Win the game whenever possible
* Block opponent winning opportunities
* Maximize board advantage
* Avoid weak or losing positions
* Select efficient strategic moves

The agent evaluates the board and chooses actions based on future outcomes rather than only the current move.

---

## Agent Classification

### PEAS Analysis

#### Performance

* Win the game
* Block opponent moves
* Maximize connected discs
* Avoid losing positions
* Make efficient strategic decisions

#### Environment

* Connect 4 board (**6 × 7 grid**)
* Two players
* Colored discs
* Game rules
* Board states

#### Actuators

* Drop disc into column 1
* Drop disc into column 2
* Drop disc into column 3
* Drop disc into column 4
* Drop disc into column 5
* Drop disc into column 6
* Drop disc into column 7

#### Sensors

* Detect board state
* Detect empty and occupied cells
* Detect valid columns
* Detect player moves
* Detect winning positions
* Detect draw states

---

### ODESDA Analysis

#### Observable

Fully observable
(The agent can observe the complete board state and all player moves.)

#### Deterministic

Deterministic
(Each action produces a predictable and known result.)

#### Episodic

Sequential
(Each move affects future states and decisions.)

#### Static

Static
(The environment does not change while the agent is deciding.)

#### Discrete

Discrete
(Board positions, actions, and states are finite and clearly defined.)

#### Agents

Multi-agent
(Two players compete, and both affect the outcome.)

---

## Agent Type

### Simple Reflex Agent?

**No**
Because Connect 4 requires more than reacting only to the current board state.

### Model-Based Agent?

**No**
Because keeping track of the board alone is not enough; the agent must also plan ahead.

### Goal-Based Agent?

**Yes**
Because the agent has a clear goal: connect four discs before the opponent.

### Utility-Based Agent?

**Yes**
Because the agent evaluates multiple possible moves and selects the best one based on:

* Winning probability
* Board advantage
* Threat blocking
* Strategic positioning

---

## AI Concepts Used

This project demonstrates several important Artificial Intelligence concepts, including:

* Intelligent Agents
* Adversarial Search
* Decision Making
* State Space Representation
* Rule-Based Evaluation
* Strategic Planning
* Game Trees

---

## Project Goal

The main goal of this project is to build an intelligent Connect 4 AI agent capable of:

* Understanding the game state
* Making strategic decisions
* Predicting future outcomes
* Competing effectively
* Demonstrating practical AI in games

---

