---
layout: session
title: Finding the shortest resolution proof of an UNSAT formula
host: Konstantin Sidorov
host_ref: https://ksidorov.nl
session_type: research
related_papers: s20240715
---

For the season finale, I will present my recent research about the proof minimization. Even though SAT solvers are good at finding relatively short proofs, there is little to say about the shortest possible proof of unsatisfiability, which could be helpful to (a) figure out the limits of conventional SAT solvers and (b) collect data on which learned clauses are “helpful” to refute a formula. My goal for this session is to show the intuition of why this is a hard problem, describe our branch-and-bound approach, and, hopefully, showcase some experimental insights.