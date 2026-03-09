# HeiHGM — Heidelberg Hypergraph Methods

We develop high-performance algorithms for b-matching in hypergraphs, including exact solvers, heuristics, and semi-streaming approaches.

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

## Contact

Heidelberg University, Institute of Computer Science
