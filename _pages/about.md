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
Hello! I am Carlos Diaz Alvarenga a PhD Candidate in the Computer Science and Engineering department at the University of California, Merced. I currently work in the [Robotics Lab](https://robotics.ucmerced.edu) under the supervision of prof. Stefano Carpin. My research intersets broadly speaking are in robotics, reinforcement learning, and control. Specifically, we have worked on problems in the realm of Security Games, Monte Carlo Tree Search for robots in a vineyard, and Trajectory Optimization for teams of robots.

As of March 2024, I have accepted an assistant professor position at Cal Poly SLO! The computer engineering department there is full of great academics with an ambitous vision to improve CSE education and research.

My work and research
======
The bulk of my work so far has been studying the problem known as the Patrolling or Security Game (2019 AAMAS, 2020 ICRA, 2024 ICRA). For these works we model two agents known as the "defender" (or patroller) and the "intruder" and try to compute strategies for the defender to solve the game. Differently, from previous work in the area we model intruders as having only limited information about the patroller's strategy. More recently, we have looked at Deep Reinforment Learning techniques to produce strategies for the defender allowing us to generalize across intruder behaviors.

I have also worked on Monte Carlo Tree Search (2023 IROS) methods to solve the stochastic orienteering problem. We model edge weights as random variables and try to solve the orienteering problem for a single robot. Edge weights that are not static only make the problem more difficult, however, we argue that this non-deterministic case can model energy costs for a robot more accurately. Consider that the distance from one end of the field to another is never changing, however, when the robot moves between the two points the actual amount of battery used will depend on external factors such as average speed and weather.

Recent News
======
1. (March 2024) I have accepted an assistant professor position at the California Polytechnic University at San Luis Obispo! Many thanks to Dr. Lynne Slivovsky and Dr. John Oliver for the opportunity to present my work and my vision for my lab.
2. (Feb 2024) Presented my work in the weekly seminar series here at UC Merced for the Electrical Engineering and Computer Science (EECS) graduate group. I gave an overview of the research I have conducted here at UC Merced with a focus on the patrolling game series.
3. (Jan. 2024) Two papers got accepted at ICRA 2024! The first one engineers the Security Game as a Marvok Decision Process and applies DRL techniques to produce a schedule for the patroller. The second looks at how to optimally partition an environment acoording to shared and independent workloads for a team of robots tasked with patrolling an area. ICRA 2024 will be held in Yokohama, Japan.