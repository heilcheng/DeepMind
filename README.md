# Google Summer of Code 2025 — Google DeepMind

## About

This repository documents my work during Google Summer of Code 2025 with Google DeepMind on the Gemma project. Over the summer, I built open-source tools for evaluating large language models, with a focus on systematic benchmarking and domain-specific assessment.

---

## Blog

**How I Landed a Google DeepMind Project in Google Summer of Code 2025: A Step-by-Step Guide**

[Read on Medium](https://medium.com/@heilcheng2-c/how-i-landed-a-google-deepmind-project-in-google-summer-of-code-2025-a-step-by-step-guide-ccb2dee66769)

### Updates

- **May 7**: Got selected by Google DeepMind for the Gemma project.
- **May 8**: Got rejected by two other orgs.

I made my proposals public for anyone curious about the GSoC application process.

**What I submitted for DeepMind:**

- A proposal (see PDF in this repo)
- A blog post shared under the demo tag in the Gemma repo: [google-deepmind/gemma#244](https://github.com/google-deepmind/gemma/issues/244)

Feel free to reach out. Good luck to anyone applying for the 2026 batch.

---

## Projects

### OpenEvals

**Repository:** [github.com/heilcheng/openevals](https://github.com/heilcheng/openevals)

OpenEvals is an open-source evaluation framework for large language models. I built this to provide a standardized way to benchmark open-weight models across established academic tasks.

**What it does:**

- Runs models through standard benchmarks including MMLU, GSM8K, MATH, HumanEval, ARC, TruthfulQA, and more
- Compares performance across model families: Gemma, Llama, Mistral, Qwen, DeepSeek, and any model on HuggingFace
- Measures computational efficiency: latency, throughput, and memory usage
- Generates statistical analyses with confidence intervals
- Produces publication-ready visualizations and reports

**Why it matters:**

Evaluating language models is fragmented. Different papers use different evaluation setups, making comparisons unreliable. OpenEvals provides a unified framework so researchers can run consistent benchmarks and get reproducible results. This helps the community understand where models excel and where they fall short.

---

### MedExplain Evals

**Repository:** [github.com/heilcheng/medexplain-evals](https://github.com/heilcheng/medexplain-evals)

MedExplain Evals is a domain-specific evaluation framework for assessing how well language models explain medical information to patients and non-experts.

**What it does:**

- Evaluates model outputs on medical explanation tasks
- Measures accuracy, clarity, and safety of health-related responses
- Provides specialized benchmarks for healthcare use cases
- Includes a web interface for interactive evaluation

**Why it matters:**

General-purpose benchmarks do not capture how well models communicate medical information. This matters because health misinformation can cause real harm. MedExplain Evals provides targeted evaluation so developers can understand whether a model is suitable for patient-facing applications before deployment.

---

## Proposal

The original proposal submitted to Google DeepMind is included in this repository:

- [Comprehensive Benchmark Suite for Evaluating Gemma Models (PDF)](./Comprehensive%20Benchmark%20Suite%20for%20Evaluating%20Gemma%20Models.pdf)

---

## License

MIT
