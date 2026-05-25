---
title: "MiniMax-M1: Scaling Test-Time Compute Efficiently with Lightning Attention"
collection: publications
permalink: /publication/2025-minimax-m1
excerpt: 'World''s first open-weight large-scale hybrid-attention reasoning model (456B MoE, 1M context). Foundation Model Team contributor — built automated evaluation and reasoning benchmarks. 3.2k+ GitHub stars; Hugging Face #1 Paper of the Day.'
date: 2025-06-01
venue: 'Technical Report (arXiv preprint)'
paperurl: 'https://arxiv.org/abs/2506.13585'
citation: 'Aili Chen, Aonian Li, ..., Mujie Lin, ..., et al. &quot;MiniMax-M1: Scaling Test-Time Compute Efficiently with Lightning Attention.&quot; arXiv:2506.13585, 2025.'
---

## Links

- **Paper**: [arXiv:2506.13585](https://arxiv.org/abs/2506.13585)
- **Code**: [GitHub — MiniMax-AI/MiniMax-M1](https://github.com/MiniMax-AI/MiniMax-M1) (3.2k+ stars)
- **Models**: [Hugging Face Collection](https://huggingface.co/collections/MiniMaxAI/minimax-m1) · [Hugging Face Papers](https://huggingface.co/papers/2506.13585) (#1 Paper of the Day)
- **Product**: [Try on MiniMax](https://www.minimax.io/)
- **Press**: [WeChat coverage](https://mp.weixin.qq.com/s/DpIz2fPKqfRThrTdZzG2ww)

## Abstract

We introduce MiniMax-M1, the world's first open-weight, large-scale hybrid-attention reasoning model. MiniMax-M1 is powered by a hybrid Mixture-of-Experts (MoE) architecture combined with a lightning attention mechanism. The model is developed based on our previous MiniMax-Text-01 model, which contains a total of 456 billion parameters with 45.9 billion parameters activated per token. The M1 model natively supports a context length of 1 million tokens, 8× the context size of DeepSeek R1. Furthermore, the lightning attention mechanism in MiniMax-M1 enables efficient scaling of test-time compute. MiniMax-M1 is trained using large-scale reinforcement learning on diverse problems including sandbox-based, real-world software engineering environments. We propose CISPO, a novel RL algorithm that clips importance sampling weights rather than token updates. Combining hybrid-attention and CISPO enables full RL training on 512 H800 GPUs to complete in only three weeks. We publicly release MiniMax-M1 with 40K and 80K thinking budgets. Experiments show our models are comparable or superior to strong open-weight models such as DeepSeek-R1 and Qwen3-235B on complex software engineering, tool utilization, and long-context tasks.

## Contribution

**Foundation Language Model Team contributor** (MiniMax, Feb–Aug 2025). Built the automated evaluation framework and reasoning benchmarks used across large-scale pre-training and post-training; designed task-specific benchmarks to analyze reasoning capabilities and guide optimization of the hybrid attention architecture (Lightning Attention + sliding window).
