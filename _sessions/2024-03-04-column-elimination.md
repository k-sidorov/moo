---
layout: session
title: Column Elimination for Capacitated Vehicle Routing Problems
host: Elif Arslan
session_type: paper
related_papers: s20240304
---

We introduce a column elimination procedure for the capacitated vehicle routing problem. Our procedure maintains a decision diagram to represent a relaxation of the set of feasible routes, over which we define a constrained network flow. The optimal solution corresponds to a collection of paths in the decision diagram and yields a dual bound. The column elimination process iteratively removes infeasible paths from the diagram to strengthen the relaxation. The network flow model can be solved as a linear program with a conventional solver or via a Lagrangian relaxation. To solve the Lagrangian subproblem more efficiently, we implement a special successive shortest paths algorithm. We introduce several cutting planes to strengthen the dual bound, including a new type of clique cut that exploits the structure of the decision diagram. We experimentally compare the bounds from column elimination with those from column generation for capacitated vehicle routing problems.