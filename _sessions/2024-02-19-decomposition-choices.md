---
layout: session
title: Decomposition choices for column generation applied to large-scale urban multi-energy system models
host: Maaike Elgersma
session_type: research
---

To tackle the energy transition challenges, urban decision-makers need to make good long-term investment plans. MILP models that describe the urban multi-energy system can help them. However, these models are extremely large in terms of the number of decision variables and constraints. Even for simplified versions of the model, Gurobi was not able to find the optimal solution. In my master thesis, I attempted to answer the research question “Can column generation improve the quality of the solution found by a model that optimizes the design of a real-life urban multi-energy system within a fixed amount of time?”. Because of the many dimensions of the model, different decomposition choices could be made while implementing column generation. In this reading group session, we will investigate and analyze these different options and draw conclusions on what to take into account when applying column generation to large-scale MILPs.