---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About
======
Hello! My name is Carlos, and I am currently an Assistant Professor in the Computer Engineering department at Cal Poly, San Luis Obispo. I teach courses related to autonomous mobile robots (CPE416) and computer organization (CPE225). Broadly speaking, my research interests lie in robotics, reinforcement learning, and game theory. Specifically, I have worked on problems in the realm of security games, Monte Carlo Tree Search for robots in vineyards, and trajectory optimization for teams of robots.

My work and research
======
The bulk of my work so far has focused on studying the problem known as the Patrolling Game or Security Game (AAMAS 2019, ICRA 2020, ICRA 2024). In these works, we model two agents: the "defender" and the "intruder", and we compute optimal strategies for the defender to solve the game. Unlike prior work in this area, we model intruders as having only limited information about the patroller's strategy. More recently, we have explored deep reinforcement learning techniques to generate defender strategies, enabling generalization across diverse intruder behaviors.

I have also worked on Monte Carlo Tree Search (MCTS) methods (IROS 2023) to solve the stochastic orienteering problem. Here, we model edge weights as random variables and solve the orienteering problem for a single robot. While non-static edge weights complicate the problem, we argue that this stochastic formulation more accurately models real-world energy costs for robots. For instance, the physical distance between two points in a field remains constant, but the actual battery consumption depends on external factors such as average speed and weather conditions.

Recent News
======
1. June 2025. Congratulations to lab student Wyatt Colburn for walking the graduation stage just before defending his Master's thesis this summer! He has been working on an exciting project at the intersection of robotics and machine learning.
3. June 2025. Congratulations to lab students Jay Rajesh and Jorge Ramirez, who will present their work at the BEACoN Symposium this spring! Their posters represent the culmination of two quarters of work building a robot dataset and training an ML model for control.
3. March 2025. This spring quarter, I will be teaching CPE 225: Computer Organization. The course will cover RISC-V architectures and memory management in C, providing students with foundational knowledge in low-level computing.