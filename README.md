# AI Lab Programs – Python (Jupyter Notebook)

This repository contains basic **Artificial Intelligence laboratory programs implemented using Python in Jupyter Notebook**.
The programs demonstrate fundamental AI concepts such as **Simple Reflex Agents, Rational Agents, Goal-Based Agents, and the Vacuum Cleaner Environment**.

## 📌 Programs Included

### 1. Simple Reflex Agent – Vacuum Cleaner World

This program implements a **simple reflex agent** that decides actions based only on the **current percept** (location and status of the room).

**Actions performed:**

* If the room is **Dirty → Suck**
* If the agent is in **Room A → Move Right**
* If the agent is in **Room B → Move Left**

This demonstrates how reflex agents respond to the environment without memory.

---

### 2. Simple Reflex Agent Simulation

This program simulates the **vacuum cleaner agent for multiple iterations**.

Features:

* Agent operates in two locations: **A and B**
* The environment is updated after each action
* The agent runs for **5 iterations**
* Shows how the agent repeatedly senses and acts in the environment

---

### 3. Goal-Based Agent – Moving Towards a Goal

This program demonstrates a **goal-based agent**.

Functionality:

* The agent starts from an **initial position**
* Moves step-by-step until it reaches the **goal position**
* Prints the **current position at each step**

This illustrates how an agent works towards achieving a predefined goal.

---

### 4. Rational Agent Implementation

This program implements a **rational agent using a Python class**.

Features:

* Uses **Object-Oriented Programming**
* The agent has a **goal position**
* Moves step-by-step until the goal is reached
* Demonstrates the concept of **rational decision making**

---

### 5. Vacuum Cleaner Agent for Multiple Rooms

This program simulates a **vacuum cleaner agent cleaning a grid environment**.

Environment:

* A **4×4 room grid**
* Cells can be **Dirty (1)** or **Clean (0)**

Process:

1. All rooms start as dirty.
2. Random dirt is generated in the grid.
3. The agent scans each location.
4. If dirt is detected, the agent cleans the cell.
5. The final room status and **performance percentage** are displayed.

---

## 🛠 Technologies Used

* **Python**
* **Jupyter Notebook**
* **Random module**

---

## 📚 Concepts Demonstrated

* Simple Reflex Agents
* Goal-Based Agents
* Rational Agents
* Environment Interaction
* Performance Measurement
* Basic AI Problem Solving

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/your-repository-name.git
```

2. Open the project folder.

3. Launch **Jupyter Notebook**:

```
jupyter notebook
```

4. Open the notebook and run the cells.

---

## 🎓 Purpose

This repository was created as part of **Artificial Intelligence Laboratory coursework** to understand the **basic behavior of intelligent agents and their interaction with environments**.

---

⭐ If you found this repository helpful, feel free to **star the repo**.
