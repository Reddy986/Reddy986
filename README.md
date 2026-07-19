# Hi, I'm Ajit Mahareddy 👋

I build and study practical ways to evaluate language-model products.

Right now I am learning **LLM evaluation in public**: turning product requirements into transparent datasets, graders, failure analyses, and reproducible model decisions.

## What I'm building

### [Open Product Evals](https://github.com/Reddy986/open-product-evals)

Small, inspectable evaluations for real product workflows.

The first experiment asks:

> Can a small local model reliably triage customer-support tickets—and catch the cases that need a human?

The repository includes a manually reviewed synthetic dataset, a published labeling policy, deterministic scoring, a zero-setup baseline, and a local Ollama runner. Version 0.2.2 publishes a complete decision cycle: a pre-committed prompt experiment, its rejection, a frozen held-out gate, and the resulting failed prototype decision.

**Latest decision:** Qwen3 4B passed the development gate but failed the one-time test gate because exact match was 60% against a pre-committed 70% threshold. The prototype was rejected, the raw failures were published, and the consumed test set was permanently marked as a regression suite.

**[Read the held-out decision](https://github.com/Reddy986/open-product-evals/tree/main/results/published/2026-07-18-qwen3-v1-held-out)**, **[try the 60-second baseline](https://github.com/Reddy986/open-product-evals#try-the-complete-eval-loop-in-60-seconds)**, or follow **[Learn LLM evals by doing](https://github.com/Reddy986/open-product-evals/blob/main/docs/EVALS_101.md)**.

## What I care about

- Product-specific evals instead of generic leaderboard scores
- Small and open-weight models when they are good enough
- Deterministic graders before model-based graders
- Human calibration for subjective judgments
- Failure slices and error analysis instead of one average score
- Reproducibility, honest limitations, and learning in public

## Current learning path

1. Objective classification and structured-output evals
2. Dataset design and failure taxonomies
3. Subjective rubrics and grader calibration
4. Regression testing and uncertainty
5. Model selection for real product constraints

If you work on LLM evaluations, open models, or AI product development, I would value your critiques and edge cases.

---

*The projects shared here are independent personal work and are not affiliated with or endorsed by any employer or model provider.*
