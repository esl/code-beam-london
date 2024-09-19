---
tags:
level: Addvaced
title: "BEAM's bright future with Gleam (and JavaScript?)"
speakers:
- _participants/Peter-Saxton.md

---
Gleam is a language "running on the battle-tested Erlang virtual machine that powers planet-scale systems". Several of Gleam's design decisions were made to target the BEAM.

Gleam also compiles to JavaScript and this is the most exciting thing it does for the BEAM ecosystem.
Why?

- Exposing new people to the BEAM. People familiar with Elm are trying a Gleam web framework.
When looking for how to build the web backend the obvious answer is more Gleam, but on BEAM.
- Actor's everywhere. The community is now asking questions like "how do I start actors in the browser" "How do I message pass to the server, from the server"
- Using types as a design tool. Erlang has blocking IO, JavaScript does not. These are not just differences in the language but the platform they run on. Gleam captures these differences in types,
allowing cross environment code reuse where appropriate but highlighting the differences where necessary.

**TALK OBJECTIVES:**

* Erlang has always been a superstar when it comes to distributed cloud/web applications.
But in this space there is normally an frontend component.
JavaScript is eating the world because it works on the front and the backend.
* Elixir is trying to tackle this space with LiveView, but is server first.
* Gleam is positioned to allow a unified solution for a whole range of modern cloud applications.
The aim of this talk is to explain that this bright future is possible.
Even more importantly the talk will dive into the Gleam ecosystem and show that this bright future is already happening.

**TARGET AUDIENCE:**

* This talk is for anyone who has build systems in erlang or elixir and was even close to having to work with the front end.
