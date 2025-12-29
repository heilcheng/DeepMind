# Google Summer of Code 2025 / Google DeepMind

## About

Work done during Google Summer of Code 2025 with Google DeepMind on the Gemma project. Built tools for evaluating large language models. Focused on systematic benchmarking and domain-specific assessment.

This repository is hosted at [haileycheng.com/DeepMind/](https://haileycheng.com/DeepMind/)

## Blog

**How I Landed a Google DeepMind Project in Google Summer of Code 2025: A Step-by-Step Guide**

[Read on Medium](https://medium.com/@heilcheng2-c/how-i-landed-a-google-deepmind-project-in-google-summer-of-code-2025-a-step-by-step-guide-ccb2dee66769)

### Updates

- **May 7:** Selected by Google DeepMind for the Gemma project.
- **May 8:** Rejected by two other orgs.

Proposals are public for anyone curious about the process.

**Submission for DeepMind:**

- A proposal (PDF attached)
- A blog post under the demo tag in the Gemma repo: [google-deepmind/gemma#244](https://github.com/google-deepmind/gemma/issues/244)

Good luck for your GSoC 2026 application.

## Projects

### OpenEvals

**Repository:** [github.com/heilcheng/openevals](https://github.com/heilcheng/openevals)

**Documentation:** [haileycheng.com/openevals](https://haileycheng.com/openevals)

OpenEvals is a framework for LLM evaluation. Standardized benchmarking across academic tasks.

**Functionality:**

- Runs standard benchmarks: MMLU, GSM8K, MATH, HumanEval, ARC, TruthfulQA
- Compares model families: Gemma, Llama, Mistral, Qwen, DeepSeek, HuggingFace
- Measures efficiency: latency, throughput, memory
- Statistical analyses with confidence intervals
- Publication-ready visualizations

**Significance:**

Evaluation is fragmented. OpenEvals unifies it. Consistent benchmarks. Reproducible results.

### MedExplain Evals

**Repository:** [github.com/heilcheng/medexplain-evals](https://github.com/heilcheng/medexplain-evals)

**Documentation:** [haileycheng.com/medexplain-evals](https://haileycheng.com/medexplain-evals)

Domain-specific framework. Assessing model explanations of medical info for non-experts.

**Functionality:**

- Evaluates medical explanation tasks
- Measures accuracy, clarity, safety
- Specialized benchmarks
- Interactive web interface

**Significance:**

General benchmarks miss medical nuances. Misinformation harms. Targeted evaluation for patient-facing applications.

## Proposal

Original proposal submitted to Google DeepMind:

- [Comprehensive Benchmark Suite for Evaluating Gemma Models (PDF)](./Comprehensive%20Benchmark%20Suite%20for%20Evaluating%20Gemma%20Models.pdf)

## License

MIT
