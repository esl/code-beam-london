---
audience:
- beginners
- intermediate
tags:
- devops
- no-downtime
- hot-upgrades
speakers:
- _participants/Daniel-Szoboszlay.mds

---
Hot code loading is a well known, but not exactly well understood feature of the BEAM. However, at Klarna we boldly use it for no-downtime upgrades for over 20 years now. Which is a lot of time to master our skills, and also to walk into every conceivable trap on the way. This talk will let you achieve the former, while avoiding the latter, in less then half an hour. So buckle up, and let's get lost in the world of changing supervision trees, backward-compatible API updates, ageing anonymous functions and the rpc calls that always arrive at the worst possible moment!

**TALK OBJECTIVES:**

Understand the underlying mechanisms of hot code loading in Erlang and learn a lot of best practices about how to execute no-downtime upgrades in a safe way.

**TARGET AUDIENCE:**

BEAM developers who want to do safe upgrades in a DevOps role, or from a pure Dev role allow their Ops colleagues to do so on the code they hand over.
