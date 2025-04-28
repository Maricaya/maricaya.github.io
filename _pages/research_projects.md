---
layout: page
title: research
description: My research work and involvement
permalink: /research/
nav: true
nav_order: 3
---

## Academia Research Experiences

### DePaul University DICE Lab (Advisor: Professor Tanu Malik)

#### Minimum Path Recovery Set (mPRS) for Trace Differencing (Jan 2024 – Present)
- Contributed to the mPRS algorithm that stores only the trace events strictly needed to reconstruct any execution path, formalising the problem, proving NP-hardness, and providing a fast heuristic plus an exact ILP solver
- Implemented mPRS as an LLVM pass; on 9 GNU Coreutils programs it instruments ≈ 62% fewer basic blocks and ≈ 82% fewer function calls than full tracing while keeping recovery loss-free
- Integrated mPRS into the SPADE provenance system, cutting emitted provenance events and speeding up differential-trace analysis without loss of accuracy

#### Accurate Differential Analysis using Record and Selective Replay (Apr 2024 – Mar 2025)
- Co-developed SelTraceReplay, a selective record-and-replay framework that aligns two distributed runs at runtime and extracts precise trace-level provenance
- Introduced loop-aware path IDs and dynamic message-ordering normalization to tame nondeterminism in MPI/HPC programs
- Improved divergence-localization accuracy by 30% over ReMPI while shrinking log size 20×; accepted at SSDBM '25 (second author)

#### AI-Assisted Debugging with Trace-Enhanced Prompts (Poster) (Jan 2025 – Apr 2025)
- Designed a workflow that feeds SelTraceReplay trace differences into LLM prompts to boost bug-localization suggestions
- In experiments with ChatGPT-4o, Gemini 1.5 Pro, and Claude 3.5 on four HPC benchmarks, trace-enhanced prompts raised the Jaccard similarity of predicted divergence points from 0.42 to 0.55 (+31%)

#### Parallel Audit and Reproduction of DAG Workflows (Apr 2024 – Aug 2024)
- Supported research on improving reproducibility in Sciunit through parallel auditing and repeating DAG workflows
- Set up and ran experiments to test Sciunit's performance in parallel auditing and workflow reproduction
- Collected data on system calls and dependencies to enhance audit accuracy and workflow efficiency
