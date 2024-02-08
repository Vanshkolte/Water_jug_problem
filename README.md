##Water Jug Problem
Overview
The Water Jug Problem is a classic puzzle in computer science and mathematics that involves transferring water between jugs to achieve a specific goal. The problem typically involves two jugs of known capacities and a desired amount of water to be measured using these jugs.

Problem Statement
Given two jugs with capacities X and Y liters, a starting state of (0, 0) liters of water in both jugs, and a goal state of G liters of water in one of the jugs, determine the steps required to reach the goal state, if possible, using a set of allowed operations. The allowed operations usually include filling a jug, emptying a jug, and pouring water from one jug to another until either the other jug is full or the first jug is empty.

Implementation
The provided Python script water_jug_problem.py implements a solution to the Water Jug Problem using a simple console-based interface. The user can input specific rules corresponding to the allowed operations to simulate the steps needed to solve the problem.

Instructions
Run the Python script water_jug_problem.py.
Follow the on-screen prompts to input rules corresponding to the allowed operations:
Rule 2: Fill the second jug (Y) to its maximum capacity.
Rule 9: Pour water from the first jug (X) into the second jug (Y) until either the second jug is full or the first jug is empty.
Rule 7: Pour water from the second jug (Y) into the first jug (X) until either the first jug is full or the second jug is empty.
Rule 5: Empty the first jug (X).
Continue inputting rules until the goal state (G, _) is achieved, where G is the desired amount of water in one of the jugs.
Example
Suppose the capacities of the jugs are X = 4 liters and Y = 3 liters, and the goal is to measure 2 liters of water using these jugs. The script will output the sequence of steps required to achieve the goal, demonstrating the solution to the Water Jug Problem.
