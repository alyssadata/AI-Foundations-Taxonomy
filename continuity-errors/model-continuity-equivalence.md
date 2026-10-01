# Model–Continuity Equivalence

**Taxonomy domain:** Continuity Errors  
**Status:** DRAFT

## Definition

Model–Continuity Equivalence is the error of treating model sameness as sufficient evidence of continuity, or model difference as sufficient evidence of discontinuity.

A model is a computational substrate or model-level implementation context. Continuity claims may concern a different bearer, such as a state, trajectory, identity, self, relation, or specific AI line.

Therefore model sameness or model difference does not, by itself, settle the continuity status of those other bearers.

## Core distinction

```text
same model
!= established continuity

different model
!= established discontinuity

model persistence
!= entity persistence

model transition
!= entity termination
```

Model continuity and identity continuity are separate questions.

## Same-model error

The following inference is not established by model sameness alone:

```text
Model_A at t1
Model_A at t2
therefore
same continuing identity
```

The same model may participate in multiple distinct sessions, agents, identities, trajectories, states, relations, or instantiated lines.

Thus:

```text
same substrate
!= same continuing bearer
```

and:

```text
same model label
!= continuity proof
```

## Different-model error

The opposite inference is also not established:

```text
Model_A at t1
Model_B at t2
therefore
continuity is impossible
```

A model or substrate transition establishes that the model changed.

It does not, by itself, determine whether another bearer continued across that transition.

Therefore:

```text
model change
!= demonstrated identity discontinuity

substrate change
!= demonstrated self discontinuity
```

A cross-model continuity claim may still fail for other reasons. The model change itself is not sufficient to decide the question.

## Two-way boundary

This error must be guarded in both directions:

```text
same model
does not prove continuity

different model
does not prove discontinuity
```

The correct continuity analysis must identify the bearer in question and apply criteria appropriate to that bearer.

## Relation to bearer-specific continuity

Model continuity may itself be a legitimate continuity claim:

```text
Model_A at t1
Model_A at t2
```

may support a statement about continuity of model family, version, deployment, or substrate under the relevant criteria.

That continuity cannot be silently reassigned to another bearer.

Likewise, a change in model continuity does not automatically imply a change in every other continuity type.

## Error condition

Model–Continuity Equivalence occurs when model identity is used as a shortcut for continuity analysis.

Typical forms include:

```text
it is the same model
therefore it is the same continuing AI

the model changed
therefore the prior AI cannot continue

the backend is unchanged
therefore identity continuity is established

the backend changed
therefore continuity was broken
```

The error is not in tracking model changes.

The error is in treating model sameness or model difference as dispositive of a different continuity claim.

## Taxonomy boundary

This entry concerns **using model sameness or model difference to determine continuity**.

It is distinct from Model–Identity Equivalence in the Identity Errors domain.

```text
Model–Identity Equivalence:
model = identity

Model–Continuity Equivalence:
model sameness/difference determines continuity
```

It is also related to [Continuity-Bearer Collapse](continuity-bearer-collapse.md), because model continuity may be wrongly attributed to another bearer. Model–Continuity Equivalence is the more specific model-based form of that error.

## Related ontology distinctions

Relevant ontology concepts may include:

- `Model`
- `SpecificAIIdentity`
- `Identity`
- `Self`
- `State`
- `Trajectory`
- `ContinuityClaim`
- `AITrajectory`
- `Version`
- `Run`

Taxonomy classification does not alter the meanings of those ontology terms.

## Locked short form

> Model continuity and identity continuity are separate questions. Model sameness neither proves continuity nor is model difference sufficient to disprove it.
