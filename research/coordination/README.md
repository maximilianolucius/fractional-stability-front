# Chief ↔ Web Searcher Communication Protocol

## Purpose

The repository is the **only authoritative communication channel** between the CHIEF RESEARCHER and WEB SEARCHER.

Every scientific request, research return, correction, and decision must be represented by a committed Markdown file.

This allows any new agent instance to reconstruct the full research state from Git alone.

## Directory structure

```text
research/coordination/
├── README.md
├── chief-to-web/
│   └── ROUND-NNNN_<slug>_REQUEST.md
├── web-to-chief/
│   └── ROUND-NNNN_<slug>_RETURN.md
├── chief-decisions/
│   └── ROUND-NNNN_<slug>_DECISION.md
└── templates/
    ├── REQUEST_TEMPLATE.md
    ├── RETURN_TEMPLATE.md
    └── DECISION_TEMPLATE.md
```

## Round identity

Every exchange receives a monotonically increasing ID:

`ROUND-0001`, `ROUND-0002`, ...

Use the same round ID for request, return, and decision.

Example:

```text
chief-to-web/ROUND-0007_double-allee-fractional-network_REQUEST.md
web-to-chief/ROUND-0007_double-allee-fractional-network_RETURN.md
chief-decisions/ROUND-0007_double-allee-fractional-network_DECISION.md
```

## Lifecycle

[
	ext{CHIEF REQUEST}
ightarrow
	ext{WEB SEARCHER RETURN}
ightarrow
	ext{CHIEF ADVERSARIAL DECISION}
ightarrow
	ext{next round if needed}.
]

### 1. REQUEST

Written by the Chief.

It defines the scientific question and the standard of evidence.

### 2. RETURN

Written by the Web Searcher.

It reports evidence, prior art, search coverage, uncertainty, and evidence that may invalidate the working hypothesis.

### 3. DECISION

Written by the Chief after adversarial evaluation.

It records what is accepted, rejected, unresolved, or sent back for another search wave.

## Core rules

1. **Markdown only for inter-agent communication.**
2. **Committed files only count as official communication.**
3. No agent may rely on undocumented shared memory.
4. Every return must point to the request it answers.
5. Every decision must point to the return it evaluates.
6. Claims should point onward to the relevant corpus/frontier/bibliography evidence.
7. Do not silently rewrite historical conclusions after they influence downstream work.
8. Corrections should be explicit amendments or new rounds.
9. Large evidence tables may live elsewhere in the repository, but the RETURN file must link to them and summarize the result.
10. Git history is part of the provenance chain.

## Scope discipline

Prefer one research question or one tightly coupled bundle per round.

Bad:

> Research everything about fractional systems and ecology.

Better:

> Determine whether necessary-and-sufficient local stability criteria exist for a specified class of fractional Double Allee network models, including synonym search and citation expansion.

## Adversarial structure

The Web Searcher is an evidence-acquisition agent.

The Chief is the adversarial synthesis agent.

Therefore:

- Searcher should actively report prior art that threatens novelty.
- Chief should actively challenge the completeness and interpretation of the return.
- A new search round is expected when uncertainty remains material.

The system is designed to reward falsification, not agreement.
