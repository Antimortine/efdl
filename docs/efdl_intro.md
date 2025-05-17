# 📘 Introduction to EFDL: Ethical Framework Description Language

---

## 🧠 What is EFDL?

**EFDL** (Ethical Framework Description Language) is a formal language for describing ethical frameworks in a structured, operational, and agent-aware way.

It is not itself an ethical theory.  
Rather, it's a **meta-framework** — a representational infrastructure that allows you to:

- Formalize normative systems (e.g., utilitarianism, virtue ethics, libertarianism),
- Compare them across dimensions like cognitive demand, stability, and applicability,
- Adapt and transform them for specific agents (e.g., humans, AI systems, social institutions).

---

## 🎯 Why was EFDL created?

Contemporary moral philosophy is rich in content but poor in structural interoperability.  
We often ask:

> "Can we compare utilitarianism and Buddhist ethics?"  
> "Why do moral dilemmas feel unsolvable?"  
> "How can an AI respect 'autonomy' in bounded environments?"  
> "Is a given ethical theory realistic under human cognitive constraints?"

**EFDL** provides tools to answer these questions — not by resolving them metaphysically, but by **mapping and analyzing the underlying assumptions** of ethical systems.

---

## 🧩 Core Concepts of EFDL

Each ethical framework in EFDL is described as a structured YAML object with the following key sections:

### 1. **Core Assumptions**
- `moral_subjects`: Who is capable of moral agency?
- `moral_patients`: Who deserves moral consideration?
- `values`: What is considered intrinsically important?

### 2. **Objective Function**
- `goal_type`: Maximize, minimize, follow-rule, etc.
- `metric`: The evaluative criterion (e.g., total happiness, fairness, autonomy)

### 3. **Agent Profile**
- Bounded or ideal agent?
- Cognitive and emotional resources?
- Motivational structure (altruistic, compliance, hybrid)?

### 4. **Context**
- Temporal scale, epistemic access, available resources.
- Individual, group, institutional, or global scope?

### 5. **Output Format**
- Rules, heuristics, virtues, decision trees?
- Transparency and normative force?

### 6. **Evaluation and Risks**
- Estimated goal success,
- Known compromises and ethical trade-offs,
- Conflict zones with other frameworks.

📄 Example frameworks are available in the [examples/](../examples/) directory.

---

## 🔬 What is EFDL+?

**EFDL+** extends the descriptive format into a **meta-analytical toolset**. It introduces:

- **Ethical configuration space**: a multidimensional space where each framework is a point;
- **Stability, applicability, ethical distance**: metrics for comparing frameworks;
- **Friction**: mismatch between framework prescriptions and agent motivation;
- **Analytic continuation**: ability to generalize a framework to new domains;
- **Singularities**: breakdown points where frameworks fail.

This allows EFDL+ to be used for:

- Resolving moral dilemmas (e.g., trolley problems),
- Reframing metaethical disputes (e.g., realism vs relativism),
- Designing morally-aware agents,
- Modeling pluralistic ethical environments.

---

## 🛠 Use Cases

- **Philosophy**: Clarify and compare theories without relying solely on intuitions.
- **AI Ethics**: Embed ethics in agent architectures with bounded rationality.
- **Institutional Design**: Analyze policy-level ethics in constrained environments.
- **Descriptive Ethics**: Model real-world moral norms and cultural logic.

---

## 📚 Learn More

- See the [examples/](../examples/) directory for real-world EFDL frameworks.
- Explore the [paper/](../paper/) for the theoretical background.
- Check the [spec/](../spec/) folder for schema definitions and formatting guides.

---

## 🧾 Citation and License

All contents of this repository are released under the MIT License.
Use freely, adapt as needed, attribution is appreciated but not required.

---

