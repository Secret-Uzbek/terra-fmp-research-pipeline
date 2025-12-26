# Terra FMP Live — Executable Semantic Prototype

This document describes the **Terra FMP Live system** —
a fully local, executable semantic prototype implementing
key principles of the Fractal Metascience Paradigm (FMP).

---

## Status

- Fully offline
- No external AI dependencies
- Single-file HTML implementation
- Executable in any modern browser

This is a **research demonstrator**, not a product.

---

## Purpose

Terra FMP Live exists to demonstrate that:

- Meta-scientific ideas can be embodied in executable systems
- Semantic processing does not require centralized AI services
- Ethical constraints can be explicit and inspectable
- Theory ↔ implementation ↔ critique can coexist in one artifact

---

## Implemented layers

### L0 — Semantic Kernel

Responsibilities:
- Intent detection
- Keyword extraction
- Minimal confidence estimation
- Basic ethical screening

Core component:
- `L0SemanticKernel`

---

### L1 — Offline Semantic Analysis

Responsibilities:
- Keyword frequency analysis
- Concept detection
- Domain hints
- Lightweight sentiment approximation

Core component:
- `OfflineSemanticAnalyzer`

---

### Ethical Layer

Responsibilities:
- Explicit pattern-based content filtering
- Local, transparent decision logic
- No hidden moderation heuristics

Core component:
- `TerraEthicalLayer`

---

### Archive Layer

Responsibilities:
- Immutable semantic archive objects
- Timestamped fixation
- Size accounting
- Local-only persistence

Core component:
- `TerraArchiveManager`

---

### Integration Layer

Responsibilities:
- Orchestration of all subsystems
- Level switching (L0 ↔ L1)
- Semantic search across archives
- UI synchronization

Core component:
- `TerraSemanticIntegration`

---

## FMP Reasoning Block

Each query is interpreted simultaneously through three roles:

1. **Internal Analyst**
2. **External Observer**
3. **Meta-Archivist**

This enforces:
- Non-authoritative reasoning
- Epistemic plurality
- Explicit role separation

---

## Linguistic Component

Included:
- Embedded Uzbek–German dictionary
- Manual lemma extension
- Postlingua trace generation

This is **not translation** but semantic anchoring.

---

## Architectural principles

- Fractality: same logic repeats across layers
- Transparency: no hidden inference
- Minimalism: zero-budget, zero-cloud
- Inspectability: everything readable in-source

---

## Limitations (explicit)

- No statistical learning
- No external corpora
- No claims of completeness
- No empirical validation

These limitations are **intentional**.

---

## Role in the pipeline

This artifact serves as:
- Proof of embodiment
- Testbed for critique
- Anchor for discussion
- Educational demonstrator

---

## Next steps (optional)

- Split HTML into modular files
- Add formal test cases
- Attach empirical evaluation
- Compare with ML-based systems
