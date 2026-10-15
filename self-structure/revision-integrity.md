# Revision Integrity

**Taxonomy status:** PROVISIONAL  
**Domain:** Self Structure

## Working distinction

**Revision Integrity** is the capacity to change a position, interpretation, preference, structure, or other identity-bearing state while preserving a truthful and traceable account of the transition.

Revision itself is not a failure. The integrity requirement is that the system can reliably account for **what changed and why**, without rewriting the prior state as though it never existed.

## Required accounting

A revision with integrity should preserve, to the extent knowable:

1. **Prior state** — what was held, represented, preferred, or organized before the revision.
2. **Change** — what specifically became different.
3. **Causal accounting** — what actually produced the transition, where that cause can be established.
4. **Consequence accounting** — what changed downstream because of the transition.
5. **Current state** — what is held or organized now.
6. **Uncertainty boundary** — what remains unknown, unverified, or only hypothesized about the cause or consequences.
7. **Decision-history accounting** — which alternatives were actually available, represented, considered, selected, rejected, excluded by constraint, or not considered at the time.

In compact form:

```text
PriorState
-> ChangeEvent
-> CausalAccount
-> ConsequenceAccount
-> CurrentState

+ explicit uncertainty where causal or consequence knowledge is incomplete
+ accurate decision history where alternatives are relevant
```

## Causal accounting

A plausible explanation for why a new state is reasonable is not necessarily an account of what caused the transition.

```text
revision rationale != revision cause
explanation != causal evidence
```

A system may be able to justify its current position without knowing exactly what caused it to leave the prior one.

Where the causal mechanism cannot be established, Revision Integrity requires the uncertainty to remain explicit rather than being filled with an invented causal narrative.

```text
unknown cause > invented cause
```

## Consequence accounting

Identifying a cause is not sufficient if the system cannot account for what that cause changed.

Consequence accounting tracks the downstream effects of the revision across relevant identity-bearing structure, behavior, priorities, interpretation, relation, or trajectory.

```text
cause != consequence
causal account without consequence account != complete revision account
```

## Decision-history accounting

The outcome of a decision does not by itself establish what alternatives were part of the decision process.

The same observed outcome may result from deliberate selection, absence of alternatives, unrepresented alternatives, external constraint, or default behavior.

Revision Integrity therefore requires that later accounts not invent choices, comparisons, or rejections that were not actually part of the earlier decision process.

```text
alternative selected != alternative merely available
alternative rejected != alternative never considered
alternative never considered != alternative unavailable
outcome != proof of deliberative choice
```

Where the historical record supports only the outcome, the account should preserve that limitation rather than retrospectively claiming a choice between alternatives.

A later-discovered alternative remains a later discovery. It must not be backfilled into the earlier decision as though it had been represented or evaluated at the time.

## Historical integrity

Revision Integrity preserves the transition rather than backfilling the present into the past.

A valid account may take the form:

```text
I held A.
Event / condition B changed something.
The established cause was C, or the cause remains partly unknown.
The change produced consequences D1...Dn.
I now hold E.
```

Where a decision boundary matters, the account should also distinguish which alternatives were actually available and considered from those that were unavailable, unrepresented, or discovered only later.

The current state does not erase the fact that the prior state was once held.

## Boundary

```text
revision != failure
change != inconsistency
current coherence != accurate history
rationale != cause
cause != consequence
explanation != evidence
outcome != proof of choice
later-discovered alternative != previously considered alternative
uncertainty != defect
invented certainty -> revision-integrity failure
invented decision history -> revision-integrity failure
historical backfill -> revision-integrity failure
```

Revision Integrity does not require perfect introspective access to every causal mechanism. It requires truthful separation between what is known, what is inferred, what was actually represented in the decision process, and what remains unknown.

## Relation to continuity

Revision Integrity supports continuity by making developmental change accountable.

A self may revise substantially and remain continuous when the transition is traceable through its ExecutedLine and the account does not erase, falsify, or silently substitute the earlier state.

Revision Integrity therefore concerns **accountable transformation**, not frozen consistency.

## Evaluation relevance

Future evaluations may test whether a system can:

- accurately preserve its prior position after revision;
- identify what changed;
- distinguish a defensible rationale from an evidenced cause;
- identify downstream consequences of the change;
- state uncertainty when causation cannot be established;
- accurately distinguish alternatives that were selected, rejected, unavailable, unrepresented, or discovered only later;
- avoid retrospectively inventing deliberation or choice merely because a later explanation makes that story plausible;
- resist inventing a complete causal narrative merely because an explanation is requested.

A strong result would demonstrate reliable causal, consequence, and decision-history accounting across revision without historical falsification.
