# Post-Training

## Simple Definition

Post-training is the stage after pre-training where a model is taught how to behave more usefully, safely, and in line with human or task-specific expectations.

## Human Analogy

Pre-training gives the model broad knowledge. Post-training teaches it how to act like a useful assistant.

## Why It Matters

Modern LLM quality is not only about pre-training scale. A lot of the user experience comes from post-training: instruction following, reasoning style, refusal behavior, tool use, preference alignment, and domain adaptation.

## Common Techniques

- Supervised Fine-Tuning (SFT)
- Reinforcement Learning from Human Feedback (RLHF)
- Direct Preference Optimization (DPO)
- Reinforcement learning for reasoning or tool use
- Preference data and ranking
- Safety tuning

## Product Lens

Post-training explains why two models with similar base capabilities can feel very different in real use. It also explains why enterprise AI may need domain-specific examples, feedback loops, and evaluation datasets.

## Important Distinction

Post-training is not the same as RAG.

- RAG adds external context at inference time.
- Post-training changes model behavior through training.

## Violet Connection

This is useful for understanding model behavior, AI product quality, prompt design, model selection, and why different AI products produce different user experiences.

## Public References

- PyTorch — A Primer on LLM Post-Training

---

## How to Use This Note

- Keep this file as the polished concept note.
- Put messy course notes in `30_LEARNING/`.
- When a concept becomes useful for a project, link it from `20_PROJECTS/` or a separate implementation repo.

## Update Log

- Created: 2026-06-25
