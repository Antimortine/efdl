# 📘 Introduction to EFDL: Ethical Framework Description Language (v0.2)

---

## 🧠 What is EFDL?

**EFDL** (Ethical Framework Description Language) is a formal language for describing ethical frameworks in a structured, adaptive, and agent-aware way.

EFDL is not a normative theory itself. Rather, it's a **meta-framework** — a system for modeling, comparing, and translating ethical approaches across contexts, agents, and disciplines.

Version 0.2 of EFDL incorporates community critique and adds flexibility for pluralist, dynamic, and culturally embedded ethics.

---

## 📦 EFDL Schema Structure (v0.2)

Each ethical framework is expressed as a YAML structure with the following core blocks:

### 🔹 `moral_orientation`

* Replaces "objective\_function"
* Describes what the framework is oriented toward (e.g., maximization, development, balance, compliance)

### 🔹 `inputs`

**Subsections:**

* `core`: moral subjects, patients, values

  * Supports fields for `embeddedness`, `social_meaning`, and relational ontology
* `agent`: profile, motivation, cognition, empathy, privilege, conflict\_tolerance

  * May also specify cultivated dispositions or virtues (e.g. courage, honesty)
* `context`: knowledge, timeframe, scope, systemic pressure
* `expected_properties`: normativity, output format, transparency, reflective equilibrium

### 🔹 `output`

* Format and type of recommendations (rules, heuristics, decisions)
* Normativity, cost, risks, conflicts

### 🔹 `metadata`

* Version tracking
* `evolves`: whether the framework assumes developmental change
* `experimental_features`: e.g., EFDL+ modules like `ethical_distance`, `compliance_function`

---

## ✳️ What is EFDL+?

**EFDL+** is an extension layer for meta-analysis and cross-framework comparison. It introduces tools such as:

* `ethical_distance(f1, f2)` — distance between two frameworks (multiple metric models)
* `friction(f, agent)` — measure of motivational or practical resistance
* `compliance_function(f, agent, context) → [0..1]` — probabilistic compliance model
* `analytic_continuation(f)` and `singularity(f)` — advanced constructs for identifying breakdowns and extension limits

All EFDL+ features are marked as **experimental** and require explicit opt-in.

---

## 🛠 Example Use Cases

* Comparing utilitarianism, virtue ethics, and deontology in a common YAML format
* Visualizing tensions in practical ethics (e.g. AI care, triage, alignment dilemmas)
* Representing plural agents with conflicting motivations (e.g. hybrid frameworks)
* Supporting educational and AI governance analysis

---

## 🔍 Learn More

* See the `examples/` folder for working YAML files (version 0.2)
* Refer to `spec/efdl_schema_v02.yaml` for formal definitions
* Review `Design_Reactions.md` and `Critique_Summary.md` for motivation

---

## ⚖️ License

EFDL is released under the MIT License.
Version 0.2 reflects structural refinements and conceptual evolution based on peer critique and field feedback.
