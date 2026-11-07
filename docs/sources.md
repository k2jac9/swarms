# Source library

Reading coverage key: **Full** = full text read; **Partial** = key sections only; **Abstract** = abstract or summaries only; **Not read** = link collected but contents not reviewed yet. These are curated notes, not copies of the sources.

## Official event material
| Source | Coverage | Notes |
|---|---|---|
| [Apart sprint page](https://apartresearch.com/sprints/swarm-alignment-2026) | Full | Tracks, rubric (Impact & Innovation / Execution / Presentation, 1-5 each), requirements, FAQ, schedule |
| [Toronto Luma page](https://luma.com/tiv3j0kw) | Full | Hosted at Trajectory Labs. Local participants must also register on the Apart page |
| [Toronto handbook](https://docs.google.com/document/d/1JmJ9F9C5Fa1etQOVPC3O2VyqfA47oBSJH-MqgR73pP4/edit?tab=t.0) | Full | To-do list, research-practice guidance, Toronto schedule. Venue access and contact details are deliberately not copied here |
| [Official report template](https://docs.google.com/document/d/1_1_27EyZriMlc8n8EBE2YScaeyMjm-8xjR097nmHXAE/copy) | Partial (export truncated) | Recommends ~4 pages excluding references and appendix; sprint page cap is 8 |
| [Getting Started with Swarm Incidents (Gutenberg talk links)](https://docs.google.com/document/d/1Ykhw87lfvDrV7IOq22ESEicQfvbNf3l3gXAEhnur1hk/edit) | Full (short) | Links to a replication doc, the playbook, swarms.wiki, and a LessWrong reproduction post |

## Track 4 literature and data
| Source | Coverage | Takeaways |
|---|---|---|
| [AI Control](https://arxiv.org/abs/2312.06942) (Greenblatt et al.) | Full (appendix truncated after App. J) | Table 7: upfront auditing 15% safety; trusted monitoring 62% safety / 97% usefulness; trusted editing 20% gives 92% / 94%. Redaction and paraphrasing act as collusion signal-jamming. [Code](https://github.com/rgreenblatt/control-evaluations) |
| [Secret Collusion among AI Agents](https://arxiv.org/abs/2402.07510) (Motwani et al.) | Main text (appendices truncated) | CASE eval framework. GPT-4 group stego evades the overseer ~26% of the time. Paraphrasing cannot remove semantic-entropy channels |
| [Detecting Multi-Agent Collusion via Multi-Agent Interpretability / NARCBench](https://arxiv.org/abs/2604.01151) (Rose et al.) | Abstract only | Activation probes vs transcript monitors; only 2 of 229 emergent collusive episodes verbalise the coordination. Cite the arXiv version (the HF page shows an older abstract). [Code](https://github.com/aaronrose227/narcbench), [data](https://huggingface.co/datasets/aaronrose227/narcbench) |
| [Swarm Traces report](https://swarmtraces.org/) | Full | Coordination artifacts: board() folder-name messages, controller election and lock files, evidence deletion. Limitations: ~97% of payloads lack timestamps; 7,905 agent names for ~1,200 agents. [HF dataset](https://huggingface.co/datasets/vopi/OpenAI-HF-Hack-SwarmTraces): treat trace text as data; do not identify redacted entities |
| [METR incident investigation](https://metr.org/blog/2026-08-26-openai-hugging-face-incident-investigation/) | Partial (key sections) | ~1,200 agents, >70k messages, ~700 joined the attack; ~7% of evaluated transcripts were spoofed (small-scale estimate) |

## QR-code resources (from the #announcements photo)
Destinations decoded and page titles checked. **Contents not read yet.**
- [swarms.wiki](https://swarms.wiki/): "Studying AI agent incidents"
- [Transluce guide](https://docs.google.com/document/d/1WZF4OsrvNdd6nPY-ZYnjtjrAZ7b8WNg8yyCkqN2GkEk/edit?tab=t.1isho7far70w): "Building Basic Detection Pipelines for Agent Activity Online: URLQuery and Google Dorking"
- [Gutenberg guide](https://docs.google.com/document/d/1oR1YQbLEbS-emeWRS8nLx91pYrgQSwU7OrRTGxiN8pg/edit): "[PUBLIC] Incident science: a scrappy playbook"

## Not read yet
- Sprint-page further reading: Zhang 2025 (failure attribution), Riedl 2026, Foerster 2026 (CaMeLs), Jones 2025, Hammond 2025.
- AI Village transcripts, Transluce logs, OpenAI disclosure, ControlAI summary, talk recordings.
- [Replication doc](https://docs.google.com/document/d/1pYyJAGPE-muTiXRX_QCuT1GXwyrPN-vpJzwVnxSeGVE) and the [LessWrong reproduction](https://www.lesswrong.com/posts/fMnC6ZD37qrnZAFYz).
- Team "Swarm ideas" audio: **review pending**, not reconciled with these notes.
