---
layout: session
title: A conditional time-intervals formulation of the real-time Railway Traffic Management Problem
host: Nevena Gincheva
session_type: paper
related_papers: s20240624
---

In this session, we will tackle the real-time Railway Traffic Management Problem (rtRTMP) by viewing it as a scheduling, but also a routing problem.  RtRTMP is the problem of finding optimal choices for train schedules and routes to minimize delays due to conflicts. The authors present a new Constraint Programming (CP) algorithm for the rtRTMP. The new formulation at the basis of this algorithm exploits the concept of conditional time-interval variables provided in the CP Optimizer library.

The algorithm performance is compared to one of the state-of-the-art algorithms RECIFE-MILP based on a mixed-integer linear programming (MILP) formulation. Moreover, a hybridization of RECIFE-MILP and the proposed algorithm is proposed. It often outperforms the two individual approaches, while the opposite never happens.

Briefly, in the end, I will also identify the differences between the problem that is tackled here and the Shunt Routing Problem at NS, the main topic of my thesis.