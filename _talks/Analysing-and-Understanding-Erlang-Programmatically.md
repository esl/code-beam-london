---
audience:
- Intermediate
title: "Analysing and Understanding Erlang Programmatically"
speakers:
- _participants/Cons-T-Ahs.md

---
Code is being read more often than it is written, but who reads the code? Not only developers and the compiler, but also a large number of tools for analysing code. Analysis tools can be a great time saver, both by providing interactive help during development, but also for finding properties of code and change requests. This talk will focus on the latter where the main target of the results are other programmatic interfaces. Contents will include existing tools in OTP for analysis, pitfalls of analysis (with examples), why build tools and debug_info are your best friends when doing analysis. Additionally, there will a high level overview of code analysis tools for Erlang built in Erlang at WhatsApp. The use of these tools translate to saving developer time and other resources.

**Talk objectives:**

Analysing and understanding code and and changes to code contains more challenges than just looking at the source code (changes). Finding the right level of abstraction for doing the analysis, especially when it is done with programmatic interfaces in mind is important and can simplify the analysis. Finding the right point to do the analysis also decreases the number of languages one needs to understand.

**Target audience**

* Developers, tool makers
