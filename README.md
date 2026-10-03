# ExchangeLab

ExchangeLab is a planned C++20 limit-order-book simulator for learning about quantitative engineering, market microstructure and performance-aware software development.

The project will simulate the submission, cancellation and matching of financial orders. It will not connect to a real exchange or use real money.

## Problem

Electronic exchanges must process orders according to clearly defined matching rules while maintaining correctness and predictable performance.

ExchangeLab will explore how these systems can be represented using appropriate algorithms and data structures.

## Planned behaviour

The simulator will eventually support:

- Limit buy and sell orders
- Market orders
- Order cancellation
- Price-time priority
- Partial order fills
- Trade-event generation
- Deterministic replay from an input file
- Performance benchmarks
- Python-based analysis of simulated trades

## Planned technology

- C++20
- CMake
- Catch2 or GoogleTest
- Compiler warnings
- Address and undefined-behaviour sanitizers
- Google Benchmark
- Python
- pandas
- Docker
- GitHub Actions

## Engineering principles

The project will prioritise:

1. Correctness
2. Automated testing
3. Reproducibility
4. Clear documentation
5. Measurement before optimisation

The project will not claim to be a production exchange or genuinely low-latency system.

## Current status

Planning and repository setup.

No matching engine has been implemented
