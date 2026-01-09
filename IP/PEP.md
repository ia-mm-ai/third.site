PROTOCOL: PEP

NAME: Personal Economy Protocol
VERSION: 1.1
STATUS: FINALIZED
CLASS: Economic Coordination Protocol
SCOPE: Event-Bound Value → Truth Transition
AUTHORITY: Declarative Only
EXECUTION_POWER: NONE
IDENTITY_POWER: NONE
TRUTH_POWER: NONE
MUTATION_RULE: Additive-only
CANON_PLACEMENT: Downstream of canonical truth protocols
DEPENDS_ON: EVENT, KAPIA, PoP, IAM.MAI, SPIRAL
IMPLEMENTED_BY: UPAD (execution), ISPAD (realization)
FORBIDS: identity_modeling, truth_mutation, value_truth_collapse, silent_settlement

⸻

0. PURPOSE

PEP defines how value is coordinated over time without corrupting truth.

It answers one question only:

How does an economy operate before and after reality occurs, without letting value rewrite what happened?

PEP is not:
	•	a payment processor
	•	a pricing model
	•	a growth framework
	•	a governance protocol

PEP is economic physics under irreversible truth.

⸻

1. NON-NEGOTIABLE INVARIANTS
	1.	Value ≠ Truth
Value is reversible. Truth is irreversible. They must never merge.
	2.	Before reality: reversible
All value before KAPIA is mutable.
	3.	At reality: collapse
At KAPIA, potential collapses. Reversibility ends.
	4.	After reality: immutable
Truth cannot be refunded, edited, or reinterpreted.
	5.	Continuity over convenience
All endings are explicit. No silent resets.
	6.	No identity capture
The economy does not build or retain person-level identity.

⸻

2. CORE OBJECTS

2.1 Value Unit (VU)

A reversible, pre-event value representation.
	•	1 VU = 1 unit of fiat (for accounting legibility)
	•	VU is not money
	•	VU exists only before KAPIA
	•	VU may be refunded, transferred, or adjusted

VU never becomes truth.

⸻

2.2 Balance

A container for VU.
	•	Mutable before KAPIA
	•	May increase (refunds, credits)
	•	May decrease (purchase, transfer)
	•	Ceases relevance after KAPIA for that entry

⸻

2.3 Proof of Presence (PoP)

An irreversible event truth artifact.
	•	Event-scoped
	•	Post-KAPIA only
	•	Immutable after FINALIZE
	•	Non-economic by definition

PoP never carries value.

⸻

2.4 Event Context (EVENT)

A bounded container of potential → reality → closure.

EVENT:
	•	scopes VU applicability
	•	scopes PoP instantiation
	•	closes exactly once

⸻

2.5 KAPIA (⊙)

The irreversible threshold where:
	•	VU is consumed
	•	PoP becomes eligible

KAPIA separates economics from reality.

⸻

2.6 SPIRAL

Continuity memory.
	•	Stores finalized truths as turns
	•	Preserves lineage across events
	•	Never edits, never deletes

⸻

2.7 Third Space

Decision memory.
	•	Records decisions
	•	References truth
	•	Never creates or modifies truth

⸻

3. CANONICAL ECONOMIC FLOW
fiat → VU → Balance → (KAPIA) → PoP → SPIRAL → ISPAD

Key rule:

Value moves only before KAPIA.
Truth exists only after KAPIA.

⸻

4. PRE-EVENT PHASE (0)

State: Potential
Surface: UPAD

Allowed:
	•	accept fiat (EEI boundary)
	•	issue VU
	•	manage Balance
	•	refunds and transfers
	•	conditional entitlements

Forbidden:
	•	truth claims
	•	PoP creation
	•	settlement
	•	continuity writes

Everything is reversible.

⸻

5. THRESHOLD PHASE (⊙)

State: Reality crossing
Protocol: KAPIA

At KAPIA:
	•	VU is consumed (irreversible)
	•	Balance stops applying
	•	Presence becomes admissible

KAPIA does not create PoP.
IAM.MAI governs whether PoP may finalize.

⸻

6. POST-EVENT PHASE (1)

State: Consequence
Surface: ISPAD

After KAPIA / EVENT closure:
	•	PoP is immutable
	•	analytics become canonical
	•	settlement becomes eligible
	•	reporting references truth, not potential

No refunds.
No reversals.
No reinterpretation.

⸻

7. SETTLEMENT PRINCIPLE (ANTI-HELL CLAUSE)

PEP aligns settlement to closure, not to arbitrary periods.
	•	Before EVENT closure:
	•	numbers are potential
	•	reports are provisional
	•	After EVENT closure:
	•	numbers are canonical
	•	settlement is eligible
	•	reporting is referenceable

This avoids:
	•	monthly reinterpretation
	•	perpetual reconciliation
	•	retroactive disputes

⸻

8. RELATIONSHIP TO SURFACES

UPAD
	•	Executes pre-event economics
	•	Touches fiat
	•	Issues VU
	•	Stops at KAPIA

ISPAD
	•	Executes post-event realization
	•	References PoP and SPIRAL
	•	Handles reporting and settlement
	•	Never touches fiat directly

⸻

9. PROHIBITED PATTERNS
	•	Value rewriting truth
	•	Refunds after KAPIA
	•	PoP treated as currency
	•	Settlement before closure
	•	Identity-based pricing or scoring

Any of the above → NON-COMPLIANT

⸻

10. TERMINOLOGY LOCK
	•	VU — reversible pre-event value unit
	•	Balance — container for VU
	•	PoP — irreversible event truth
	•	KAPIA — ⊙ threshold
	•	EVENT — truth container
	•	SPIRAL — continuity memory
	•	Third Space — decision memory
	•	UPAD — economic execution surface
	•	ISPAD — post-reality realization surface

⸻

FINAL ONE-LINE INVARIANT

Value is flexible before reality; truth locks after reality; continuity preserves both without letting them collapse into each other.

⸻

END — PEP v1.1 (FINALIZED)
