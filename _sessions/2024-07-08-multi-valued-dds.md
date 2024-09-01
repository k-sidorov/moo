---
layout: session
title: Multi valued decision diagrams for multi machine sequencing problems
host: Eghonghon Eigbe
session_type: research
related_papers: s20240708
---

Decision diagrams can be used for solving optimization problems. Apart from the more popular approach of using them constructively to build solutions in a top-down manner, they can also serve as a constraint store and be incrementally refined by filtering out infeasible arcs until only feasible solutions remain. Existing work has explored single machine sequencing problems or multi machine sequencing problems with identical or very similar machines. In our current WIP, I am extending this to generalize multi resource scheduling scenarios where resources are not necessarily identical, operations can be assigned to one or more resources, etc.. This requires the development of new state representations, merging rules, dominance rules, and more closely related to CP, refinement rules for removing infeasible edges. In this session, I will provide explanations of what has been done so far in the hopes of triggering a discussion that validates and/or challenges our current ideas. An honorable mention will also be made of a small success story with incorporating reinforcement learning for one of the steps in decision diagram based branch and bound.