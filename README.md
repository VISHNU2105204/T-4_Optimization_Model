# Task - 4
# Optimization Model
*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: BADIMELA VISHNU VARDHAN

*INTERN ID*: CTIS1342

*DOMAIN*: DATA SCIENCE

*DURATION*: 12 WEEKS

*MENTOR*: NEELA SANTHOSH

## Project Overview: Automated Workforce Optimization using Mixed-Integer Linear Programming

## This is a sophisticated project that applies Operations Research (OR) and Data Science to a critical business challenge: workforce optimization. Below is a 500-word description of your project, designed for a professional portfolio or technical report.

## The Problem: The Complexity of Human-Centric Scheduling
## In high-stakes industries such as healthcare, retail, and manufacturing, generating a weekly employee roster is a complex combinatorial problem. Managers must balance three competing priorities: operational requirements (ensuring enough staff are on-site), legal/safety constraints (labor laws and rest periods), and employee wellbeing (personal shift preferences).

## Manual scheduling is not only time-consuming but often leads to sub-optimal results, such as employee burnout or accidental violations of labor regulations. This project addresses these challenges by transforming scheduling from a subjective manual task into a mathematical optimization problem.

## The Solution: Linear Programming with PuLP
## The project utilizes Mixed-Integer Linear Programming (MILP), implemented via the PuLP library in Python, to generate an optimal 7-day schedule for a team of 10 employees. Unlike a simple randomized assignment, this model uses the COIN-OR solver to navigate thousands of possible combinations to find the single "best" version of the schedule.The model defines a binary decision variable Xe,d,s, which equals 1 if an employee is assigned to a specific shift and 0 otherwise. The Objective Function is designed to minimize a "Displeasure Cost"—a metric derived by subtracting employee shift preferences (on a 1–10 scale) from a maximum value. By minimizing this cost, the model mathematically maximizes collective employee satisfaction.

# OUTPUT:
<img width="656" height="792" alt="Image" src="https://github.com/user-attachments/assets/15126668-f97b-41ba-997c-ad4d3af13523" />
<img width="400" height="93" alt="Image" src="https://github.com/user-attachments/assets/6c01c99f-2165-478c-886d-9acbc05adb23" />
