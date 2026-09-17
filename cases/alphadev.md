# Faster sorting routines in a widely used library

**Published:** 2023-06-07 · **Category:** Computing · **System:** AlphaDev

**Evidence:** Published research · **Sources checked:** 2026-09-17

## What happened

DeepMind reported improved small sorting routines discovered with AlphaDev. Researchers translated the routines into C++ and incorporated improvements into LLVM libc++, a C++ standard library implementation. [1, 2]

## What AI did

A reinforcement-learning agent searched for efficient assembly instruction sequences, evaluated for correctness and performance. [1, 2]

## What humans did

Researchers designed the task and evaluation, examined the discovered routines, translated them, and worked through library integration. This was a research and software-engineering collaboration. [2]

## Evidence

1. [Nature paper](https://www.nature.com/articles/s41586-023-06004-9): algorithms and experimental evaluation. DOI: `10.1038/s41586-023-06004-9`.
2. [DeepMind technical account](https://deepmind.google/blog/alphadev-discovers-faster-sorting-algorithms/): algorithm discovery and links to library contributions.

## Limits

Gains apply to particular routines and test conditions, not all C++ programs. This case makes no universal speedup claim. It records the published integration milestone rather than auditing today's library implementation.

The paper landing page presented an access redirect during this check; the technical account was accessible. This repository has not rerun the benchmarks.

[Back to the collection](../README.md)
