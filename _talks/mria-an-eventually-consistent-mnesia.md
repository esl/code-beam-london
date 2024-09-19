---
level:
- Intermediate
tags:
- Innovation
- Mnesia
title: 'Mria: an eventually consistent Mnesia'
speakers:
- _participants/Dmitrii-Fedoseev.md

---
Mnesia is an embedded database that keeps data locally, and as such it offers incredible read throughput.

Despite offering lightning-fast read queries, horizontal scalability of Mnesia is limited by its replication model: write throughput tends to decrease with the cluster size.  
EMQX is an MQTT message broker implemented in Erlang, which uses Mnesia to replicate its runtime state and configuration, and it makes full use of the data locality to deliver low-latency message routing at scale.  
We fixed the problems with the horizontal scalability by extending Mnesia replication protocol to support eventual consistency in a project called Mria.  
This project was a success: we tested EMQX clusters with 20+ nodes, routing messages between 100 millions of simultaneous clients and 50 millions unique topics.  
In this talk I will share some of the advanced coding and testing techniques that we used in this journey, including lock-free programming in Erlang and model checking with Concuerror.

**Talk objectives:** 

I will talk about Mnesia internals, lock-free programming from Erlang perspective and advanced testing techniques.

**Audience:**

Mnesia users.

***