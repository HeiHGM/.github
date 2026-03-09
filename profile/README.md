# HeiHGM — Heidelberg Hypergraph Matching

We develop high-performance algorithms for b-matching in hypergraphs, including exact solvers, heuristics, and semi-streaming approaches.

## The Problem

A *hypergraph* generalizes a graph by allowing edges (called *hyperedges*) to connect any number of nodes, not just two. A *b-matching* assigns each node a capacity *b* and selects a maximum-weight subset of hyperedges such that no node appears in more than *b* selected hyperedges. This is a fundamental combinatorial optimization problem with applications in scheduling, resource allocation, reviewer assignment, and market design. Our algorithms tackle this problem at scale — from exact ILP formulations to fast streaming algorithms that process edges in a single pass with bounded memory.

## Projects

| Repository | Description |
|---|---|
| [**Streaming**](https://github.com/HeiHGM/Streaming) | Semi-streaming algorithms for hypergraph matching — swap-based, guarantee-stack, and lenient update strategies with provable approximation guarantees |
| [**Bmatching**](https://github.com/HeiHGM/Bmatching) | High-performance solver for b-matching problems in hypergraphs — greedy, ILS, ILP, and reduction-based pipelines |

## Quick Start

```console
brew install HeiHGM/bmatching/bmatching
bmatching_cli --graph input.hgr --algorithms greedy --capacity 5
```

