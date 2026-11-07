# Project options (PROPOSED. None chosen)

These came out of early research and have not been compared with the team's own ideas yet. Earlier team ideas take precedence.

## A. SwarmTraces coordination forensics (Track Q4.1)
- Cluster payloads into coordination events using structural features: board/mailbox naming, controller election and lock patterns, agent-name co-occurrence.
- Hypothesis: structural features find coordination clusters with higher precision than keyword search.
- Baselines: a regex/keyword heuristic; an LLM reading single payloads.
- Positive control: recover patterns the Swarm Traces report already documents.
- Risks: no ground truth; dual-use. Analyse payloads as data only, never execute them, and never de-redact.

## B. Trusted monitoring vs multi-agent split attacks (Q4.4)
- K untrusted agents each contribute part of a solution, and one backdoor is split across contributions.
- Hypothesis: a per-contribution monitor loses safety as K grows, while a whole-trajectory monitor recovers some of it at a fixed audit budget.
- Baselines: upfront auditing; single-agent trusted monitoring.

## C. Partial-view collusion detection (Q4.3)
- Two agents collude using a simple codebook, and a monitor sees only a fraction p of their messages.
- Hypothesis: AUROC degrades as p falls; paraphrasing changes it by a measurable amount.
- Baselines: a full-view monitor; a random classifier; optionally NARCBench transcripts.
