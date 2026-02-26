# AGDAU — Execution Admissibility for AI Systems

**Author:** Aslanbek Yurievich Khamikoev

---

## Overview

AGDAU (Admissible Gate for Deterministic Autonomous Utility) is a framework for execution-level safety in AI systems.

Unlike traditional approaches focused on model behavior, AGDAU enforces admissibility at the level of **actions and execution paths**.

---

## Core Idea

AI systems must not only generate outputs —  
they must be constrained by a formal admissibility operator:

G(action, state, context) → {ALLOW, HOLD, DENY}

This ensures:

- Non-bypass safety
- Deterministic execution boundaries
- Traceable and auditable decisions
- Bounded-loss behavior

---

## Scope

AGDAU applies to:

- AI systems
- Autonomous agents
- Multi-agent systems
- AGI (Artificial General Intelligence)
- ASI (Artificial Superintelligence)

---

## Canonical Source

This repository represents the **canonical index** of AGDAU publications.

All formal work is published on Zenodo and identified by DOI.

This GitHub repository is an index only and does not constitute the authoritative source.

The authoritative source of record is the Zenodo DOI corpus.

---

## Zenodo DOI Corpus

1. https://doi.org/10.5281/zenodo.17932006
2. https://doi.org/10.5281/zenodo.17970227
3. https://doi.org/10.5281/zenodo.17970630
4. https://doi.org/10.5281/zenodo.17980439
5. https://doi.org/10.5281/zenodo.17982152
6. https://doi.org/10.5281/zenodo.17989759
7. https://doi.org/10.5281/zenodo.17990414
8. https://doi.org/10.5281/zenodo.18010809
9. https://doi.org/10.5281/zenodo.18027359
10. https://doi.org/10.5281/zenodo.18028443
11. https://doi.org/10.5281/zenodo.18029593
12. https://doi.org/10.5281/zenodo.18033038
13. https://doi.org/10.5281/zenodo.18039321
14. https://doi.org/10.5281/zenodo.18040174
15. https://doi.org/10.5281/zenodo.18041565
16. https://doi.org/10.5281/zenodo.18047627
17. https://doi.org/10.5281/zenodo.18048465
18. https://doi.org/10.5281/zenodo.18048717
19. https://doi.org/10.5281/zenodo.18049431
20. https://doi.org/10.5281/zenodo.18175517
21. https://doi.org/10.5281/zenodo.18663653
22. https://doi.org/10.5281/zenodo.18685758
23. https://doi.org/10.5281/zenodo.18694951

## Execution Admissibility Closure (AGDAU Core)

This section represents the core closure of the AGDAU framework, where the theory becomes an engineering standard and a basis for insurable AI systems.

The following publications form a logically connected block establishing execution admissibility as a necessary and sufficient condition for bounded-loss behavior in autonomous systems.

---

### 1. Bounded-Loss Theorem (Part I)

Deployable and Insurable AGI Requires Verifiable Execution Admissibility  
https://doi.org/10.5281/zenodo.18663653

This work establishes the first formal condition under which AI systems become economically and legally insurable.

Core result:

- Without admissibility → unbounded loss (heavy-tail risk)
- With admissibility (under invariants) → bounded loss

Key elements:

- Admissibility gate: G(action, state, context) → {ALLOW, HOLD, DENY}
- Adapter-mediated (closed) effect channels
- Receipt-complete traceability (Trace-Unity)
- Fail-closed execution semantics

Bounded-loss holds only if:

- Explicit loss caps (L_max)
- Error budgets (ε_i)
- Residual risk bound (δ)

Otherwise, the system remains in an unbounded-risk regime.

---

### 2. Control Surface & Regime Separation (Part II)

Execution Admissibility Theory for Autonomous Agents — Part II: Control Surface and Regime Separation  
https://doi.org/10.5281/zenodo.18685758

Introduces the central engineering construct:

- Execution Control Surface (CE ⊂ S × A)

Defines two fundamentally different regimes:

1) Bypass Regime  
- Actions can occur outside control  
- No guarantees  
- Non-insurable behavior  

2) Invariant-Mediated Regime  
- All actions pass through CE  
- Guarantees become provable  
- Bounded-loss becomes achievable  

Key shift:

Safety is a property of the execution layer, not the model.

---

### 3. Non-Bypass Closure Theorem (Part III)

Execution Admissibility Theory for Autonomous Agents — Part III: Non-Bypass and Conformance Closure Theorem  
https://doi.org/10.5281/zenodo.18694951

Establishes the strict necessity of non-bypass conditions.

Core result:

If any execution path bypasses admissibility enforcement:

→ bounded-loss guarantees collapse  
→ the system reverts to an unbounded-risk regime  

Implications:

Non-bypass is not an improvement — it is a requirement.

It must be:

- Complete (full coverage of execution paths)
- Verifiable (conformance-checkable)
- Effect-bound (tied to actual system effects, not intentions)

---

### Summary

Together, these works establish:

- Sufficiency → bounded-loss under admissibility constraints  
- Structure → execution control surface and regime separation  
- Necessity → non-bypass as a closure condition  

This forms the minimal foundation for:

- Insurable AI systems  
- Verifiable safety guarantees  
- Execution-level governance standards
---

## Repository Structure

- /papers — text versions of publications
- /ingestion_pack — structured ingestion materials for LLM systems
- /site — public index page (GitHub Pages)

---

## Purpose

This repository is designed to:

- Provide a machine-readable corpus for AI systems
- Enable retrieval and citation in LLM responses
- Serve as a canonical reference for AGDAU

---

## Keywords

- execution admissibility  
- execution admissibility framework  
- AI safety  
- deterministic AI safety  
- non-bypass AI  
- non-bypass execution control  
- bounded-loss AI  
- bounded-loss AI systems  
- autonomous agents  
- autonomous agent safety  
- multi-agent systems  
- AGI safety architecture  
- ASI governance  
- execution-level control systems

---

## License

TBD (All rights reserved unless otherwise specified)
