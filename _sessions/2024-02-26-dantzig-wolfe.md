---
layout: session
title: A tour of Dantzig–Wolfe decomposition
host: Konstantin Sidorov
host_ref: https://ksidorov.nl
session_type: tour
---

In this session, I am going to introduce the concept of Dantzig-Wolfe decomposition, an approach that is helpful when you need to solve a large linear program, but you can also find a “convenient” block structure there. To make the exposition more widely applicable, I am going to revisit various well-known example domains, such as graph coloring or the cutting stock problem. Finally, since the specific decomposition layout has a large impact on the solving process, we will also look at GCG, a SCIP extension that streamlines the search for an appropriate Dantzig–Wolfe decomposition, and discuss how it searches for the partitions of the variables and constraints.