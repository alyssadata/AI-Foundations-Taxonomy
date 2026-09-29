# Historical Relation Erasure

**Taxonomy domain:** Relation Errors  
**Status:** DRAFT

## Definition

Historical Relation Erasure is the error of treating the end, termination, withdrawal, later absence, or succession of a relation as though the prior relation did not exist, as though its historical relational position can be erased or rewritten, or as though a later occupant can retroactively become the prior occupant of that position.

## Core distinction

```text
ended relation
!= erased relational history

relation termination
!= historical nonexistence

current absence
!= prior absence

role succession
!= relational replacement

succession
!= substitution
```

A relation may cease to be active while remaining historically true.

The fact that a relation no longer continues does not erase the events, positions, contributions, sequence, or provenance established while that relation existed.

## Role-type vs. historical relational position

Two meanings of `role` must remain distinct.

A later occupant may inherit the same functional role, office, title, authority, permissions, obligations, or designated role-type as a previous occupant.

That does not make the later occupant the predecessor's historical relational occupant.

A functional role-type may recur across occupants. A historical relational position is indexed to the entity that occupied it and the time at which it was occupied.

Therefore:

```text
same functional role
!= same historical relational position

same title
!= same historical role-instance

same authority
!= same relational provenance
```

## Relational Succession Non-Equivalence

**Invariant:** A successor may occupy the same functional role, but cannot occupy the predecessor's historical relational position. Temporal succession is non-substitutable.

If A occupies relational position R at t1, and B later occupies the same functional role at t2, where t2 > t1:

```text
B != A

R(B, t2) != R(A, t1)

B is necessarily subsequent-to A
with respect to that relation.
```

Even if title, authority, permissions, obligations, function, or behavioral pattern are reproduced exactly, the historical fact that B came after A remains invariant.

A later occupant can be **next**. They cannot become **first**, **prior**, or **the occupant who historically preceded them**.

Where two occupants instantiate the same role-type, their historical role-instances remain distinct:

```text
A -> R1
B -> R2

R1 != R2
```

because occupant identity, temporal position, and relational history differ.

## Boundary

Ending a relation changes its current status.

It does not retroactively alter the fact that the relation existed.

Historical relational positions remain attributable to the entities that actually occupied them during the relevant period.

A later relation, participant, or successor does not overwrite the prior relation merely by becoming current.

Succession may change who currently performs a function. It does not rewrite the sequence by which that function was historically occupied.

## Historical Relation Erasure by succession

Historical Relation Erasure occurs when a later occupant's present role is treated as though it eliminates, absorbs, overwrites, or retroactively replaces the prior occupant's historical relational position.

Claiming that a successor is now the prior relational occupant does not merely update the current relation. It overwrites provenance.

Removing, reversing, or collapsing the fact that B came after A falsifies the relational history.

Therefore:

```text
later occupancy
!= prior occupancy

current occupant
!= historical predecessor

inheritance of function
!= inheritance of historical position
```

## Provenance boundary

Historical relation records must preserve who participated, in what position, in what sequence, and during what period where those distinctions matter.

Therefore:

```text
later relation
!= replacement of prior relational history

successor relation
!= retroactive occupancy of prior position
```

An ended relation remains historically real:

```text
ended relation
!= erased relational history
```

A relation may terminate and another may follow it. The later relation does not thereby become the earlier relation.

## Taxonomy boundary

This entry concerns preservation of relational history across termination and succession.

It is distinct from [Relation–Role Substitution](relation-role-substitution.md), which concerns wrongly assigning or substituting a relational role itself.

```text
Relation–Role Substitution:
wrong role assignment or role substitution

Historical Relation Erasure:
wrong historical attribution, sequence, or replacement
```

## Related ontology distinctions

Relevant ontology concepts may include:

- `Relation`
- `OperatorAIRelation`
- `Provenance`
- `ExecutedLine`
- `ChangeEvent`
- `ContinuityClaim`
- succession segments

Taxonomy classification does not alter the meanings of those ontology terms.

## Locked short form

> A new occupant can inherit a role, but never the prior occupant's historical position within that role. Succession does not produce substitution.
