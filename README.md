# Hi, I'm Ajit Mahareddy 👋

I build and study practical ways to evaluate language-model products.

Right now I am learning **LLM evaluation in public**: turning product requirements into transparent datasets, graders, failure analyses, and reproducible model decisions.

## What I'm building

### [Open Product Evals](https://github.com/Reddy986/open-product-evals)

Small, inspectable evaluations for real product workflows.

The first experiment asks:

> Can a small local model reliably triage customer-support tickets—and catch the cases that need a human?

The repository includes a manually reviewed synthetic dataset, a published labeling policy, deterministic scoring, a zero-setup baseline, and a local Ollama runner. Version 0.2.1 publishes the first reproducible open-model comparison, including raw outputs, failure analysis, runtime details, and honest limitations.

**Latest finding:** Qwen3 4B was more accurate than Gemma 3 4B on the 40-ticket development set, while Gemma 3 was about 21 times faster by median latency. This is development evidence, not a production-safety claim.

**[Read the model decision](https://github.com/Reddy986/open-product-evals/tree/main/results/published/2026-07-18-open-model-comparison)**, **[try the 60-second baseline](https://github.com/Reddy986/open-product-evals#try-the-complete-eval-loop-in-60-seconds)**, or follow **[Learn LLM evals by doing](https://github.com/Reddy986/open-product-evals/blob/main/docs/EVALS_101.md)**.

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
