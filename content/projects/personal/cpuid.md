---
title: "CPUID"
date: 2020-02-16T15:50:21-06:00
featured: true
description: "<ul><li>Used C++ and x86 Assembly to create a terminal application that reads CPU details</li><li>Learned to read large documentation manuals to understand a complex API</li><li>Practiced interfacing between low-level and high-level languages</li></ul>"
tags: ["C++","Assembly","Makefile"]
image: "img/cpuid.png"
link: "https://github.com/Preston12321/cpuid"
fact: "Learn about your CPU!"
weight: 500
sitemap:
  priority : 0.8
---

I started this project after becoming curious how hardware detection tools like [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html)
work. When I looked up the developers of the software, CPUID, I learned that their namesake was
also the name of an Assembly instruction that returns info about a machine's CPU! Since my Computer
Systems Organization class taught me about the inner workings of a processor and how Assembly
code works, I really wanted to see if I could write my own code to utilize the CPUID instruction.

This project gave me the opportunity to work with both C++ and Assembly together, something I had
also never done before. I learned how to interface between the two using what I had learned about
passing arguments between functions in lower-level languages like C/C++ and Assembly. Being
unfamiliar with highly technical documentation, it was also a learning experience navigating
Intel's [developer manuals](https://software.intel.com/content/www/us/en/develop/articles/intel-sdm.html)
to piece together how the CPUID instruction works.

Needless to say, modern processors are extremely complex with an immense amount of "feature flags",
so I was never able to implement the parsing of every possible "leaf" of info the CPU can return.
Nevertheless, this project stands as a proof-of-concept to show that I can parse dense documentation
and implement hybrid low-level and high-level solutions that interface with real hardware. It was
truly a fun project to hack on!
