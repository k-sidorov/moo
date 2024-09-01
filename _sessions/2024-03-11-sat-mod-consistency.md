---
layout: session
title: Satisfiability modulo ordering consistency theory for multi-threaded program verification
host: Dennis Sprokholt
host_ref: https://dennis.life/
session_type: paper
related_papers: s20240311
---

Analyzing multi-threaded programs is hard due to the number of thread interleavings. Partial orders can be used for modeling and analyzing multi-threaded programs. However, there is no dedicated decision procedure for solving partial-order constraints. In this paper, we propose a novel ordering consistency theory for multi-threaded program verification under sequential consistency, and we elaborate its theory solver, which realizes incremental consistency checking, minimal conflict clause generation, and specialized theory propagation to improve the efficiency of SMT solving. We conducted extensive experiments on credible benchmarks; the results show significant promotion of our approach.