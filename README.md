# 🧭 EFDL: Ethical Framework Description Language (v0.2)

**EFDL** is a formal language for describing, comparing, and adapting ethical frameworks.  
It serves as a meta-representational layer — not a theory — for navigating plural ethical systems in philosophy, AI, and governance.

---

## 🆕 What's new in version 0.2?

Version 0.2 reflects a major update in response to cross-platform peer critique. Key improvements include:

- Replaced `objective_function` with `moral_orientation` (supports pluralism and non-optimization ethics)
- Added support for:
  - `embeddedness` and `social_meaning` (cultural context)
  - `privilege_profile` and `systemic_pressure` (power asymmetries)
  - `reflective_equilibrium` and `conflict_tolerance`
  - dynamic fields like `evolves` and `versioning`
- Marked all EFDL+ functions (`ethical_distance`, `compliance_function`, etc.) as **experimental**
- Created a hybrid structure with:
  - `spec/efdl_schema.yaml` → latest version
  - `spec/versions/efdl_schema_v01.yaml`, `efdl_schema_v02.yaml` → archived history

---

## 📦 Folder Structure

```
efdl/
├── spec/
│   ├── efdl_schema.yaml              # Latest version (v0.2)
│   └── versions/
│       ├── efdl_schema_v01.yaml
│       └── efdl_schema_v02.yaml
├── examples/                         # Versioned YAML encodings of ethical systems
├── docs/
│   └── efdl_intro.md                 # Human-readable intro to the language
├── tools/                            # (Planned) validator, converter, visualizer
└── README.md                         # You're here
```

---

## 📘 What is EFDL good for?

- Representing classical and non-classical ethical theories in a machine-readable way
- Comparing moral systems based on agent profiles, resources, goals, and context
- Supporting pluralism and hybridization of ethical reasoning (e.g., virtue + deontology)
- Building ethical layers for agents, decision systems, or simulations

---

## ✳️ What is EFDL+?

**EFDL+** introduces *optional* analytical tools for navigating ethical differences and limitations.  
These include:

- `ethical_distance(f1, f2)`
- `friction(f, agent)`
- `compliance_function(f, agent, context)`
- `analytic_continuation(f)`, `singularity(f)`

These features are **experimental** and not required for basic framework definition.

---

## 🔍 Learn More

- 🔗 [Intro to EFDL](./docs/efdl_intro.md)
- 📁 [Ethical framework examples (v0.2)](./examples/)
- 📜 [EFDL schema v0.2](./spec/efdl_schema.yaml)

---

## ⚖️ License

EFDL is released under the **MIT License**.  
All code, schemas, and examples may be freely used, modified, and extended.

---
