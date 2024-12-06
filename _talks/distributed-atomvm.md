---
tags:
- IoT, disterl, AtomVM
level: Intermediate users, Proficient users
title: "Distributed AtomVM: Let's Create Clusters of Microcontrollers"
speakers:
- _participants/paul-guyot.md
github: pguyot
linkedin: /in/pguyot


---
AtomVM, the Erlang and Elixir VM for microcontrolers, is all about IoT, but the first commercial product based on AtomVM, La Machine, isn't connected to the internet. Nevertheless, AtomVM can be used on many boards with Ethernet and Wifi capabilities.

The most requested feature for AtomVM at CodeBEAM Europe 2024 was distributed Erlang, and this session will officially introduce the feature. Beyond a demo, probably involving several IoT devices on stage, session will present major AtomVM features and capabilities related to distribution, including differences with Erlang and key take aways from their implementation.

For example, it will describe networking API and how socket became first-class citizen on AtomVM. It will also cover REPL prototypes on tiny-size cardputers and whether they can be used to connect to Erlang nodes.

**KEY OBJECTIVE:**
- Introducing the audience to key AtomVM capabilities.

**TARGET AUDIENCE:**
- Elixir and Erlang developers. IoT enthusiasts