---
layout: session
title: "Automatic Caching via Constraint Projection"
host: Imko Marijnissen
session_type: paper
related_papers: s20240129
---

In this session I will present the work done by Geoffrey Chu related to identifying identical subproblems. For example, consider the constraint `alldiff(x1, x2, x3, x4)`, the partial assignment `P1 = {x1 = 1, x2 = 2}` and, the partial assignment `P2 = {x1 = 2, x1 = 1}`; both of these partial assignments will lead to the same sub-problem `alldiff(1, 2, x3, x4)`. The works discussed during the session aim to automatically detect these types of symmetries and efficiently prune the search space.