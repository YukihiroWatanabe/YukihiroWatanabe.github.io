# YukihiroWatanabe.github.io

Visual explanations of **Nakano-style Associatron** and related associative-memory dynamics:
cue → competition → convergence (recall), with diagrams and small runnable demos.

This repository is written as a technical notebook for:
- understanding associative memory as **dynamics** (not “lookup”)
- building small, reproducible demos (HTML / JS)
- documenting historical references with a calm, source-first style

---

## What is “Associatron” (Nakano, 1972)?

Kaoru Nakano proposed “Associatron” as an associative memory model that can
store patterns and reconstruct a whole from a part (content-addressable recall).
A canonical reference is:

- K. Nakano, “Associatron—A Model of Associative Memory,” IEEE Trans. SMC, 1972.  
  (See bibliographic entries: DBLP / CiNii)

---

## What this site is (and is not)

**This site is:**
- a set of visual notes and runnable toy implementations
- focused on *mechanism*: cue injection → context/room competition → recall
- written to be readable without heavy math

**This site is not:**
- a ranking or “credit war” page
- a critique campaign against any named model or community
- a comprehensive survey (it stays narrow and reproducible)

---

## Pages

- Historical note: Nakano (1972) and the lineage of associative-memory ideas  
  → `Historical Note: Nakano (1972) and Associative Memory as Dynamics`

---

## License

This project is released under the MIT License.

Copyright © 2026 Yukihiro Watanabe

---

## Development Background

This project was developed through an extended iterative process involving multiple perspectives.

The system design was explored through intensive discussions with AI tools (ChatGPT and Grok), often involving disagreement, correction, and redesign rather than straightforward code generation.

In addition to AI-assisted development, the design was repeatedly challenged by feedback from outside the technical domain:

- A non-technical, everyday human perspective questioned assumptions such as:
  - reliance on predefined external concepts,
  - immediate recall behavior,
  - and the expectation that the system should respond instantly rather than develop gradually.
  
  This led to the idea that the system should behave more like early human cognition — slower, incomplete, and developmental, “like a baby learning.”

- Practical engineering feedback from system development staff pointed out implementation issues, structure problems, and code-level concerns, forcing continuous refinement and simplification.

Rather than following a fixed theoretical model, the architecture evolved through continuous challenge from:
- AI reasoning partners,
- non-technical human intuition,
- and practical engineering constraints.

All conceptual direction, system architecture, and final decisions were made by Yukihiro Watanabe.

The current implementation reflects a human-driven design process shaped by persistent questioning and cross-disciplinary feedback.


---
## What is new in this work?

This project explores associative memory not as a fast pattern completion mechanism, but as a developmental and context-dependent cognitive process.

The key ideas are:

- External input is treated as a **perturbation (initial condition)** rather than a command.
- Recall is not immediate lookup, but an **emergent result of internal competition and convergence**.
- Memory is organized along an external time axis (“episode rooms”), allowing distant contexts to compete.
- The system is intentionally allowed to be **slow, incomplete, and uncertain**, reflecting early human cognition rather than optimized machine response.

The focus of this work is not higher accuracy or larger models, but a shift in perspective:
from instantaneous prediction to internally driven recall dynamics.

---

## Research Note

This repository is a research and educational demonstration of associative memory dynamics (Nakano-style Associatron).

External inputs (mouse / camera) are treated as **perturbations (initial conditions)**.  
The recalled state emerges from internal competition and convergence, rather than from explicit commands.


