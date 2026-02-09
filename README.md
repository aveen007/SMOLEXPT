Here's a short README for your project:

---

# Instruction Sensitivity Analysis in Vision-Language Models

This repository contains code and experiments for analyzing instruction sensitivity in vision-language models (VLMs), focusing on embedding consistency for semantically equivalent instructions.

## Overview

Vision-language models often produce varied internal representations for instructions with the same semantic meaning when conditioned on the same image. This project:

1. **Identifies** the instruction sensitivity problem in SMOLVLM
2. **Quantifies** embedding divergence through similarity metrics
3. **Proposes** a Contrastive Instruction Alignment Adapter (CIAA) to improve consistency

## Key Findings

- Semantically equivalent instructions produce embeddings with average similarity of 0.837 (below the 0.9-1.0 expected range)
- CIAA improves within-group similarity while reducing between-group similarity
- The within/between similarity ratio improves by 28.6% with CIAA

## License

MIT License

---
