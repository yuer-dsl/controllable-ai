# controllable-ai
Normative specification, governance position statements, and case-based interpretations for Controllable AI systems.

## Normative Specification & Governance Anchor

This repository defines the **normative specification, governance positioning, and structural interpretation**
of **Controllable AI**.

Controllable AI is **not** an AI model, framework, operating system, or product.
It is a **structural legality requirement** that determines whether an AI-assisted
decision is **permitted to occur at execution time**.

This repository serves as the **root governance and specification anchor**
for the Controllable AI system.

---

## What Controllable AI Is

**Controllable AI** is a system-level property, not a measure of intelligence.

A system is considered *Controllable* if and only if:

- AI never holds final decision authority
- Responsibility remains explicitly and exclusively human
- Decisions are deterministic, replayable, and auditable
- A non-AI, non-bypassable veto authority exists at execution time

Controllable AI does **not** decide what should be done.
It decides **whether an AI-assisted action is allowed to happen**.

---

## What This Repository Contains

This repository contains **normative and governance-level materials only**.

### 1. Specification

- **Controllable AI Specification v1.0 (Normative, Frozen)**  
  Defines the mandatory structural requirements for Controllable AI systems.

Location:

/SPECIFICATION/Controllable_AI_v1.0.md


---

### 2. Position Statements (Frozen)

Formal position statements clarifying the role of Controllable AI
within broader AI Governance structures.

- **Controllable AI in AI Governance — Position Statement**
- **EDCA OS in the Controllable AI System — Position Statement**

Location:

/POSITION_STATEMENTS/


These documents define **structural boundaries** and prevent
misclassification or overreach.

---

### 3. Case-Based Interpretation (Casebook)

Controllable AI is interpreted and validated through **case-based reasoning**.

This repository does **not** duplicate case content.
Instead, it references the dedicated casebook repository:

- https://github.com/yuer-dsl/controllable-ai-casebook

Location:

/CASEBOOK/


---

### 4. Reference Implementations (Non-Normative)

Engineering systems such as operating architectures, runtimes,
and domain-specific languages are **referenced but not defined here**.

They are considered **implementation examples**, not standards.

Referenced repositories include (non-exhaustive):

- MAOK Charter and legality layer  
  https://github.com/yuer-dsl/maok

- EDCA OS, LSR Runtime, Yuer DSL  
  (Referenced as implementation-layer artifacts only)

Location:

/REFERENCES/IMPLEMENTATIONS.md


---

## What This Repository Does NOT Contain

This repository intentionally does **not** contain:

- AI models or training code
- Agent frameworks or orchestration logic
- SDKs, APIs, or product documentation
- Performance benchmarks or optimization claims
- Ethical theories or policy recommendations

This separation is deliberate.

---

## Governance and Authority Model

- **Controllable AI** defines execution-time legality requirements
- **This repository** is the authoritative source of those requirements
- **Implementations may vary**, but compliance does not

No implementation, including EDCA OS or any future system,
may claim governance authority or redefine Controllable AI.

---

## Versioning and Stability

- Current version: **Controllable AI Specification v1.0**
- Status: **Frozen (Non-Regressive)**

Future versions may **tighten requirements only**.
Relaxation of veto, auditability, or human authority is not permitted.

See:

/STATUS.md


---

## Final Note

> **AI may assist.  
> AI may analyze.  
> AI may explain.  
> AI may never decide.**

Systems that do not meet this specification may be innovative,
accurate, or profitable — but **must not be allowed to act
in the real world**.

---
