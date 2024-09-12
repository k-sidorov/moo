---
layout: session
title: Parallel General-Purpose Dynamic Programming Solvers for Combinatorial Optimization
host: Chris Beck
host_ref: https://www.mie.utoronto.ca/faculty_staff/beck/
session_type: research
related_papers: s20240916
---

Domain-independent dynamic programming (DIDP) is a recently proposed model-based paradigm for combinatorial optimization based on dynamic programming (DP). In DIDP, similar to mathematical programming, a user formulates a combinatorial optimization problem as a declarative DP model and then solves the formulated model by calling a general-purpose solver. The currently developed DIDP solvers are based on heuristic search algorithms studied in the artificial intelligence community. In this work, we develop parallel DIDP solvers using parallel heuristic search algorithms. First, we empirically confirm that the multi-thread versions of our parallel DIDP solvers outperform commercial multi-thread mixed-integer programming and constraint programming solvers in multiple combinatorial optimization problems. Then, we develop distributed parallel DIDP solvers using the Message Passing Interface. Our experimental evaluation demonstrates the high scalability of the parallel DIDP solvers in a massively parallel distributed environment.
