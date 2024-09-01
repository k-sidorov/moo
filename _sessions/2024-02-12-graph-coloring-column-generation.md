---
layout: session
title: A Column Generation Approach for Graph Coloring
host: Konstantin Sidorov
host_ref: https://ksidorov.nl
session_type: paper
related_papers: s20240212
---

In this session, I will discuss the branch-and-price framework using graph coloring as an example problem. The branch-and-price approach involves restating the original problem as a MILP model with (exponentially) many variables and lazily introducing them via the duality reasoning, all while executing a normal branch-and-bound loop. The graph coloring case is particularly convenient here because (a) the reformulation is, in my opinion, relatively intuitive and (b) most of the typical branch-and-price technical complications are resolved straightforwardly.

I will largely follow the narrative of (Mehrotra & Trick, 1996) but I also hope to mention some of the more involved branch-and-price topics and how they are resolved, as well as some connections to (unsurprisingly) the proof-logging domain:)