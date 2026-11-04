# Improving Mathematical Reasoning in Large Language Models for Persian

This repository contains the implementation and experiments of a master's thesis focused on improving mathematical reasoning in Large Language Models (LLMs), particularly for Persian-language mathematical problems.

## Research Overview

The research explores techniques to improve multi-step mathematical reasoning through:

- **Prompt Engineering:** Chain-of-Thought (CoT) prompting.
- **Supervised Fine-Tuning (SFT):** Adapting pre-trained models using mathematical datasets.
- **Reinforcement Learning:** Applying Group Relative Policy Optimization (GRPO).

## Dataset

Persian mathematical question-answering datasets, including Persian adaptations of GSM8K-style problems.

## Evaluation

Models are evaluated using the [EleutherAI lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness), with a focus on Exact Match (EM) accuracy.

## Technologies

- Python & PyTorch
- Hugging Face Transformers
- Unsloth & TRL
- PEFT / LoRA
- lm-evaluation-harness

## Repository Structure

```text
reasoning/
├── eval/                  # Evaluation scripts and resources
├── fine tuning/           # Fine-tuning experiments
└── README.md
```

## Author

**Arefeh Rajabian**

M.Sc. in Computer Engineering – Software Engineering  
Iran University of Science and Technology (IUST)
