# ICL-Kenyan-MoneyMarket-Returns

This notebook tests In-Context Learning (ICL) using a small language model to predict returns for Kenyan money market funds.

Inspired by the paper:  
**Self-Instruct: Aligning Language Models with Self-Generated Instructions**  
📄 https://arxiv.org/abs/2212.10560

---

## What this notebook does

- Runs a simple few-shot ICL experiment using a base model (`distilgpt2`)
- Compares:
  - Zero-shot prompt (no examples)
  - Structured ICL prompt (clear format)
  - Natural language style ICL prompt
---


