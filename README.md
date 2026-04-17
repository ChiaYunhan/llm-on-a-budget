# llm-on-a-budget

Personal research repo documenting experiments in local LLM hosting,
cloud model benchmarking, and LLM-assisted code generation — all on
consumer hardware and a tight budget.

---

## Goals

### 1. Local LLM Hosting

- Understand and identify inference bottlenecks on consumer hardware (M4 MacBook Air)
- Identify key metrics: TTFT, tokens/sec, KV cache behaviour, GPU layer offloading
- Document quantization tradeoffs (Q4 vs Q8 vs fp16) on real hardware

### 2. Benchmarking Pipeline

- Learn how to objectively measure LLM output
- Build a reproducible eval suite
- Identify and track meaningful metrics beyond vibes-based comparison

---

## Setup

- **Hardware:** Apple MacBook Air M4, 16GB unified memory, 10 core cpu gpu
- **Models tested:** _(updated as experiments run)_

---

## Structure

- `benchmarks/` — results, methodology, plots
- `experiments/` — write-ups for each experiment
- `scripts/` — benchmark runners and result parsers
- `logs/` — dated session notes and discoveries
