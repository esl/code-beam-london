---
level:
- Introductory and Overview
tags: []
title: 'Little things and big things: lessons for building large systems'
speakers:
- _participants/Peteer-Van-Roy.md

---
Designing systems at a bigger scale than what has been done before is hard. Past experience only goes so far. In this talk I will give some hard-earned lessons of system design, both little and big, that can keep your system working and save your sanity when you are building a big system. I will illustrate these lessons with examples taken from real systems. Some topics I will cover are: two rules that the system must always obey, why big buffers are bad, what happens when the system jumps off a cliff, how to avoid nondeterminism in distributed systems, understanding internal and external correlations, the right way to use time-outs, whether to mitigate or propagate (building on top of supervisor trees), and the importance of multiple timescales. This talk is based on an ongoing project in collaboration with the company PNSol. We are creating a comprehensive tutorial and tool support for large-scale system design. I dedicate this talk to Neil Davies and Peter Thompson of PNSol for their insights and friendship.
