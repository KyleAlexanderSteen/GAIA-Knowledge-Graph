# Knowledge Graph Evidence, Provenance, and Contradiction — Proposal

**Status:** Proposed; not approved or implemented.
**Canonical proposal:** https://github.com/KyleAlexanderSteen/GAIA-Documentation/blob/docs/alignment-attunement-self-improvement/GAIA-Documentation/GAIA-Universal-Principles-Integrity-Knowledge-and-Flourishing.md

## Candidate semantics

The graph should distinguish entities and relationships from the evidence asserted for those relationships. A graph edge must not imply truth merely because it exists. Claims or edges may need states such as proposed, sourced, corroborated, disputed, superseded, or invalidated, subject to approved ontology and contracts.

Candidate metadata to assess: source/evidence references and version; assertion origin (observed, imported, inferred, human-confirmed, or system-generated); valid/recorded time where relevant; confidence and method; contradicting evidence and alternative hypotheses; correction/supersession links; and downstream impact.

## Safeguards

- Preserve provenance through ingestion, normalization, and derived relationships.
- Avoid treating repeated copies of one source as independent corroboration.
- Support retraction or invalidation when evidence is corrected.
- Do not resolve disagreements using prestige or model confidence alone.
- Apply privacy, access, and retention rules to graph data and provenance.

Reconcile with GAIA-Ontology and approved Core contracts before schema or implementation work. No implementation is claimed.