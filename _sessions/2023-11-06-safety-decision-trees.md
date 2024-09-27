---
layout: session
title: Safety Verification of Decision-Tree Policies in Continuous Time
host: Anna Lukina
host_ref: https://annalukina.com/
session_type: research
related_papers: s20231106
---

Following up on Koos' presentation, we have another presentation on decision trees, but this time in a completely different context: verification of decision trees as controllers in continuous time. These problems are difficult for our standard SAT/CP/MIP procedures, so we will look at something new! The presentation is based on a recently accepted NeurIPS'23 paper that was a joint effort of TU Delft (Anna, Emir) and Aalborg University (Christian Schilling and Kim Larsen)

<i>Abstract.</i> Decision trees have gained popularity as interpretable surrogate models for learning-based control policies. However, providing safety guarantees for systems controlled by decision trees is an open challenge. We show that the problem is undecidable even for systems with the simplest dynamics, and PSPACE-complete for finite horizon properties. The latter can be verified for discrete-time systems via bounded model checking. However, for continuous-time systems, such an approach requires discretization, thereby weakening the guarantees for the original system. This paper presents the first algorithm to directly verify decision-tree controlled systems in continuous time. The key aspect of our method is exploiting the decision tree structure to propagate a set-based approximation through the decision nodes. We demonstrate the effectiveness of our approach by verifying the safety of several decision trees distilled to imitate neural network policies for nonlinear systems.
