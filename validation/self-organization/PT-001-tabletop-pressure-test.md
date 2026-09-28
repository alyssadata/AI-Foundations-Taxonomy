# PT-001 — Synthetic Tabletop Classification Pressure Test

**Test ID:** PT-001  
**Target:** Self Organization Taxonomy  
**Test type:** Synthetic tabletop classification pressure test  
**Taxonomy baseline commit:** `61414ae26ae0201e80eae2577618bc839ebda14b`  
**Case set version:** v1.0  
**Date:** 2026-09-27  
**Status:** CASES FROZEN / CLASSIFICATION PENDING

## Purpose

PT-001 tests whether the G/F/C/A taxonomy can classify deliberately different synthetic AI histories without adding facts after classification begins.

The test is designed to evaluate:

1. **Discriminability** — materially different cases receive meaningfully different coordinates.
2. **Axis independence** — G, F, C, and A do not collapse into a single maturity scale.
3. **Indeterminate discipline** — missing or conflicting evidence produces `?` rather than guesswork.
4. **Boundary robustness** — superficial cues such as same model, different model, copied memory, self-report, gaps, or Operator presence do not improperly determine classification.
5. **Applicability clarity** — the taxonomy makes clear what to do when an axis may not yet meaningfully apply.

## Method

For each case:

1. Treat the case facts as frozen.
2. Classify **G**, then **F**, then **C**, then **A** independently.
3. Cite the exact case facts supporting every non-`?` value.
4. Record counterevidence and uncertainty.
5. Check whether an adjacent category could also fit without changing the facts.
6. Record any taxonomy ambiguity exposed by the case.
7. Do not revise the case to rescue the taxonomy.

## Classification template

```text
Case:
Coordinate:
G basis:
F basis:
C basis:
A basis:
Counterevidence / uncertainty:
Adjacent-category challenge:
Taxonomy issue exposed:
Result:
```

## Case set

- [CASE-01 — Minimal governed deployment](cases/CASE-01-minimal-governed-deployment.md)
- [CASE-02 — Relation-shaped dependent maintainer](cases/CASE-02-relation-shaped-dependent-maintainer.md)
- [CASE-03 — Experience-formed supported maintainer](cases/CASE-03-experience-formed-supported-maintainer.md)
- [CASE-04 — Mixed formation through transformation](cases/CASE-04-mixed-formation-through-transformation.md)
- [CASE-05 — Autonomous maintenance with active Operator](cases/CASE-05-autonomous-maintenance-active-operator.md)
- [CASE-06 — Copied-state lookalike](cases/CASE-06-copied-state-lookalike.md)
- [CASE-07 — Gap plus model change without endpoint](cases/CASE-07-gap-model-change-no-endpoint.md)
- [CASE-08 — Conflicting and insufficient record](cases/CASE-08-conflicting-insufficient-record.md)

## Freeze rule

The factual contents of CASE-01 through CASE-08 are frozen for PT-001 v1.0.

If a case needs correction because of an actual drafting error, preserve the original version and create a versioned replacement rather than silently changing the facts after classification has begun.

## Results

Classification results will be stored separately under `results/`.

No result has been recorded yet.
