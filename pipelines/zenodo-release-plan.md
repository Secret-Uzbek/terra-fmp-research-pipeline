# Zenodo Release & DOI Strategy

**Repository:** Terra FMP Research Pipeline  
**Author:** Abdurashid Abdukarimov  
**Purpose:** Establishing a citable academic release mechanism

---

## 1. Why a Zenodo Release Is Used

This repository is a living research pipeline.
However, academic discourse requires **stable, citable snapshots**.

Zenodo provides:

- DOI assignment
- long-term archival storage
- versioned releases
- compatibility with academic citation practices
- visibility via OpenAIRE

Zenodo is therefore used as the **citation anchor**, not as a development platform.

---

## 2. What Is Considered a Citable Artifact

A Zenodo release of this repository represents:

- a **time-bound integration snapshot**
- not a claim of final theory
- not a peer-reviewed publication
- a reproducible research state

Each release corresponds to a **research phase**, not a product milestone.

---

## 3. Scope of the First Zenodo Release

**Release title (proposed):**  
*Fractal Metascience Paradigm (FMP): Research Pipeline Snapshot v0.1*

**Included components:**

- `theory/`
- `pipelines/`
- `implementations/`
- `MANIFEST.md`
- `PIPELINE.md`
- `README.md`
- `discussions/academic-critique-invitation.md`

**Explicitly excluded:**

- unfinished drafts marked as experimental
- private notes
- external repositories

---

## 4. Versioning Policy

Versioning follows a **semantic–epistemic model**, not software semantics.

- `v0.x` — exploratory integration snapshots
- `v1.0` — conceptually stable framework definition
- `v1.x` — refined or expanded theoretical releases
- `v2.0+` — major paradigm-level restructuring

A version does **not** imply correctness — only stability.

---

## 5. Release Triggers

A Zenodo release is created when:

- a coherent integration snapshot exists
- MANIFEST.md reflects repository contents accurately
- PIPELINE.md documents the research logic
- discussion entry points are available
- no critical structural inconsistencies are known

Releases are **intentional**, not automatic.

---

## 6. GitHub–Zenodo Integration

Procedure:

1. Connect GitHub repository to Zenodo
2. Enable DOI generation for releases
3. Create a GitHub Release with:
   - version tag
   - short epistemic description
4. Zenodo automatically archives and assigns DOI
5. DOI is referenced in:
   - README.md
   - future publications
   - academic profiles (e.g., ORCID)

---

## 7. Citation Format (Proposed)

```text
Abdukarimov, A. (Year).
Fractal Metascience Paradigm (FMP): Research Pipeline Snapshot vX.X.
Zenodo. https://doi.org/DOI_PLACEHOLDER
This format may be adapted to journal requirements.

8. Relationship to Peer Review
Zenodo releases:

do not replace journals

do not bypass peer review

serve as referenceable research artifacts

enable transparent critique prior to formal publication

Peer-reviewed papers may later reference these releases.

9. Archival Philosophy
Each Zenodo release is treated as:

immutable

historically traceable

citable even if later rejected or superseded

Scientific progress includes discarded paths.

They are not erased.

10. Status
This document defines the canonical DOI strategy for the Terra FMP Research Pipeline.

No release is created automatically.
Each release is a deliberate research act.

yaml
Копировать код

---

## Шаг 21.3 — Commit message

```text
add zenodo release and DOI strategy

---
<!-- TERRA_IDENTITY_POSTFIX v1 -->
**Contact:** a.abdukarimov@fractal-metascience.org
**ORCID:** 0009-0000-6394-4912

