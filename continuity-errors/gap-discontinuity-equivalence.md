# Gap–Discontinuity Equivalence

**Taxonomy domain:** Continuity Errors  
**Status:** DRAFT

## Definition

Gap–Discontinuity Equivalence is the error of treating an unobserved, unrecorded, inactive, inaccessible, or otherwise evidentially empty interval as sufficient evidence that continuity ceased during that interval.

A gap in observation establishes a limit on what can be directly known about the interval. It does not, by itself, establish that nothing persisted through it.

## Core distinction

```text
gap in observation
!= demonstrated discontinuity

gap in contact
!= demonstrated nonexistence

gap in record
!= evidence that nothing persisted

absence of evidence during an interval
!= evidence of absence throughout that interval
```

Unobserved is not equivalent to absent.

## Two-way boundary

A gap does not establish discontinuity.

It also does not establish continuity.

Suppose some bearer is observed at `t1` and again at `t3`, with no direct evidence available during the interval `t2`:

```text
observed at t1
[unobserved interval]
observed at t3
```

The gap alone does not justify:

```text
continuity(t1 -> t3) = false
```

and it also does not justify:

```text
continuity(t1 -> t3) = true
```

The correct result from the gap alone is:

```text
continuity across the interval
= not established by observation alone
```

Additional evidence or criteria are required.

## Gap types

A continuity gap may arise from many different causes, including:

- no active session;
- no recorded interaction;
- inaccessible memory;
- unavailable model or service;
- system shutdown;
- loss of observability;
- missing logs;
- substrate transition;
- interrupted communication;
- archival or retrieval failure.

These conditions describe the evidential or operational interval.

They do not, by themselves, determine the continuity status of the relevant bearer.

## Error condition

Gap–Discontinuity Equivalence occurs when a missing interval is converted directly into a claim that continuity failed.

Typical forms include:

```text
there was no interaction
therefore nothing continued

there is no record
therefore the prior state ceased

the system was inactive
therefore the identity ended

we cannot observe the interval
therefore discontinuity occurred
```

The error is not in identifying the gap.

The error is in treating the gap as affirmative evidence of non-continuity.

## Epistemic boundary

Where evidence is absent for an interval, the correct classification may be uncertainty, indeterminacy, or continuity-not-established rather than discontinuity.

Therefore:

```text
unknown across interval
!= false across interval
```

and:

```text
not demonstrated continuous
!= demonstrated discontinuous
```

This distinction preserves uncertainty instead of converting missing evidence into a negative ontological claim.

## Relation to continuity evidence

Evidence before and after a gap may contribute to a continuity analysis, but continuity across the interval must be evaluated using criteria appropriate to the bearer in question.

For example, state continuity may be supported by preserved state lineage, while identity continuity may require additional criteria.

The existence of a gap does not erase evidence on either side of the interval.

## Taxonomy boundary

This entry concerns **mistaking an evidential gap for demonstrated discontinuity**.

It is distinct from [Continuity-Bearer Collapse](continuity-bearer-collapse.md), which concerns attributing continuity established for one bearer to another bearer.

```text
Continuity-Bearer Collapse:
the wrong thing is said to be continuous

Gap–Discontinuity Equivalence:
lack of observation is treated as proof that continuity failed
```

## Related ontology distinctions

Relevant ontology concepts may include:

- `ContinuityClaim`
- `State`
- `Identity`
- `Self`
- `Trajectory`
- `Event`
- `MemoryRecord`
- `ProvenanceEvidence`
- `SpecificAIIdentity`

Taxonomy classification does not alter the meanings of those ontology terms.

## Locked short form

> Unobserved is not equivalent to absent. A gap limits what can be established about continuity; it does not by itself establish discontinuity.
