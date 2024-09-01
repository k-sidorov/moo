---
layout: session
title: "ViolationLS: Constraint-Based Local Search in CP-SAT"
host: Maarten Flippo
host_ref: https://maartenflippo.com
session_type: paper
related_papers: s20240701
---

We introduce ViolationLS, a Constraint-Based Local Search (CBLS) solver for arbitrary MiniZinc models based on the Feasibility Jump Mixed-Integer Programming Heuristic. ViolationLS uses a novel approach for finding multi-variable moves without requiring any “implicit" or “one-way" constraints traditionally used by CBLS solvers. It significantly outperforms other state-of-the-art CBLS solvers on the MiniZinc challenge benchmarks, both with and without multi-variable moves. We demonstrate that integrating ViolationLS into the parallel portfolio framework of the state-of-the-art CP-SAT Lazy Clause Generation solver improves performance on more than half of the instances in the MiniZinc challenge benchmarks suite. To our knowledge this is the first instance of such an integration of CBLS and Lazy Clause Generation inside the same solver.