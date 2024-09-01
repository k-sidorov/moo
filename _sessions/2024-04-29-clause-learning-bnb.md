---
layout: session
title: Combining Clause Learning and Branch and Bound for MaxSAT
host: Imko Marijnissen
session_type: paper
related_papers: s20240429
---

Branch and Bound (BnB) is a powerful technique that has been successfully used to solve many combinatorial optimization problems. However, MaxSAT is a notorious exception because BnB MaxSAT solvers perform poorly on many instances encoding interesting real-world and academic optimization problems. This has formed a prevailing opinion in the community stating that BnB is not so useful for MaxSAT, except for random and some special crafted instances. In fact, there has been no advance allowing to significantly speed up BnB MaxSAT solvers in the past few years, as illustrated by the absence of BnB solvers in the annual MaxSAT Evaluation since 2017. Our work aims to change this situation and proposes a new BnB MaxSAT solver, called MaxCDCL, by combining clause learning and an efficient bounding procedure. The experimental results show that, contrary to the prevailing opinion, BnB can be competitive for MaxSAT. MaxCDCL is ranked among the top 5 solvers of the 15 solvers that participated in the 2020 MaxSAT Evaluation, solving a number of instances that other solvers cannot solve. Furthermore, MaxCDCL, when combined with the best existing solvers, solves the highest number of instances of the MaxSAT Evaluations.