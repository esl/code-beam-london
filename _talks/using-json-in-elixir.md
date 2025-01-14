---
tags:
- json, elixir, performance
level: Intermediate users, Proficient users
title: "Trade-offs using JSON in Elixir 1.18: Wrappers vs Erlang Libs"
speakers:
- _participants/michal-muskala.md

---
Elixir 1.18 builds on top of the new json module from OTP 27 and introduces the JSON module to the standard library. It provides performance significantly exceeding existing pure-Erlang and Elixir libraries (including Jason), and sometimes even beating NIFs written in C. Furthermore, it offers a more flexible and adaptable API. In this talk, we’ll have a brief look at the new module, and explore how it was possible to achieve the speed and flexibility it offers. We'll answer why it was useful to build and Elixir wrapper, and advise on migration strategy from Jason. Finally, we’ll look at various tips & tricks for building performant Erlang and Elixir libraries.

**KEY OBJECTIVES:**
- How to use the new JSON module from Elixir 1.18
- How to migrate applications and libraries using Jason
- How to build high performance libraries in Erlang & Elixir

**TARGET AUDIENCE:**
- Medium to advanced Elixir & Erlang engineers interested in BEAM performance & internals as well as library API design