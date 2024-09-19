---
level:
- Intermediate
tags:
- Distributed systems
- AWS
title: "Fault tolerance guarantees in AWS cloud transition"
speakers:
- _participants/thomas-arts.md
- _participants/Martin-Sumner.md

---
Recently a large deployment of the Riak noSQL database has been migrated from a dedicated data centre to the AWS cloud.
What does that mean for Erlang software to make that transition? One clear point is fault tolerance. Two AWS instances are not guaranteed to run on different hardware. As a consequence, if your Erlang software is fault tolerant for hardware failure using distribution, these guarantees may be gone when just running cloud instances.
Riak has fault tolerance based upon a ring of nodes. It is important that consecutive nodes run on different hardware.
In order to establish this, we needed to design a new placement algorithm.

In this talk we also address what it means to move from
slow/reliable disk to cloud fast/unreliable disk. From abundant intel-based CPU to limited ARM-based CPU and from low-cost RAM to constrained RAM usage. By a concrete case study we show general issues that arise in a transition to the cloud.

**TALK OBJECTIVES:**

We demonstrate what you should be prepared for if you want to make a transition from distributed Erlang/Elixir application on dedicated hardware to a cloud setting.

**TARGET AUDIENCE:**

Developers of distributed systems
