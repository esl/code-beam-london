---
tags:
- Observability, Tracing, Instrumentation
level: Intermediate users, Proficient users
title: "Distributed Tracing on the BEAM"
speakers:
- _participants/zack-kayser.md

---
Distributed tracing is an essential component to well-instrumented, modern day applications where requests often span across network boundaries and services. Tracing across HTTP services is a relatively common form of distributed tracing and generally works by passing contextual information about a trace in HTTP headers. The OpenTelemetry Specification incorporates a concept known as ""Context Propagation"" that describes this type of mechanism for passing context about an ongoing trace to other services and processes, regardless of where they are running. In OpenTelemetry, we can create our own ""Propagators"" to pass this context along in novel ways that aren't just sending contextual information in HTTP headers.

So what does that have to do with the BEAM?
On the BEAM, we are constantly crossing process boundaries. Once we've instrumented our applications with traces, we now have the need to pass trace context
across those process boundaries. That means we are dealing with a form of distributed traces all of the time –– even if those processes are running on the same machine!

The need for novel ways to pass trace context along for distributed traces on the BEAM doesn't end there. What if you want distributed traces on messages
being passed between distributed Erlang nodes? If you're sending a message to a GenServer running on another node, how do you propagate your trace context along from the caller node? How about tying together producers and consumers in a GenStage pipeline? And what about working with LiveView -- what if you want to tie client and server spans together in a single trace?

In this talk we'll explore the concepts needed to tackle these problems and point out some of the sharp edges you may want to avoid.

**TALK OBJECTIVES:**
1. Raise awareness of how distributed tracing is essential to well-instrumented BEAM applications
2. Provide the viewers with some background on what distributed tracing is, how it generally works, and how to incorporate it into day-to-day tasks while working in BEAM languages.

**TARGET AUDIENCE:**
- Elixir, Erlang, and other BEAM language engineers who have some familiarity with observability engineering (particularly tracing) will benefit the most from this talk.
- Engineering managers and technical leads considering using a BEAM language for a new production project should also find the topics covered in this topic insightful.
