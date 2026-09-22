## Javier Rodriguez Hernaez

Senior Bioinformatics Programmer at NYU Langone. 8 years of multi-omics research; now building **trustworthy AI systems for genomics** — reproducible workflows, provenance, human approval gates on the study design and the analysis plan, and pre-registered evaluations that measure where AI fails and where it adds real value, published as measured.

AI can now build an end-to-end pipeline and run a genomics analysis astonishingly fast. That has moved the bottleneck to supervision and validation: judging where the agent should go, then proving what it produced. Judgment and evaluation are now the most critical skills, and they're where I spend most of my time. I build AI systems up through evaluation gates: an AI feature goes into use only once an evaluation shows it makes the research faster or more accurate.

**🔭 Flagship:** [GARS — Genomics Agentic Research System](https://github.com/javrodriguez/genomics-agentic-research-system) — reproducible bioinformatics workflows through an LLM agent on HPC, where the filesystem is the state machine, stage contracts constrain the agent, and scientific decisions stay with the human · **[▶ try the interactive demo](https://gars.javrodriguez.dev/)** — recorded real runs, playable human gate, in the browser.

**🔬 Measuring where the AI fails:**

- [The Gap Study](https://github.com/javrodriguez/genomics-agentic-research-system/blob/main/docs/EVALS.md#the-gap-study) — a pre-registered, controlled study of the GARS agent: six failure-mode tasks, each with a control, on three Claude models; 108 graded takes, frozen before the first take with every amendment recorded, regraded without calling a model, and published exactly as graded: 2 of 18 model–task cells held.
- [PeerPanel](https://github.com/javrodriguez/peerpanel) — a multi-agent scientific-review system built to be measured: planted defects scored by a committed rule with its own negative control, per-call run conditions on every record, and the result published as the record shows it — a null.

**🔌 Tools:** [HiC-MCP](https://github.com/javrodriguez/hic-mcp) — Hi-C / 3D-chromatin analysis for AI agents. An MCP server exposing the open2c stack (cooler, cooltools) over local contact matrices, with a real Micro-C dataset bundled so it runs offline.

**📄 Research frameworks:**

- [Ensemble NeuralODE GRNs in primary AML](https://github.com/javrodriguez/aml-neuralode-ensemble-grn) — NeuralODE training, ChIP validation and influence pipelines for regulatory-network inference
- [Nanopore HBV–HCC integration framework](https://github.com/javrodriguez/hbv-hcc-ont-manuscript) — 29-module long-read pipeline for viral integration, structural variants and methylation

**🧬 Research line:** deep-learning models of 3D chromatin ([C.Origami extensions](https://github.com/javrodriguez/C.Origami_vGeneric)) + [in-silico genetic screens across 155 B-ALL patient samples](https://github.com/javrodriguez/ISGS_BALL).

**🔧 Open source:** long-time maintainer and #2 contributor (150+ commits) of [NYU-BFX/hic-bench](https://github.com/NYU-BFX/hic-bench) — Hi-C and HiChIP analysis pipelines used across NYU labs.

**⚙️ How I build:** agentic engineering as daily practice — Claude Code as the driver, worktree-isolated parallel sessions with merge gates, and eval-driven development: work is reviewed by independent fresh-context evaluators and re-evaluated until it converges. What that discipline produces is public — an append-only [decision log](https://github.com/javrodriguez/genomics-agentic-research-system/tree/main/docs/decisions), a [reproduction campaign](https://github.com/javrodriguez/genomics-agentic-research-system/blob/main/docs/reproduction-campaign.md) on public GEO cohorts whose [results](https://github.com/javrodriguez/genomics-agentic-research-system/blob/main/docs/RESULTS.md) include a failed immunoprecipitation in published data that the original depth-only QC could not have seen, and the [upstream defects](https://github.com/javrodriguez/genomics-agentic-research-system/tree/main/docs/upstream) it surfaced. My day-to-day project management runs on an open-source, local-first agentic second brain (someone else's framework — persistent memory, deterministic hooks, background workers) that I run daily and extend with my own skills and tooling. Deterministic code gathers, validates and writes; the model reasons only where judgment is genuine.

Shared first author, *Molecular Cell* (2025) · [Publications](https://www.ncbi.nlm.nih.gov/myncbi/1X137yzukYKAC/bibliography/public/) · [LinkedIn](https://www.linkedin.com/in/jrodriguezhernaez/)
