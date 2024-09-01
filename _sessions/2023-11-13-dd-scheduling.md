---
layout: session
title: Decision Diagrams for Industrial Scheduling​
host: Eghonghon Eigbe
session_type: research
related_papers: s20231113
---

A common way to model a manufacturing system is as a flow shop, which is a collection of jobs and machines. Many different variants exist depending on whether machines are multi-purpose, if jobs are processed in a fixed order, etc. Many exact and heuristic scheduling methods for flow shops exist in the literature. Exact solutions often scale poorly, and heuristics typically do not provide any theoretical guarantees. In this work, we bridge these gaps by combining the strength of decision diagrams to generalise easily and provide optimal solutions with the heuristic strength of finding good solutions quickly. Our approach builds on recent work on exploring solution neighbourhoods with decision diagrams. We introduce new state dominance relationships and extend the existing literature to perform neighbourhood search with exact decision diagrams. As the state-of-the-art for many flow shop scheduling problems is still to use heuristics, our approach serves as a way to strategically improve heuristic solutions and also to assess their optimality. We discuss the operation of this approach on a basic flow shop and a more complex industrial use case. We show via empirical evaluation that our approach is competitive with other exact solvers for some problems and scales better for others.