---
layout: session
title: "Control- & Data-Flow Analysis"
host: Jeff Smits
host_ref: https://www.jeffsmits.net/
session_type: research
related_papers: s20231016
---

Data-flow analysis is the static analysis of programs to estimate their approximate run-time behaviour or approximate intermediate run-time values. It is an integral part of modern language specifications and compilers. In the specification of static semantics of programming languages, the concept of data-flow allows the description of well-formedness such as definite assignment of a local variable before its first use. In the implementation of compiler back-ends, data-flow analyses inform optimisations.

In this presentation I want to familiarise you with the concept of data-flow analysis, explain Monotone Frameworks as a mathematical foundation for this kind of analysis, and show how you can derive a practical solver from it. If we have enough time I’ll also go into a bit of my research: designing the FlowSpec DSL in which you can define data-flow analysis on a high level.