---
level:
- Beginner
- Intermediate
- Advanced
tags:
- Distributed systems
- Microbatching
- Elixir
title: "Building a Highly Available, Distributed Streaming System Using Only Elixir and The BEAM"
speakers:
- _participants/flora-petterson.md
- _participants/madison-brown.md

---
HCA’s Waterpark data integration engine is a continuously available streaming system; it's also a distributed database that never touches disk. Waterpark accomplishes this by utilizing built-in features of Elixir and the BEAM. Each message in the endless streams arriving in Waterpark is routed across the geographically distributed cluster to the relevant actor processes for exactly-once processing without depending on external broker dependencies such as RabbitMQ or Kafka.
How does our team build and maintain this unique system? This talk will discuss a few key tools: the Publish-Subscribe Messaging Pattern, micro-batching, queuing theory, and more. You'll see how we use these tools, along with core BEAM features, to safely and reliably store messages from a publication within our application, until they are sent to a subscriber. And we'll share the lessons we learned along the way.

**TALK OBJECTIVES:**

Discuss how to store messages from a publication as part of the Publish-Subscribe model in Elixir and Erlang distributed systems.

**TARGET AUDIENCE:**

Erlang, Elixir & distributed systems developers
