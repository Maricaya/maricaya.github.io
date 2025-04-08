---
layout: page
title: Research Projects
description: My research work and involvement
permalink: /research/
nav: true
nav_order: 3
---

## Differential Analysis in Scientific Computing

My research explores reproducibility and trace-based debugging in distributed systems. I am a co-author of the paper "Accurate Differential Analysis using Record and Selective Replay" (SSDBM 2025), led by Yuta Nakamura. This work addresses the challenge of comparing execution traces in parallel MPI applications, where tasks may exchange messages in a non-deterministic order. Our approach uses selective replay to reduce false positives by more than 50% when comparing execution runs, enabling more precise identification of divergence points in scientific applications. I contributed to the experimental design and evaluation of this method on real-world MPI benchmarks.

## Related Projects

I have been introduced to the [Floability Project](https://floability.github.io/), an NSF-funded research initiative led by Professor Tanu Malik. This project aims to enable the rapid and portable deployment of notebooks expressing complex scientific workflows across various cyberinfrastructure by addressing workflow incompleteness through capturing software dependencies, required datasets, and cluster hardware capabilities.

The Floability Project is a collaborative effort between the University of Notre Dame, the University of Missouri, and the University of Illinois, leveraging technologies like Jupyter, Sciunit, TaskVine, and Conda Forge.