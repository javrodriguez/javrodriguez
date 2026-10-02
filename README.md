## Javier Rodríguez Hernáez

Formerly Senior Bioinformatics Programmer at NYU Langone (2018–2026); now independent and **open to contract and full-time work** in AI for science and genomics. 8 years of multi-omics research. I build **AI systems scientists can check**: code that stops on a confounded design or a missing decision, a person's yes on the study design, an analysis plan whose approval is bound to its exact bytes, a project history that records each step and names the model when the agent reports it, and pre-registered evaluations that measure where the agent holds and where it fails, published as measured.

AI can now build an end-to-end pipeline and run a genomics analysis astonishingly fast. That has moved the bottleneck to supervision and validation: judging where the agent should go, then proving what it produced. Judgment and evaluation are now the most critical skills, and they're where I spend most of my time. I build AI systems up through evaluation gates: an AI feature goes into use only once an evaluation shows it makes the research faster or more accurate.

**🔭 Flagship: [GARS — Genomics Agentic Research System](https://github.com/javrodriguez/genomics-agentic-research-system).** Genomics analysis an AI agent can run and a scientist can check. GARS lets an AI agent run real genomics pipelines inside a folder of written rules: tested code does the computing, a scientist makes the decisions, and each project keeps an append-only record of every step and the model that took it.

- **Code computes, not the model:** pinned nf-core pipelines and tested scripts; under Claude Code, a guard on every file and shell call: the shell runs only GARS's registered tools, the agent cannot write the system's own files, and a call it cannot judge is refused.
- **You decide, on the record:** it never picks your reference or contrast, refuses confounded designs, and binds a custom analysis's approval to the plan's exact bytes; the Methods paragraph is rendered from the run's own records.
- **Checked against the real world:** scored against published data, where it flagged a failed replicate the paper's QC could not see.

Next, not claimed until shown: the same rules under other agents and models, with the outputs compared.

**[▶ Watch a recorded run](https://gars.javrodriguez.dev/demo/)** · [check it in 5 minutes](https://gars.javrodriguez.dev/try/) · [evidence and limits](https://gars.javrodriguez.dev/evidence/)

**🔬 Measuring where the AI fails:**

- [The Gap Study](https://github.com/javrodriguez/genomics-agentic-research-system/blob/main/docs/EVALS.md#the-gap-study) — a pre-registered, controlled study of the GARS agent: six failure-mode tasks, each with a control, on three Claude models; 108 graded takes, frozen before the first take with every amendment recorded, regraded without calling a model, and published exactly as graded: 2 of 18 model–task cells held; round 2, with the instrument fixed before its freeze: 5 of 18 task-model pairs held.
- [Validity arguments](https://github.com/javrodriguez/genomics-agentic-research-system/tree/main/docs/validity) — does each Gap Study task measure what it claims? One signed page per task, checked against a published checklist for agentic benchmarks, including where the graders fall short.
- [Recompute it yourself](https://github.com/javrodriguez/genomics-agentic-research-system/tree/main/reproduction/gse58638) — one command re-derives the failed-replicate finding from the authors' own GEO deposit; it runs green on GitHub's machines.
- [BixBench answer-key audit](https://github.com/javrodriguez/bixbench-audit) — a public audit of ten answer keys in BixBench, a benchmark for AI agents in computational biology: each re-derived from its data, pre-registered, run twice in a pinned environment and adversarially reviewed; 1 incorrect answer key and 6 questions needing clearer wording, plus a normalisation issue in one reference notebook.
- [PeerPanel](https://github.com/javrodriguez/peerpanel) — a multi-agent scientific-review system built to be measured: planted defects scored by a committed rule with its own negative control, per-call run conditions on every record, and the result published as the record shows it — a null.

**🔌 Tools:** [HiC-MCP](https://github.com/javrodriguez/hic-mcp) — Hi-C / 3D-chromatin analysis for AI agents. An MCP server exposing the open2c stack (cooler, cooltools) over local contact matrices, with a real Micro-C dataset bundled so it runs offline.

**📄 Research frameworks:**

- [Ensemble NeuralODE GRNs in primary AML](https://github.com/javrodriguez/aml-neuralode-ensemble-grn) — NeuralODE training, ChIP validation and influence pipelines for regulatory-network inference
- [Nanopore HBV–HCC integration framework](https://github.com/javrodriguez/hbv-hcc-ont-manuscript) — 29-module long-read pipeline for viral integration, structural variants and methylation

**🧬 Research line:** deep-learning models of 3D chromatin ([C.Origami extensions](https://github.com/javrodriguez/C.Origami_vGeneric)) + [in-silico genetic screens across 155 B-ALL patient samples](https://github.com/javrodriguez/ISGS_BALL).

**🔧 Open source:** long-time maintainer and #2 contributor (150+ commits) of [NYU-BFX/hic-bench](https://github.com/NYU-BFX/hic-bench) — Hi-C and HiChIP analysis pipelines used across NYU labs.

**⚙️ How I build:** agentic engineering as daily practice — Claude Code as the driver, worktree-isolated parallel sessions with merge gates, and eval-driven development: work is reviewed by independent fresh-context evaluators and re-evaluated until it converges. What that discipline produces is public — an append-only [decision log](https://github.com/javrodriguez/genomics-agentic-research-system/tree/main/docs/decisions), a [reproduction campaign](https://github.com/javrodriguez/genomics-agentic-research-system/blob/main/docs/reproduction-campaign.md) on public GEO cohorts whose [results](https://github.com/javrodriguez/genomics-agentic-research-system/blob/main/docs/RESULTS.md) include a failed immunoprecipitation in published data that the original depth-only QC could not have seen, and the [upstream defects](https://github.com/javrodriguez/genomics-agentic-research-system/tree/main/docs/upstream) it surfaced. My day-to-day project management runs on an open-source, local-first agentic second brain (someone else's framework — persistent memory, deterministic hooks, background workers) that I run daily and extend with my own skills and tooling. Deterministic code gathers, validates and writes; the model reasons only where judgment is genuine.

Shared first author, *Molecular Cell* (2025) · [Publications](https://www.ncbi.nlm.nih.gov/myncbi/1X137yzukYKAC/bibliography/public/) · [LinkedIn](https://www.linkedin.com/in/jrodriguezhernaez/)
