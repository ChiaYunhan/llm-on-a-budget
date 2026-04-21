# Open Questions

A running list of things I'm confused about and want to dig into. Entries get added as I bump into them, and crossed out / moved to an "Answered" section as I figure them out.

## MoE & Model Architecture

- Why does MoE have **active params** vs total params? How does the router decide which experts to fire?
- Why is `gemma4:e4b` _larger_ on disk (9.6 GB) than `Qwopus3.5:9b` (6.5 GB) despite having fewer "b" in its name? Different quantization levels? Different architectures?

## KV Cache

- Is the KV cache **per-conversation** or shared across requests?
- What happens to it when I hit the context window limit?

## Quantization

- Does quantization happen **at training time** or after (post-training quantization)? Are there different flavors?
- Is there a meaningful quality difference between Ollama's default quantization and what I could pick manually?

## Memory & Sizing

- How do I calculate the actual **memory footprint** of a model at runtime (weights + KV cache + overhead)?

## Ollama Parameters

- What's the difference between `num_ctx`, `num_predict`, and `num_batch` in Ollama?

---

## Answered

_(nothing yet — move items here with a short answer + link to the journal entry where I figured it out)_
