# STATUS

## Controllable AI  
### Specification & Governance Status Document

---

## 1. Document Purpose

This document defines the **stability status, versioning policy, and governance rules**
for all materials contained in the **Controllable AI** root repository.

Its purpose is to prevent:

- Silent semantic drift
- Retroactive reinterpretation
- De facto weakening of constraints
- Governance authority capture by implementations

This document is **normative** with respect to repository governance.

---

## 2. Current Status

- **Specification Version:** Controllable AI v1.0  
- **Status:** **Frozen (Non-Regressive)**  
- **Effective Date:** Upon initial publication  

“Frozen” means:

- The semantic meaning of all normative statements is fixed
- The structural role of Controllable AI is fixed
- Governance positioning is fixed

No future change may contradict the intent or constraints
defined in the frozen documents.

---

## 3. Scope of Freeze

The following components are explicitly frozen:

### 3.1 Normative Specification

- `/SPECIFICATION/Controllable_AI_v1.0.md`

This file defines the **minimum mandatory structural requirements**
for Controllable AI systems.

Its core principles are non-negotiable, including but not limited to:

- AI never holds final decision authority
- Human responsibility is explicit and exclusive
- Execution-time veto is mandatory
- Decisions must be deterministic, replayable, and auditable

---

### 3.2 Position Statements

- `/POSITION_STATEMENTS/*`

Position Statements define the **structural placement**
of Controllable AI and its implementations within AI Governance.

They are frozen to prevent scope expansion, authority escalation,
or misclassification.

---

## 4. Versioning Policy

### 4.1 Allowed Changes

Future versions of the Controllable AI Specification:

- MAY clarify language
- MAY add constraints
- MAY tighten requirements
- MAY add new veto conditions
- MAY add sector-specific appendices

---

### 4.2 Prohibited Changes

Future versions MUST NOT:

- Remove or weaken any veto condition
- Grant AI final decision authority
- Reduce auditability or replayability requirements
- Transfer responsibility away from humans
- Reclassify implementations as governance authorities

Any derivative work that violates these constraints
is **non-compliant by definition**.

---

## 5. Governance Authority Model

- **Controllable AI** is a governance-level legality construct
- This repository is the **authoritative source** of its definition
- No implementation repository may redefine or override it

Implementation systems (e.g. operating architectures, runtimes, DSLs):

- Are optional
- Are replaceable
- Are non-authoritative
- Must conform to this repository if claiming compliance

---

## 6. Relationship to Implementations

This repository does not endorse, certify, or privilege
any specific implementation.

Including but not limited to:

- EDCA OS
- LSR Runtime
- Yuer DSL
- Domain-specific runtimes or kernels

Compliance is determined **structurally**, not by lineage or origin.

---

## 7. Amendment Process

Any proposal to modify this repository MUST:

1. Explicitly declare whether it is:
   - Clarification
   - Constraint tightening
   - Additive extension
2. Demonstrate non-regression
3. Preserve execution-time veto authority
4. Preserve exclusive human responsibility

Proposals that do not meet all criteria
**must be rejected without review**.

---

## 8. Interpretation Priority

In the event of ambiguity:

1. Normative Specification takes precedence
2. Position Statements take precedence over implementations
3. Structural constraints take precedence over intent claims
4. Execution-time legality takes precedence over performance or utility

---

## 9. Final Statement

Controllable AI is not a trend, framework, or product category.

It is a **structural legality requirement** that exists
to protect execution-time human authority.

Once frozen, this requirement does not evolve with fashion,
market pressure, or technological enthusiasm.

---

**Status: Frozen**  
**Regression: Not Permitted**
