# capstoneproject
capstone project  for AI and ML course
1. Project Overview
This project explores Black-Box Optimisation (BBO), where the objective functions are unknown and must be optimised through limited experiments.

The challenge involves eight synthetic functions with 2–8 dimensions, representing applications such as robotics, manufacturing, radiation detection, recipe design and machine learning.

The goal is to maximise each function's output within a limited query budget, developing practical skills in optimisation, experimental design, surrogate modelling and data-driven decision-making.

2. Inputs and Outputs
Inputs: Continuous values between 0 and 1.

Dimensions: Vary from 2 to 8 across the eight functions.

Outputs: A single numerical performance value per query.

Objective: Maximise the output of every function.

Example input (Function 3):

0.340000-0.660000-0.420000

Example output: 1842.50527

3. Challenge Objectives
The challenge aims to maximise all eight unknown functions under the following constraints:

Mathematical functions are hidden.

Only one query per function is allowed per round.

Each submission returns an observation for subsequent analysis.

Decisions must rely on limited historical data.

Higher dimensions increase search complexity.

Success depends on both optimisation performance and a logical, evidence-based approach.

4. Technical Approach
The strategy has evolved across three stages:

Round 1 – Exploration

Sampled previously unexplored regions.

Established initial performance benchmarks.

Discovered promising regions, particularly in Function 3.

Round 2 – Targeted Exploitation

Used previous observations to identify promising regions.

Refined input values around stronger-performing points.

Achieved significant improvements in Functions 1, 3 and 5.

Round 3 – Local Optimisation

Focused on refining high-performing regions.

Applied small perturbations to promising inputs.

Prioritised Functions 3, 5 and 8, alongside refinement of Functions 4, 6 and 7.

Methods and concepts applied:

Exploratory sampling and local search

Feature-level analysis and regression reasoning

Surrogate modelling

Bayesian optimisation principles

Potential application of Gaussian Processes, Random Forests, SVMs and Upper Confidence Bound (UCB).

The overall approach balances exploration (discovering promising regions) with exploitation (refining known high-performing regions).

5. Current Progress
Function

Dimensions

Best observed output

1

2

-0.000455

2

2

0.611205

3

3

-0.004693

4

4

-4.025540

5

4

1842.505270

6

5

-0.714265

7

6

1.364970

8

8

9.598480

6. Next Steps
Continue refining promising regions, improve the balance between exploration and exploitation, and investigate surrogate modelling and Bayesian optimisation to make better use of the limited query budget.

The README will be updated as new observations are collected and optimisation strategies evolve.
