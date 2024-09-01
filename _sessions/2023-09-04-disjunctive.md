---
layout: session
title: Enhancing Hybrid CP-SAT Search for Disjunctive Scheduling
host: Maarten Flippo
host_ref: https://maartenflippo.com
session_type: paper
related_papers: s20230904
---

Disjunctive scheduling problems such as the job shop and open shop are at the heart of many real world scheduling instances. In this paper, we frame such problems as disjunctive temporal networks associated with a makespan minimization objective. For those, we propose a hybrid approach between SAT/SMT and CP solvers. In particular, we keep from SMT solvers the aggregated constraint propagation in decision procedures as well as the explanations and clause learning mechanisms upon conflict. However, like all CP solvers, we maintain an explicit domain representation of integer variables, tightly integrated with clause learning. Automated search exploits explanations to derive activity-based heuristics combined with the more classical value-based heuristics of CP solvers. The resulting solver is shown to be competitive with state-of-the-art exhaustive search solvers on the classical benchmarks of job shop and open shop problems.
